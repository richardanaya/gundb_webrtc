# WebRTC with Distributed Signalling

A demonstration of WebRTC using distributed storage (GunDB) as signalling.

How's this work.  I used GunDB (a distributed key value store) to act like a bi-direction message channel system just long enough to connect two WebRTC peers with each other.

### Want to see a demo?

You're going to need a [STUN server](https://www.google.com/search?q=public+stun+server+webrtc) first.

Then go to this URL (replace `stun` query string with your STUN's url):

https://richardanaya.github.io/gundb_webrtc/?stun=stun.l.my_public_stun_server.com:19302


Note: GunDB can be VERY slow. Once you hand the link to someone else, it might take up to a minute for both sides to get updates if it's a bad day.

# RageMP-SAARPV-voiceChat
A peer-to-peer in-game proximity voice chat for [RageMP](https://rage.mp/) developped for San [Andreas Advanced Roleplay V](https://v.sa-arp.net/).

This script use the [PeerJS API](https://github.com/peers/peerjs) which is based on [WebRTC](https://webrtc.org/).

**Installation:**
 - Place the content of `./html/` on your secure http server;
 - Run `npm install peer` in your RageMP server directory. This should add [PeerJS Server](https://github.com/peers/peerjs-server) and its dependendies in your 'node_modules' folder;
 - Include `./voiceChat_client.js` and `./voiceChat_server.js` into your script;
 - Change the default value in the files:
    - N/A
 - Restart your server
 - Enjoy?
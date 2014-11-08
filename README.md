Hubot TeamSpeak Tracker
=====================
Allows Hubot to track who enters/exits a TeamSpeak server, as well as report on who is currently connected

[![NPM](https://nodei.co/npm/hubot-teamspeak-track.png?downloads=true)](https://nodei.co/npm/hubot-teamspeak-track/)

Configuration
============
* HUBOT_TEAMSPEAK_IP
* HUBOT_TEAMSPEAK_USER (ServerQuery user)
* HUBOT_TEAMSPEAK_PASSWORD (ServerQuery password)
* HUBOT_TEAMSPEAK_OUT_ROOM (comma separated list of all rooms to output to)
* HUBOT_TEAMSPEAK_VOICE_PORT (optional voice port of the Teamspeak Virtual Server)

Dependencies
============
* `node-teamspeak` >= 1.0.5

Commands
============
* hubot teamspeak - replies with a comma separated list of all connected users

Install
============
npm install hubot-teamspeak-track

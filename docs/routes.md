# **Routes and their purposes**

[Webkit Routes](./routes/webkit-routes.md), routes which send a webpage to be loaded. (ex. Leaderboards, SkateProfile)<br>
[API Routes](./routes/api-routes.md), routes which often recieve data but can do both sending and recieving (ex. Setting up a match, Finding a user profile)<br>
[Unknown Routes](./routes/unknown-routes.md), routes which haven't been found to define a purpose, or are unreachable.

## General routes
Routes which which serve a purpose but don't belong in a singular category, most are designed to return abitary data, rather than set, delete, etc..

### Config (/skate3/config)
both written as <i>/PS3.xml</i> and <i>/XBL2.xml</i> stating their config settings for each platform with each variable being able to be changed.
these are accessed when you login into the server, you can easily view the json structure below
<br>[PS3](http://downloads.skate.online.ea.com/skate3/config/PS3.xml)<br>[Xbox (XBL2)](http://downloads.skate.online.ea.com/skate3/config/XBL2.xml)

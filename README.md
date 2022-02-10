# NeuroGesture using LeapMotion
### Alpha version 0.21; 30 March 2014

Designed by Dr James Teo, Dr Brigitta Zics 
This software is an Alpha version using the [LeapJS](https://github.com/leapmotion/leapjs) in 2014 with dependencies from [node.js](https://github.com/nodejs) and [three.js](https://github.com/mrdoob/three.js/).

##Issues:
Does not work on Gemini V5; Javascript support was deprecated by Ultraleap/Leapmotion in v5 with websockets only through the C, Unity API or Unreal API. 
[https://support.leapmotion.com/hc/en-us/articles/360004493917-Javascript-FAQs](https://support.leapmotion.com/hc/en-us/articles/360004493917-Javascript-FAQs)

:-(

Still works on Orion Software Version: 4.1 from Leapmotion [legacy Orion v4 download](https://developer-archive.leapmotion.com/downloads/external/v4-1-hand-tracking/windows?version=4.1.0) 

![screenshot](screenshot_2014.jpg)

## Modules within the main app
The main version (index.html) uses Node.JS; which requires a server to receive the JSON data. Study code: KCH to access modules.
A simpler version (recorder_JSON.html) uses WebSocket to record JSON directly onto webpage.

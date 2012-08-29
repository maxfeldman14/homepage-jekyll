---
layout: project_entry
category: projects
title: Bombermen
listImage: /images/projects/bombermen.png
displayDate: Spring 2011
meta: Yahoo HackU 2011
description: 
  A WebGL multiplayer Bomberman clone running on Node.js/Now.js
links:
  - url: http://vimeo.com/30568650
    name: Video of Gameplay
---
#Introduction
Bombermen is a real-time multiplayer game playable in the browser. It is 
based off of the classic game, 
[Bomberman](http://en.wikipedia.org/wiki/Bomberman) using 
[WebGL](http://en.wikipedia.org/wiki/WebGL), [Node.js](http://nodejs.org/), and 
[Now.js](http://nowjs.com/)

#Video of Gameplay

<iframe src="http://player.vimeo.com/video/30568650" width="500" height="419" frameborder="0" allowFullScreen="allowFullScreen">
</iframe> 

#Background
Bombermen was conceived and implemented at Yahoo HackU 2011. I, along with 
Amber Feng and Allen Chen decided to learn WebGL and Node.js/Now.js, and 
created Bombermen in less than 10 hours as an exercise in learning the 
frameworks. We received an honorable mention at the hackathon.

#Technical
Bombermen uses simple WebGL to render the objects in 3D on a browser. We 
texture each player's character with their Gravatar. To make the game 
real-time, we used a Node.js server with Now.js to maintain client-server 
interaction.

---
layout: post
title:  "First and raw product demo"
date:   2016-09-08 13:37:00 +0200
---
With this first blog post I want to show you where the development is at, yo ! Raw footage incoming. In this video, you'll see a demonstration of thridi. The scene (FYI my test case scene) is pretty basic : **100 red cubes and a camera rotating on itself (y-axis), the camera is positioned in the middle of that cube field.** After a cringe-worthy introduction I'll update the 3D scene without reloading, or with **hot-reload**, and we'll see changes happening in real time. Here's a list of what you'll see :

  - changing the renderer color (with hot-reload)
  - changing the camera y position (with hot-reload)
  - changing cubes positions and colors (with hot-reload)
  - the caveat of thridi : UUID
  - adding some more cubes (with hot-reload)
  - changing the newly added cubes colors (with hot-reload)
  - adding fog (with hot-reload)
  - a wild bug appears ! actually not a bug, just fog taking its time ...
  - changing the camera rotation in the update() function (w/o hot-reload, yet- this will be enhanced in the future)

<!--more-->

Thridi, fow now, is pretty basic UI-wise. The window is split in half :

  - on the left : the code describing the 3D scene
  - on the right : the 3D scene described by the code

Thrilled ? Then let's watch some 3D, with thridi, thanks to three.js.

<iframe width="560" height="315" src="https://www.youtube.com/embed/F4Rdhq2zvBk" frameborder="0" allowfullscreen></iframe>

I want to keep the UI simple but still, I need *at least* the good-old FPS meter (maybe in some status bar ?). Also I'd like to be able to detect syntax errors that blocks the execution. And then of course, a lot more has to be done on the hot-reload part.

{%include disqus.html %}

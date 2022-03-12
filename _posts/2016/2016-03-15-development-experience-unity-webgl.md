---
id: 85
title: 'Development Experience: Unity WebGL'
date: 2016-03-15T22:14:25+00:00
author: Arzola
layout: post
permalink: /development-experience-unity-webgl/
image: /wp-content/uploads/2016/03/Kongregate-Error.png
categories:
  - 'Game Development Tutorials, Tips &amp; Tricks'
  - Relevant Video Game Industry News
tags:
  - "Arzola's"
  - Development Experiences
  - Image
---
Some time now ago, Chrome launched a new version that dropped all type NPAPI-support. For regular users this might not mean anything, but for Unity developers, this meant that the Unity Web Player would become unusable. Namely, Chrome users (which actually make up a great chunk of the web market) would not be able to see or even try to make use of the Web Player content. This of course means that completed projects and already online copies of games prior to this date will no longer be supported, alas, will become unplayable.

However, this led to the birth of a new type of web player support from Unity: WebGL.

To keep the story short, this new type of player can be played regardless of NPAPI not being supported. Which in theory should completely replace the Unity Web Player and carve the path for a new generation of browser-based games.

But as expected with any new technology, the current versions are still filled with bugs, several that involve not being able to load the game. Or depending on the website or platform you wish to upload it to, it can even be very complicated to correctly upload or implement.

<a href="/images/posts/2016/03/Kongregate-Error.png" target="_blank" rel="attachment noopener wp-att-86"><img class="aligncenter wp-image-86" src="/images/posts/2016/03/Kongregate-Error.png" alt="Kongregate Error"   /></a>

If you are a Unity user and you too are aiming to upload your project to an online platform such as Kongregate, NewGrounds or GameJolt, you have two consider two things:

  * Firstly, and most importantly. That WebGL still has room for A LOT of improvements, given that even though it was aimed to be universally playable, there are still some issues when integrating it with certain resolutions, or memory capacities, that might render the game unplaya zble. To which my suggestion would actually be to either directly contact Unity or their forums regarding your issue, or wait for new builds to address said problems.
  * And secondly, each of these platforms has a certain uploading rules to follow. Kongregate asks you to upload the index.html file, and add a zip containing the Release + TemplateData (.htaccess excluded), or in the case of NewGrounds it is index.html + Release + TemplateData (.htaccess excluded once more). Where not following said instructions, or zipping the files in an unusual way (or straight up just switching the extension from .rar to .zip by force) will end up in one screen like the one shown above

If possible, try distributing your game mostly on non-WebGL formats via GameJolt or similar pages or wait a while until uploading your title. Again, the reason being the still almost brand new state of the WebGL technology, which might bring you more problems than solutions.

Of course, it is a shame that it is no longer simple to play online as before, but that time will eventually come again, we only have to wait.

&nbsp;

And as always,

Thank you for reading my blog.

<!-- AddThis Advanced Settings generic via filter on the_content -->

<!-- AddThis Share Buttons generic via filter on the_content -->
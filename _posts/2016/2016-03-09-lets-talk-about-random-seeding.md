---
id: 47
title: 'Let&#8217;s Talk About: Random Seeding'
date: 2016-03-09T15:40:39+00:00
author: Arzola
layout: post
permalink: /lets-talk-about-random-seeding/
image: /wp-content/uploads/2016/03/daily-1.jpg
categories:
  - "Arzola's Games"
  - 'Game Development Tutorials, Tips &amp; Tricks'
  - KNIGHTS
  - Tutorials
tags:
  - "Arzola's"
  - Development Progress
  - Development Tips
  - Game
  - Image
  - KNIGHTS
  - Programming Tips
  - Unity3D
---
Many games in the market today try to include a certain feature never seen in games from the early days, _procedural generation_.

But what exactly means to &#8220;procedurally generate&#8221; or &#8220;randomly generate&#8221; a game?

[<img class="alignleft" src="http://vignette1.wikia.nocookie.net/spelunky/images/f/fa/Spelunky_Splash.png/revision/latest?cb=20121021183629" alt=""   />](http://vignette1.wikia.nocookie.net/spelunky/images/f/fa/Spelunky_Splash.png/revision/latest?cb=20121021183629)In essence, it means that the game has the ability to provide a fresh new start or level everytime the player or developer desires. While attempting to give a completely different experience compared to previous content. The key value is that it offers _**INFINITE REPLAYABILITY**_ to a game, by always being able to provide new content via pre-established algorithms with the usage of _random values_.

Being with new levels on the press of a button or on a daily basis, many games now base their core mechanics around this feature with the so called &#8220;Rough-Like&#8221; or &#8220;Rough-Lite&#8221; elements.

But what if the developer chooses that everyone should get the _**EXACT SAME EXPERIENCE**_? What if the desired feature came in the shape of a daily or weekly challenge?

One option would be to have a central server where everyone can download said content, however, not all have a connection available at all times to do so. This is where **random seeding** comes in handy.

Computers can&#8217;t be &#8220;random&#8221;, in order to select a value from a certain range, they have to do so in a logical way. For most, if not all cases, whenever asked to fetch a random value a modern computer makes use of the current time and date to make that operation. Since time keeps changing, so will the values they return. Random seeding is in essence **_to lock_ the value they use to make operations.**

Taking KNIGHTS for example, it has the feature to make levels on its own everyday.

<a href="/images/posts/2016/03/Seeding.jpg" target="_blank" rel="attachment noopener wp-att-50"><img class="aligncenter wp-image-50 size-large" src="/images/posts/2016/03/Seeding.jpg" alt="Seeding"   /></a>To explain in few words, KNIGHTS makes 75 daily levels divided into 3 level packs, 25 a piece. To avoid a massive slowdown on start, if the level that the player wants to try has not been selected that day, it will generate it when the player picks it. As you can see this triggers a call to make said level, while giving a number value that is essentially the date + a number from 0 to 74 (or which of the 75 daily levels they want).

And what to we have immediately at the beginning of that call?

<a href="/images/posts/2016/03/Seeding-2.jpg" target="_blank" rel="attachment noopener wp-att-51"><img class="aligncenter wp-image-51 size-full" src="/images/posts/2016/03/Seeding-2.jpg" alt="Seeding 2"   /></a>With the date + level number, the** _random values will be locked before making the level_** so the &#8220;randomized&#8221; values that are used, are actually calculated by the seed you entered.

As a rough example, if a _seed is set,_ no matter how many times you ask the computer to give a number between 1 and 10, **it will always give the same number**. However, if with the same seed another operation asks for a number between 5 and 10, that value will be different than the one from 1 to 10, **but will never change either**. In essence a seed allows any computer to give the same answer to different questions as the rest. It is important to note however that a random number from 1 to 10, and from 5 to 10,  _**ARE**_ different questions. While asking for a number from 1 to 10 at different moments **IS ALSO** asking a different question. But do know that all computers will give you those answers in the same order.

<a href="/images/posts/2016/03/Computers.jpg" target="_blank" rel="attachment noopener wp-att-54"><img class="aligncenter wp-image-54 size-large" src="/images/posts/2016/03/Computers.jpg" alt="Computers"   /></a>

&nbsp;

This is why you need to change the seed (to a known value) everytime you make a new level, to avoid getting the exact same result everytime. Or change it at the basis that best suits your project.

KNIGHTS makes 75 levels a day, and since the date is never the same 24 hours later, using a level ID + the date, makes the trick for this project.

&nbsp;

And again, thank you for reading my blog~

<!-- AddThis Advanced Settings generic via filter on the_content -->

<!-- AddThis Share Buttons generic via filter on the_content -->
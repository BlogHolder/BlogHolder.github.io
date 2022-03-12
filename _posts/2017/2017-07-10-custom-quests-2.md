---
id: 565
title: 'What I’ve Been Working On: Quest System Pt. 2'
date: 2017-07-10T00:49:50+00:00
author: Arzola
layout: post
permalink: /custom-quests-2/
image: /wp-content/uploads/2017/07/Sakura-Quests-Pt2.png
categories:
  - "Arzola's Games"
  - Sakura Framework
tags:
  - "Arzola's"
  - Development Progress
  - Image
  - Sakura Framework
  - Screenshot
  - Unity3D
---
&nbsp;

<a href="/custom-quests/" target="_blank" rel="noopener">Last time I showed this little quest system</a> it was but a bare skeleton without functionality (other than redrawing itself as needed) and now it is finally functional.

Added some more visual aids for easy readability including a **human readable display of the conditions**, **warnings and error boxes for invalid fields** and content and the **events** that will make it all happen once it is up and running with other systems.

&nbsp;

<a href="/images/posts/2017/07/Sakura-Quests-Pt2.png" target="_blank" rel="noopener"><img class="aligncenter wp-image-566" src="/images/posts/2017/07/Sakura-Quests-Pt2.png" alt=""   /></a>

<img class="irc_mi alignright" src="https://i2.wp.com/s-media-cache-ak0.pinimg.com/originals/ea/e1/38/eae138149512928403ca1af25b33bdbd.png" alt="#Proud"   data-recalc-dims="1" />

And to be honest, there is no other purpose to this post other than bragging a little. Sure, this is far from the best looking custom inspector or the most effective at is intended job, but I can proudly say I made it myself.

&nbsp;

I&#8217;m sure taking my sweet time with these systems but that is because:

&nbsp;

<li style="list-style-type: none;">
  <ol>
    <li>
      Like I said previously, this is intended so it is never needed for me to <em><strong>never make a similar system again</strong></em>.
    </li>
    <li>
      Make it <strong>loosely coupled</strong> so it can interact as needed with any future system I make effortlessly. (Not to mention it might be a little more efficient to call an event than hard-coding the conditions on a <a href="https://en.wikipedia.org/wiki/Big_ball_of_mud" target="_blank" rel="noopener">big ball of mud</a> of code).
    </li>
  </ol>
</li>

<a href="/images/posts/2017/07/Sakura-Quests-TDD.png" target="_blank" rel="noopener"><img class="wp-image-568 alignleft" src="/images/posts/2017/07/Sakura-Quests-TDD.png" alt=""   /></a>

  1. I want this to be **as bug free as possible** to avoid future headaches (TDD anyone? Side note: I still suck at it.)
  2. And most importantly, so time later on can be spent on **designing quests (unlockables) rather than implementing them.**

&nbsp;

&nbsp;

Again, just a little &#8220;Hey this is what I&#8217;ve been doing&#8221; kind of post to indicate I&#8217;m still alive.

&nbsp;

And as always, to anyone that read it this far, thank you for reading my blog :3

<!-- AddThis Advanced Settings generic via filter on the_content -->

<!-- AddThis Share Buttons generic via filter on the_content -->
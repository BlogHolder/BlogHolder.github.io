---
layout: post
comments: true
id: 1223
date: 2018-02-07
modified: 2018-02-07
title: Programmer Tip - Optional Parameters
description: "Let your code remember what it does for you."
permalink: /programmer-tip-5/
image:
  header: headers/programmer-tips.jpg
  background: backgrounds/programmer-tips.jpg
tags:
  - Game Development Tutorials Tips And Tricks
  - Programmer Tips  
---
<center>
<h1>Saving Re-Writing Code Since C# 4</h1>

<p>When building your own systems, you might sometimes require a method you just made to slightly change its functionality in some cases.
<br><br>It might be that you wish you could provide an extra boolean or number to that method, without breaking all you have already done.
<br><br>In these cases, what you are looking for are optional parameters, something already built-in in C#:</p>
</center>

<h2> <a href="https://github.com/heisarzola/Programmer-Tips/wiki/Optional-Parameters" target="_blank">Simple, Yet Powerful</a></h2>

<!--LEFT-->
<div class="row">
    <div class="column2">
        <a href="https://github.com/heisarzola/Programmer-Tips/wiki/Optional-Parameters" data-elementor-open-lightbox="default" target="_blank"><br />
        <img src="/images/posts/2018/02/Optional-Parameters-Text.gif" alt="" data-recalc-dims="1" /> </a>
    </div>
  
<!--RIGHT-->

<div class="column2">
  <ol>
    <li>Write down your method.</li>
    <li>When declaring the parameters it should receive, make sure the parameters you want to make optional are ALL located at the end of the list.</li>
    <li>Assign a value to each of those parameters you want to make optional. (That value will be the &#8220;default&#8221;.)</li>
    <li>When calling the method, cover all non-optional parameters, and use as many optional parameters as you want.</li>
</ol>
<center><a href="https://github.com/heisarzola/Programmer-Tips/wiki/Optional-Parameters" class="btn btn-info" target="_blank">Read The Full Tip HERE</a></center>
</div>
<!--END OF COLUMNS-->
</div>

<!------------------------------------------------------------------------------->
<!--------------------GET MORE USEFUL TIPS ON THE GITHUB WIKI-------------------->
<!------------------------------------------------------------------------------->

<center>

<hr style="border-top: dotted 3px;" />

<h2><a href="https://github.com/heisarzola/Programmer-Tips/wiki" target="_blank">Get More Useful Tips On The GitHub Wiki</a></h2>

<p style="text-align: center;">
  What you just read about was ONE of several programmer tips that are available on the <a href="https://github.com/heisarzola/Programmer-Tips/wiki" target="_blank" rel="noopener">Programmer Tips Wiki</a>.
</p>

<p style="text-align: center;">
  So if you liked the one you just read, be sure to check it out (or star it) as it gets updated often! 😮
</p>

<a href="https://github.com/heisarzola/Programmer-Tips/wiki" class="btn btn-sucess" target="_blank">Read More Programmer Tips!</a>


<!------------------------------------------------------------------------------->
<!----------------------------------FINAL WORDS---------------------------------->
<!------------------------------------------------------------------------------->

<hr>

<p>I love optional parameters, especially in game development. For example, I can create an instance of an object in a scene, and via optional parameters set the default position and rotation to 0, but leaving the option to specify them. It&#8217;s magic.<br><br>So I hope knowing this becomes useful to someone else.</p>

<h3>That Is All For Today, But Like Always…</h3>

<h4>Thank you very much for reading my blog :3</h4>

<!------------------------------------------------------------------------------->
<!--GAME_DEV-->
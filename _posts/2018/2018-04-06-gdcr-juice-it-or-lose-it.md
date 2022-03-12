---
comments: true
layout: post
id: 180406
date: 2018-04-06
modified: 2018-04-06
title: GDCR - Juice It Or Lose It
description: "While working in a game, ever felt like your progress is kinda bland? That it is missing something. That something might be juice, so keep an eye on this talk."
permalink: /gdcr-juice-it-or-lose-it/
guid: http://heisarzola.com/devblog/?p=180406
image:
  header: headers/gdcr.jpg
  background: backgrounds/gdcr.jpg
tags:  
  - Game Development Tutorials Tips And Tricks
  - Game Development Conferences Redux
---
<p>
  Welcome to <strong>Game Development Conferences Redux</strong>, a place where it is attempted to <em>condense the contents of hour-long game development videos, in compact, written format for those with less time</em>.
</p>

<p>
  For this issue we are covering the contents of the <u><a href="https://www.youtube.com/watch?v=Fy0aCDmgnxg" target="_blank" rel="noopener">Juice It Or Lose It</a></u>. Where in a nutshell, we will be talking about the <b><i>many super easy ways</i></b> in which one can enhance a game experience, making it "feel" more fun.
</p>

<hr style="border-top: dotted 3px;" />

<p>
    However if after reading a little about the talk, you are still interested, you might just want to straight up watch it. (That, or if you have the suspicion I might've missed important parts of the talk.)
    <br><br><center>So, here you go just in case:</center>
</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Fy0aCDmgnxg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<hr style="border-top: dashed 2px;" />
<!------------------------------------------------------------------------------->
<!-----------------------VIDEO/IMAGE-TITLE-DESCRIPTION--------------------------->
<!------------------------------------------------------------------------------->

<h2>Sooo, what is "Juice"?</h2>

<p>
  As the heart of the talk, we will be talking about the concept of <b>"juicing"</b>. By that we mean a little animation, noise, visual feedback, or any other type of <u><i>reaction</i></u> that amplifies an action, specific input or sequence of events.
    <br><br><center>It might be easier if you see <u><b>No Juice vs. Juice</b></u> in action:</center>
</p>

<center><a href="/images/posts/2018/04/overall-juice.gif" data-elementor-open-lightbox="default">
    <img src="/images/posts/2018/04/overall-juice.gif" alt="" />
    </a></center>

<p>
  Yea, just a <i>little</i> over the top, but you get the idea. <b>Juicing</b> refers to this contrast between <i>bland</i> and <i>fun (or at least, interesting)</i>.
    <br><br>Even if you don't actually physically experience it, things like camera shake can add a lot of impact and make you somehow <i>feel</i> part of the action.
    <br><br>It is all about <i><u><b>showing a maximum output for each minimal input</b></u></i>.
</p>

<hr>

<h2>Okay, Here Is The Meat Of The Talk</h2>

<p>
  Just so you know, the talk itself focuses on the example blockout clone you just saw. While doing emphasis over the little things that added <b><i>juice</i></b> to the bland, base game.
    <br><br>So, if anything, you might say what the two folks talked about, was but an example list of things one can improve their games at:
</p>

<div class="row">
   <div class="column2">
      <center><h2>Movement And Impact</h2></center>
       A little wobble, some shaking, almost any minimal movement as a reaction to something else, adds a lot more than you imagine.
       <br><br> To the right you see a combination of all the following:
   </div>
   <div class="column2">
      <center><a href="/images/posts/2018/04/bouncy-juice.gif" data-elementor-open-lightbox="default">
    <img src="/images/posts/2018/04/bouncy-juice.gif" alt="" />
    </a></center>
   </div>
</div>

<p>
<ul>
    <li>The paddle, stretches and squashes depending on how fasy you move the mouse.</li>
    <li>The ball is resized and made a little bigger, every time it hits ANYTHING.</li>
    <li>After hitting something, the ball, rotates to denote the new directory it will be taking.</li>
    <li>After hitting something, the ball wobbles for a bit.</li>
    <li>After hitting something, the ball becomes white.</li>
    <li>The ball stretches based on its current velocity.</li>
    <li>When a block is destroyed it falls off.</li>
    <li>While being destroyed, a block becomes smaller.</li>
    <li>While being destroyed and becoming smaller, it should spin.</li>
    <li>And finally, to avoid blending with the rest, the destroyed block should become darker.</li>
    <li>All of the blocks move a little whenever the ball hits anything.</li>
    <li>The walls bounce as gum whenever the ball hits them.</li>
</ul>       
</p>

<div class="row">
   <div class="column2">
      <center><a href="/images/posts/2018/04/particles-juice.gif" data-elementor-open-lightbox="default">
    <img src="/images/posts/2018/04/particles-juice.gif" alt="" />
    </a></center>
   </div>
   <div class="column2">
      <center><h2>Particle Effects</h2></center>
       One of the easiest ways to amplify something without actually moving it, is via a particle that denotes something about it. (Direction, impact, movement, etc.)
       <br><br> On the left, you can see all of the following working together:
   </div>
</div>


<p>
<ul>
    <li>Little smoke puffs whenever the ball hits something.</li>
    <li>Following the above example, anytime it hits anything, it is complemented with unique particles as well.</li>
    <li>There is now a trail that follows the old trajectory of a ball.</li>
    <li>Every block you break, gets broken into darker sub-blocks as particles that fall off the screen.</li>
</ul>       
</p>

<div class="row">
   <div class="column2">
      <center><h2>Sound</h2></center>
       This is a <b><i>MUST</i></b> when it comes to areas that many games should focus effort when polishing.
       <br><br>Sound effects alone can sell the idea of physicality of almost anything, so you shouldn't let them slide.
    <br><br>(Also, given how it is impossible to add sound to a GIF, it is a good chance to share with you the link where you can actually play this little breakout clone.)
   </div>
   <div class="column2">
       <u><a href="http://grapefrukt.com/f/games/juicy-breakout/" data-elementor-open-lightbox="default" target="_blank"><center><h2>Play The Juiced Breakout Clone Here</h2></center></a></u>
   </div>
</div>

<p>
    Just notice how:
<ul>
    <li>Whenever the ball hits a wall, it makes a sound.</li>
    <li>Whenever the ball hits a block, it makes a DIFFERENT sound.</li>
    <li>When blocks are hit in succession, the pitch changes, making them sound "harmonized".</li>
    <li>If the ball hits a paddle, it makes yet another sound effect.</li>
    <li>And of course, the game also has BGM.</li>
</ul>       
</p>

<center><h2>And As The Final Cherry...</h2></center>

<p>
Just remember that you can juice <b>ANY</b> area or <i>moment</i> of your game. An intro for example:
</p>

<center><a href="/images/posts/2018/04/intro-juice.gif" data-elementor-open-lightbox="default">
    <img src="/images/posts/2018/04/intro-juice.gif" alt="" />
    </a></center>

<p>Screen shake with Perlin noise, transitions, alpha cuts, there are many ways that weren't spoken of during the talk really, but that is the point.
<br><br><b><i><u><center>You need to find what best suits your own game and use it.</center></u></i></b></p>

<!------------------------------------------------------------------------------->
<!----------------------------------FINAL WORDS---------------------------------->
<!------------------------------------------------------------------------------->

<hr>

<p>
    Esentially, this little talk gives an important message I think everyone should take home: <b><i><u>"You can polish EVERYTHING to an Nth deegree, you just need to look."</u></i></b>
    <br><br>But also keep in mind something equally important: <b><i><u>Don't start polishing until it is final.</u></i></b>
    <br><br>The folkds that gave the talk had a finished breakout clone by the time they started adding all the juice. They didn't add it while developing, wait until it is the right moment.
    <br><br>Regardless, hope you enjoyed the little breakdown of the talk (and/or the talk itself if you decided to watch it).
</p>

<center><h3>And Like Always...</h3></center>

<center><h4>Thank you very much for reading my blog :3</h4></center>

<!------------------------------------------------------------------------------->
<!--GAME_DEV-->
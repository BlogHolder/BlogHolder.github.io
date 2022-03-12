---
id: 942
title: GDCR – Solving The Time Travel Paradox
date: 2017-12-29T23:00:56+00:00
author: Arzola
layout: post
comments: true
permalink: /gdcr-solving-the-time-travel-paradox/
image: /wp-content/uploads/2017/12/6.gif
image:
  header: headers/gdcr.jpg
  background: backgrounds/gdcr.png
tags:  
  - Game Development Tutorials Tips And Tricks
  - Game Development Conferences Redux
---
<p style="text-align: center;">
  Welcome to <strong>Game Development Conferences Redux</strong>, a place where it is attempted to <em>condense the contents of hour-long game development videos, in compact, written format <strong>for those with less time</strong></em>.
</p>

<p style="text-align: center;">
  For this issue we are covering the contents of <a href="https://www.youtube.com/watch?v=IJCMdfpr3MQ" target="_blank" rel="noopener"><em><strong>GDC&#8217;s 2014 Solving The Time Travel Paradox Conference</strong></em></a>.
</p>

<p style="text-align: center;">
  In a nutshell, it is a conference about the<em> common issues one comes across when making a game that focuses on time manipulation</em>. But namely, how to make something as simple as a rewind or time bending mechanic something easy to understand and fun to play with.
</p>

<p style="text-align: center;">
  However do notice that this talk is mainly focused for games that mainly revolve around the action genre. But these observations might be applicable to any genre with some thought put into it.
</p>

<p style="text-align: center;">
  Without further ado, these are the main takeaways from the conference:
</p>

## &#8220;Out Of The Gate&#8221; Issues

		<img   src="/images/posts/2017/12/6.gif" alt="" data-recalc-dims="1" />

<p style="text-align: center;">
  When thinking time rewind, there are two issues one must <strong><em>IMMEDIATELY</em></strong> attempt to address in regard of game design:
</p>

<li style="text-align: left;">
  Altering the past, might prevent from vital events from happening. Which in the &#8220;second go&#8221; might break things.
</li>
<li style="text-align: left;">
  &#8220;Knowing the future&#8221; might cause any challenge to disappear.
</li>

<p style="text-align: center;">
  A go-to solution for these wasn&#8217;t provided in the talk. Instead they are named for reflection.
</p>

<p style="text-align: center;">
  But in words of the conferencist:<br /><em>&#8220;The time manipulation engine is the &#8216;easy part&#8217;, making your systems capable or handling time paradoxes is the &#8216;fun&#8217; part.&#8221;</em>
</p>

<p style="text-align: center;">
  These are the three main &#8220;fun&#8221; parts he was able to find while making <a href="http://store.steampowered.com/app/250700/Super_Time_Force_Ultra/">Super Time Force</a>:
</p>

<a href="https://www.youtube.com/watch?v=IJCMdfpr3MQ&feature=youtu.be&t=8m21s" data-elementor-open-lightbox="default" target="_blank"><br /> <img   src="/images/posts/2017/12/TIme-Travel-Paradox-1.gif" alt="" data-recalc-dims="1" /> </a>

## Casuality Violation

<p style="text-align: center;">
  Casuality is &#8220;the fundamental one-way relationship between cause and effect.&#8221;
</p>

<p style="text-align: center;">
  What if we didn&#8217;t worry of that? What if an effect takes place without a cause?
</p>

<p style="text-align: center;">
  In essence, this implies that when rewind and unwind are enabled in a game, one must reflect on  what is NEEDED to preserve past events and have them still happen.
</p>

<p style="text-align: center;">
  <em><strong><a href="https://youtu.be/IJCMdfpr3MQ?t=8m21s" target="_blank" rel="noopener">See the clip of this principle in action.</a></strong></em>
</p>

<p style="text-align: center;">
  <em>&#8220;Things don&#8217;t make temporal sense anymore, but the game will &#8216;FEEL&#8217; more correct.&#8221;</em>
</p>

## <a href="https://youtu.be/IJCMdfpr3MQ?t=13m30s" target="_blank">Butterfly Effect Management</a>

<p style="text-align: center;">
  The Butterfly effect is &#8220;when a small change in the initial state of a system can result in a large change in the final state of that system.&#8221;
</p>

<p style="text-align: center;">
  In a game, this usually comes in the shape that given how you can change the past, things will inevitably change in the &#8220;present&#8221; for better or for worse.
</p>

<p style="text-align: center;">
  The key is that 99% of the time it is for worse, which might make time traveling not worth it as a mechanic.
</p>

<p style="text-align: center;">
   To prevent this, you can attempt to establish a level entropy, a state of constant equilibrium. In video games however, equilibrium would be no progress has been made, so it should be redifined to: &#8220;modifying a timeline must always result in a &#8216;past state&#8217; where progress has been made&#8221;. Naturally, &#8220;progress&#8221; will be defined on a game to game basis based on its core objectives. 
</p>

<p style="text-align: center;">
  <em><strong><a href="https://youtu.be/IJCMdfpr3MQ?t=13m30s" target="_blank" rel="noopener">Example clip of this principle in action.</a></strong></em>
</p>

<p style="text-align: center;">
  Again, things don&#8217;t make temporal sense anymore, but the game will &#8220;FEEL&#8221; more correct.
</p>

<a href="https://youtu.be/IJCMdfpr3MQ?t=13m30s" data-elementor-open-lightbox="default" target="_blank"><br /> <img   src="/images/posts/2017/12/TIme-Travel-Paradox-2.gif" alt="" data-recalc-dims="1" /> </a>
						  
<a href="https://youtu.be/IJCMdfpr3MQ?t=19m13s" data-elementor-open-lightbox="default" target="_blank"><br /> <img   src="/images/posts/2017/12/TIme-Travel-Paradox-3.gif" alt="" data-recalc-dims="1" /> </a>

## <a href="https://youtu.be/IJCMdfpr3MQ?t=19m13s" target="_blank">The Quantum Measurement Problem</a>

<p style="text-align: center;">
  Hard to explain, but easily understandable under the premise: &#8220;If a tree falls in a forest and no one is around to hear it, does it still make a sound?&#8221;.
</p>

<p style="text-align: center;">
  While most people would say &#8220;Yes&#8221;, quantum mechanics say &#8220;Nope!&#8221;. Essentially speaking, quantum measurement means: &#8220;Something does not happen until they are actually measured by an observer&#8221;.
</p>

<p style="text-align: center;">
  The problem that comes with ignoring this is that there are sometimes things that happen offscreen that will lead to confusion when encountered.
</p>

<p style="text-align: center;">
  For example in a run and gun game, you have to decide if bullets should continue off camera, or after reaching a camera offset they should be destroyed. Why? Because things such as climbable destructible items might already be destroyed when you reach them. Naturally, the problem becomes more complex when time traveling is added to the equation.
</p>

<p style="text-align: center;">
  <a href="https://youtu.be/IJCMdfpr3MQ?t=19m13s" target="_blank" rel="noopener"><em><strong>Example clip of this principle.</strong></em></a>
</p>

## Q & A

<p style="text-align: center;">
  <em>It is important to note the questions and answers given revolve around the gameplay mechanics of the game <a href="http://store.steampowered.com/app/250700/Super_Time_Force_Ultra/">Super Time Force</a>, so might not apply to all scenarios.</em>
</p>

<p style="text-align: center;">
  <strong>Q: To prevent exploitation of power ups, and the likes by a player, what do you do?</strong><br />A: What we did was put a cap on the amount of times and total time you could rewind. For power ups, the easiest was to make them a one time use thing, across all timelines.
</p>

<p style="text-align: center;">
  <strong>Q: In the scenario a player dies, and a rewind allows you to save that past self, what do you do with that &#8220;zombie&#8221; instance? What will it do after you save it?</strong><br />A: We didn&#8217;t do anything crazy like A.I., but instead made them powerups to esentially have the manpower of 2 in 1.
</p>

## This Concludes Another Issue of GDCR

<p style="text-align: center;">
  There you have it, some interesting things to consider when making a game with rewind or time travel mechanics.
</p>

<p style="text-align: center;">
  Are you implementing something similar? Something you think that should be added?
</p>

<p style="text-align: center;">
  Leave your answers on the comment section below 😮
</p>

<p style="text-align: center;">
  I like doing these tl;drs of hour long conferences, it gives me both an excuse to watch it, and document it so I can revisit it faster later. So I hope you liked it as well, as this concludes today&#8217;s post.
</p>

## But Like Always&#8230;

# Thank you very much for reading my blog 🙂

<!--GAME_DEV-->

<!-- AddThis Advanced Settings generic via filter on the_content -->

<!-- AddThis Share Buttons generic via filter on the_content -->
---
layout: page
comments: false
id: 1802104
date: 2018-02-10
title: Unity Tips
description: "Do you frequently use Unity?. Well, here you can find not-so-known shortcuts and features to improve your experience."
permalink: /for-game-devs-and-programmers/unity-tips/
guid: http://heisarzola.com/devblog/?p=1802104
image:
  header: headers/unity.jpg
  background: backgrounds/dev.jpg
---
# Mastering A Tool Gets Easier When You Know The Tricks

<p>What you are about to read is a collection of shortcuts, keyboard commands, obscure features, and other included hidden goodies that will improve your experience developing with the <a href="https://unity3d.com/" target="_blank">Unity game engine</a>.
<br><br>Also, please do note that all of the following tips have been neatly packed <a href="https://github.com/heisarzola/Unity-Tips/wiki" target="_blank">on their own wiki</a> for your reading comfort.</p>

<br>
<hr style="border-top: dotted 3px;" />

<h2>Table Of Contents</h2>

* <a href="#short">Shortcuts</a>
    * <a href="#shortmouse">Mouse Shortcuts</a>
        * <a href="#shortmouse1">Move Components Between GameObjects</a>
* <a href="#opt">Optimization</a>
    * <a href="#optgc">Garbage Collection</a>
        * <a href="#optgc1">Use StringBuilder Instead of "String" += "OtherString"</a>
    * <a href="#optcalc">Optimize Calculations</a>
        * <a href="#optcalc1">Edit Collision Matrix</a>
    * <a href="#optdevt">Development Time Optimization</a>
        * <a href="#optdevt1">Built-In Primitive Sprites</a>
* <a href="#org">Organization</a>
    * <a href="#orgdoc">Documentation</a>
        * <a href="#orgdoc1">HelpURL</a>
        * <a href="#orgdoc2">DocumentationURL</a>

<!---------------------------------------------------------------------------->
<!----------------------------------SHORCUTS---------------------------------->
<!---------------------------------------------------------------------------->

<br><br>

<hr>
<h2 id="short">Shortcuts</h2>
<hr style="border-top: dotted 3px;" />

<h2 id="shortmouse">Mouse Shortcuts</h2>
<hr style="border-top: dashed 2px;" />

<div class="row">
   <div class="column2">
      <a href="/images/posts/2017/12/Pass-Components-Between-GO-Text.gif" data-elementor-open-lightbox="default"><br />
          <img src="/images/posts/2017/12/Pass-Components-Between-GO-Text.gif" alt="" data-recalc-dims="1" target="_blank">
       </a>
   </div>
   <div class="column2">
       <h2 id ="shortmouse1"><a href="/unity-tip-2/" target="_blank">Move Components Between GameObjects</a></h2>
       <p>Avoid going through the process of creating a new component on the target GameObject, copy-pasting the settings from the original one, and deleting said component from the original to "pass it". <u><a href="/unity-tip-2/" target="_blank">Just do it directly</a></u> :o</p>
   </div>
</div>

<!---------------------------------------------------------------------------->
<!--------------------------------OPTIMIZATION-------------------------------->
<!---------------------------------------------------------------------------->

<br><br>

<hr>
<h2 id="opt">Optimization</h2>
<hr style="border-top: dotted 3px;" />

<h2 id="optgc">Garbage Collection</h2>
<hr style="border-top: dashed 2px;" />

<div class="row">
   <div class="column2">
       <h2 id ="optgc1"><a href="/unity-tip-3/" target="_blank">Use StringBuilder Instead of "String" += "OtherString"</a></h2>
       <p>Did you know that when you use "string" += "otherString" you are generating garbage that needs to be picked up? But did you also know that <u><a href="/unity-tip-3/" target="_blank">using the StringBuilder class</a></u> takes care of that overhead?</p>
   </div>
   <div class="column2">
      <a href="/images/posts/2018/01/Use-StringBuilder-Instead-of-Text.gif" data-elementor-open-lightbox="default"><br />
          <img src="/images/posts/2018/01/Use-StringBuilder-Instead-of-Text.gif" alt="" data-recalc-dims="1" target="_blank">
       </a>
   </div>
</div>

<hr>
<h2 id="optcalc">Optimize Calculations</h2>
<hr style="border-top: dashed 2px;" />

<div class="row">
   <div class="column2">
       <h2 id ="optgc1"><a href="/unity-tip-6/" target="_blank">Edit Collision Matrix</a></h2>
       <p>If your game involves stuff colliding with one another, you might want to limit which things can collide with which via the <u><a href="/unity-tip-6/" target="_blank">collision matrix</a></u>.
       <br><br>With some good planning, you might even avoid having to make tag comparisons, and other troublesome tasks.</p>
   </div>
   <div class="column2">
      <a href="/images/posts/2018/02/Collision-Matrix-Text.gif" data-elementor-open-lightbox="default"><br />
          <img src="/images/posts/2018/02/Collision-Matrix-Text.gif" alt="" data-recalc-dims="1" target="_blank">
       </a>
   </div>
</div>

<hr>
<h2 id="optdevt">Development Time Optimization</h2>
<hr style="border-top: dashed 2px;" />

<div class="row">
   <div class="column2">
      <a href="/images/posts/2018/04/primitive-sprites.gif" data-elementor-open-lightbox="default"><br />
          <img src="/images/posts/2018/04/primitive-sprites.gif" alt="" data-recalc-dims="1" target="_blank">
       </a>
   </div>
   <div class="column2">
       <h2 id ="optdevt1"><a href="/unity-tip-7/" target="_blank">Built-In Primitive Sprites</a></h2>
       <p>Don't go out of your way making sprites like squares, triangles or circles, use those <u><a href="/unity-tip-7/" target="_blank">already built in Unity</a></u>.
       <br><br>Save your time, and even memory, with this small, efficient simple sprites.</p>
   </div>
</div>

<!---------------------------------------------------------------------------->
<!--------------------------------ORGANIZATION-------------------------------->
<!---------------------------------------------------------------------------->

<br><br>

<hr>
<h2 id="org">Organization</h2>
<hr style="border-top: dotted 3px;" />

<h2 id="orgdoc">Documentation</h2>
<hr style="border-top: dashed 2px;" />

<div class="row">
   <div class="column2">
      <a href="/images/posts/2018/01/HelpURL-Text.gif" data-elementor-open-lightbox="default"><br />
          <img src="/images/posts/2018/01/HelpURL-Text.gif" alt="" data-recalc-dims="1" target="_blank">
       </a>
   </div>
   <div class="column2">
       <h2 id ="orgdoc1"><a href="/unity-tip-4/" target="_blank">Help URL</a></h2>
       <p>Do you have your own documentation site for your things? Or have you ever wished you could keep a script reference next to you? Because, the <u><a href="/unity-tip-4/" target="_blank">HelpURL attribute</a></u> allows just that.</p>
   </div>
</div>

<hr>

<div class="row">
   <div class="column2">
       <h2 id ="orgdoc2"><a href="/unity-tip-5/" target="_blank">Documentation URL</a></h2>
       <p>If you ever forget what does a built-in Unity component does, you should keep in mind there is <u><a href="/unity-tip-5/" target="_blank">a blue help icon</a></u> on the corner of each component.</p>
   </div>
   <div class="column2">
      <a href="/images/posts/2018/01/Documentation-URL-Text.gif" data-elementor-open-lightbox="default"><br />
          <img src="/images/posts/2018/01/Documentation-URL-Text.gif" alt="" data-recalc-dims="1" target="_blank">
       </a>
   </div>
</div>

<!--GAME_DEV-->
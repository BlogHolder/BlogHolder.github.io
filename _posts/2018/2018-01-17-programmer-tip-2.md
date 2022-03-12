---
layout: post
comments: true
id: 1128
date: 2018-01-17
modified: 2018-01-17
title: Programmer Tip - Params Keyword
description: "Did you know that C# allows you to create methods that receive an infinite amount of parameters of the same type? Now you do."
permalink: /programmer-tip-2/
image:
  header: headers/programmer-tips.jpg
  background: backgrounds/programmer-tips.jpg
tags:
  - Game Development Tutorials Tips And Tricks
  - Programmer Tips  
---
<h1>Avoid Making Multiple Methods</h1>

<p>Sometimes you require to pass a LOT information to a method of a given type, and you might&#8217;ve worked around it doing something like:
    
<pre>
public MyMethodThatNeedsManyStrings(List&lt;string&gt; myStringList)
</pre>

Which in practice might seem like the way to go, but on the long run it will involve you needing to create and populate a list before passing it to this method. Where another case might be that you NEED something like the following:

<pre>
public SomeMethod(string firstString)
public SomeMethod(string firstString, string secondString)
public SomeMethod(string firstString, string secondString, string thirdString)
</pre>

If you keep doing the parameter overflow like this, you can see how quickly it can become messy and hard to manage if you need to do this for, let&#8217;s say, 50 string parameters.
<br><br>The premise might sound a little too specific, but it actually happens. It usually will involve you having different amounts of data to work with that you want to somehow connect in a central method:

<pre>
public static class Printer
{
	public static void Print(params string[] thingsToPrint)
	{
		foreach (string s in thingsToPrint)
		{
			// By the way, DON'T concatenate strings like this in Unity* (see below)
			Debug.Print("Printing: "" + s + "".");
		}
	}
</pre>

* (This generates unnecessary garbage, <a href="unity-tip-3/" target="_blank" rel="noopener">see this</a>)


<!--LEFT-->
<div class="row">
    <div class="column2">
        <a href="https://github.com/heisarzola/Programmer-Tips/wiki/Params" data-elementor-open-lightbox="default" target="_blank"><br />
                <img src="/images/posts/2018/01/Params-Text.gif" alt="" data-recalc-dims="1" /> </a>
    </div>
  
<!--RIGHT-->

<div class="column2">
<h2> <a href="https://github.com/heisarzola/Programmer-Tips/wiki/Params" target="_blank">Try It Yourself Today!</a></h2>
  <p>As you can see, now this little Printer is capable of printing any number of lines according to the amount of string parameters given.</p>
  <center><a href="https://github.com/heisarzola/Programmer-Tips/wiki/Params" class="btn btn-info" target="_blank">Read The Full Tip HERE</a></center>
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

<p>I used the little <code>params</code> keyword to make my <a href="https://github.com/heisarzola/Unity-Development-Tools/blob/master/Extensions/StringBuilderExtension.cs" target="_blank" rel="noopener">StringBuilderExtension</a>, and been using it whenever I need to since, so I hope this tip comes useful for you as well.
<br><br>This concludes today&#8217;s post, hope I was helpful today~</p>

<h3>But Like Always…</h3>

<h4>Thank you very much for reading my blog :3</h4>

<!------------------------------------------------------------------------------->
<!--GAME_DEV-->
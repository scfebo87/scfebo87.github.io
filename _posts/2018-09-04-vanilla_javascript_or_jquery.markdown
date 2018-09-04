---
layout: post
title:      "Vanilla Javascript or JQuery?"
date:       2018-09-04 06:37:06 +0000
permalink:  vanilla_javascript_or_jquery
---


Learning Javascript was fun, but it wasn't till Jquery that I really started to enjoy using Javascript. In most things in life, if I can find a shortcut that works as well or better than a long way of doing something, I am all over that. This is probably cause I'm lazy, but I love to find faster ways to accomplish something. JQuery feels almost like a cheat code in a video-game and it honestly brings joy to my heart to use. That being said, there are certain times that I perfer to use pure Javascript because I'm able to understand my code better. Here are a few examples of when pure Javascript makes more sense to me:

**Finding Elements:**

JQuery: $('.my #awesome selector');   
Vanilla: document.querySelectorAll('.my #awesome selector');

In this scenerio, JQuery is obviously less to type, but however my brain works, I perfer to type out document.querySelector as it reminds me at quick glance of the code that I am seraching for a particular element. Yes, the JQuery might be neater, but I will take understanding over being neat any day. 

**Get Attribute**

JQuery: $(el).attr('tabindex');
Vanilla: el.getAttribute('tabindex');

Again, being able to see "getAttribute" is nice cause it allows me to register what my code is trying to do. Plus, in this scenario, it's not a whole lot neater. 

**Set HTML**

JQuery: $(el).html(string);
Vanilla: el.innerHTML = string;
 
 I will chosse code that involves an equal sign over an alternative almost every time. It might not look better, but seeing/coding an equal sign doesn't allow me to question what's happening. I know some value is changing or being set and my brain is happier. 
 
 These are just a few examples of when I would not choose the JQuery convenience. Though I guess in the world of coding there are some who would never use JQuery, so I guess it's all a matter of preference. Lastly, all of these examples came from the site http://youmightnotneedjquery.com/. 



---
layout: post
title: This Coffeescript
date: '2013-11-26 05:26:02'
excerpt: "I like coffeescript, well sort of, its a bit of a love hate, but this one little trick saved me tons of typing."
---

Today I stumbled upon something that I found while working on a rails project that uses coffeescript. If you have never heard of coffeescript before, [check out coffeescript right now!](http://coffeescript.org/)
Coffeescript is basically a nice DSL on top of regular ol javascript which is just much nicer to write, plus theres some great little helpers in there for some common functions which can be a bit nasty, at least IMHO.

So what the fuss is about today is this, this as in the **this** statement in javascript. You can accomplish the same thing by using **@** in coffeescript.

Here is an example of a [jQuery](http://jquery.com/) this object used normally and then in coffeescript.

Jquery
`$(this)`

Coffeescript  
`$(@)`

This just looks much nicer to me, even though it was like uhh whats that at first, but the code following after made perfect sense in the scope of the action. 

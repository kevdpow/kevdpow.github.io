---
layout: post
title:  "Hi, hello, I'm here!"
date:   2017-07-07 13:16:50 -0400
---


If you've looked at my Flatiron progress lately, you'll see a gap between May 14th and July 6th. Wow! A lot of things happened during this time.

1. I officiated two weddings in tropical locations.
2. I made significant progress on a HUGE work project.
3. I made that quinoa soup again.
4. My parents visited and met my boyfriend for the first time (!!!).
5. I interviewed for but did not get a junior developer position at a Library.

So here I am, back at it. I've picked OO back up, and I really like it actually! I'm trying my hardest not to peek at the solution branches for tips, but sometimes it helps me know if I'm on the right track. 

On the lab I just finished, I was instructed to create a unique array from a list of email addresses that were separated by both commas and spaces. I came up with this long method chain to do it....

`emails.split(/[,\s]/).reject {|e| e.empty?}.flatten.uniq`
	
In order: 
* I split the array by commas and spaces using regex
* I remove any resulting empty array values
* I remove duplicate values

I was feeling all kinds of proud of myself because IT WORKED... until I look at the solution, which uses the `map` method, which seems much less hamfisted than my approach?

These are the moments I think about coding as a *language*. "Buffalo buffalo Buffalo buffalo buffalo buffalo Buffalo buffalo" [is a grammatically correct sentence](https://en.wikipedia.org/wiki/Buffalo_buffalo_Buffalo_buffalo_buffalo_buffalo_Buffalo_buffalo), but it isn't very communicative!

This is my current struggle; how do I write code that makes the most sense and communicates the most efficiently. Passing the `rspec` tests is cool and all but that does not a developer make! 

OK that's all for now. See you in three months (kidding... I hope!!) 

---
layout: post
title: Did You Know? Vectors not guaranteed to be contiguous?
description: First issue of the Did You Know? series
image:
category: [Programming, Did you know?]
tags: [C++, Programming]
---
Welcome to the first post of the "Did you know?" series. My intent is to provide you with interesting tibits and factoids which you may or may not find useful. They'll mostly be focused around C++ programming and Unreal Engine. Some will be my original thoughts, and others will be relaying information I found elsewhere. I hope you enjoy!

Now with the mandatory preamble out of the way lets begin with something small

***
Prior to C++03, the elements of a vector were not in fact guaranteed to be contiguous in memory as part of the standard. Of course, as a game dev, where you using the STL anyway? :)

Sources: 
* [C++ Standard Library Defect Reports and Accepted Issues (Revision R124)](https://open-std.org/JTC1/SC22/WG21/docs/lwg-defects.html#69)
* [Cringe not: Vectors are guaranteed to be contiguous](https://herbsutter.com/2008/04/07/cringe-not-vectors-are-guaranteed-to-be-contiguous/)

> Don't expect these to come out regularly (or at all if we're being honest)
{: .prompt-warning}




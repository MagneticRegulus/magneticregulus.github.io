---
layout: post
title:  "Stitchstock"
date:   2021-01-07
tags: java android mobile university
excerpt: "An Android app for keeping track of your embroidery floss."
project_title: "Stitchstock"
repo_name: MagneticRegulus/ThreadManagementApp
repo_url: https://github.com/MagneticRegulus/ThreadManagementApp
read_more: "Read the detailed project summary"
read_more_name: magneticregulus.com/ThreadManagementApp
read_more_url: https://www.magneticregulus.com/ThreadManagementApp
---

I do a lot of cross-stitching. I'm not particularly artistic; cross-stitching is essentially pixel art with thread. But it's a nice way to relax. There's something about tactile art that really makes it worthwhile.

However, something I never thought I'd have to deal with is the sheer amount of embroidery floss you assemble after only a few projects. Do you know how many shades of green there are??? (Answer: many.)

The embroidery floss company that has the widest distribution in the world is DMC, and they have over 500 different colours in their standard collection. I already have hundreds of colours!

<img style="max-width: 100%; margin-right: auto; margin-left: auto; display: block;" src="{% link assets/floss.jpg %}" />

For a long while, I used an excel spreadsheet to keep track of the colours I already had. However, that's not very efficient or user-friendly. I downloaded a few apps to try to help organise myself, but they either were overly complex ("measure the amount of thread you're using to the millimetre") or had poor UX. Either way, they didn't get me what I needed.

In January, our professors gave us a two and a half day challenge: impress us. So I chose to build an Android app to help me keep track of my growing collection of floss / thread.

The app, Stitchstock, allows users to add DMC colours to their stock, mark a skein as "low stock" (meaning, I think I'm running out of this), or mark a colour as needed regardless of whether they have it. It gives users a little shopping list of colours they need to remember to buy, which is especially important if you're like me and put projects down for...8 months...

![]({% link assets/stitchstock.gif %})

Stitchstock is far from finished. It has a few UX problems, is missing a big feature (grouping colours by project), and really needs to be tested with other potential users. I intend to keep working on it, and maybe, one day, it'll go up on Google Play.

Overall, this is the project I'm most proud of.

**2022 edit:** I would love to go back and finish this, but now with more experience under my belt, I would start over and build this in either
- Flutter for both Android and iOS development,
- a .NET Core Blazor app, or 
- return to my first love, Ruby on Rails and give [Matestack][matestack] a try.

[{{ page.read_more }}]({{ page.read_more_url }})  
[Check out the code]({{ page.repo_url }})

[matestack]: https://docs.matestack.io/about/

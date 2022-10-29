---
layout: post
title:  "The Obligatory Conway's Game of Life Attempt"
date:   2020-11-20
tags: java javafx university
tagline: "Doesn't every university student do one of these?"
excerpt: "A simple version of Conway's Game of life written in Jave using JavaFx."
project_title: "Conway's Game"
repo_name: MagneticRegulus/ConwaysGame
repo_url: https://github.com/MagneticRegulus/ConwaysGame
read_more: "Read my development journal"
read_more_name: magneticregulus.com/ConwaysGame
read_more_url: https://www.magneticregulus.com/ConwaysGame
is_project_page: true
---

So, we had a unit in Uni where we had to build [Conway's Game of Life][conway]. However, our professors gave us this task before we tackled "the Big O" problem. Every group's programs had massive memory problems or tried to fit an "infinite" grid of squares into 2D arrays (in Java).

After the unit on memory handling, I decided to tackle the task on my own. I built my Game of Life using Java with a JavaFX front-end. These were the tools we had to build it in the first place, so I stuck to it.

![]({% link assets/conway-example.gif %})

For the record, I was not aiming for artistic beauty, but rather, something that worked. I journaled my progress on GitHub and go deep in depth on the whats and hows of my program. It's a humble Conway's Game of Life, but I was fairly happy I was able to get there on my own. I hope to come back to it someday soon to finish it.

**2022 edit:** Note the naivety of "Add photo here" messages to myself and the final journal entry stating the project will be "resume[d] at a later date." The joys of student life!

In hindsight, I think the biggest issue with this attempt was the use of JavaFX and not working on a way to host online. I'd love to give this another go using a javascript or typescript frontend and a C# backend.

[{{ page.read_more }}]({{ page.read_more_url }})  
[Check out the code]({{ page.repo_url }})

[conway]: https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

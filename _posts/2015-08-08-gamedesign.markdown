---
layout: post
title:  "Parallels in Site and Game Programming"
date:   2015-08-23 12:22:13
categories: jekyll updated
---

I decided it would be fun over the long weekend to explore some of the resources available through Treehouse. I stumbled across a game programming tutorial and would like to share some of the main takeaways from that experience.

Gaming has been immensely enjoyable for me over the years, but up until recently I could hardly comprehend what might be going on behind the scenes to bring the biggest blockbuster gaming titles to life.

Jumping into my main takeaways, I quickly learned that game programmers are distinct from game designers and game artists. Designers focus on the logical elements for how the game functions. Artists focus on the aesthetics of the game. Programmers focus on the code that allows the game to function.

Most games created today are built in game engines. The most prominent of these are Unity (which uses C#) and Unreal (which uses C++). These are distinct from 3d modelling software. They're where all the elements (functional and artistic) for a particular game intersect. Much like rails, they are built on layers of programming and best practices cultivated after decades of game development. Thus they allow game programmers to not have to start from scratch every time they want to design a new game.

A game mechanic refers to an Atomic Interaction Interaction with the Game World. For instance, in this game it might be the ability of the frog to collect flies. These minute details and how they build to a greater whole is reminiscent of the individual elements and associations that define our sites. 'The frog 'has_many' tadpoles'.

As with the example above, there were numerous parallels between the logic we had used to build site and the logic that Unity uses to build dynamic games.

First lets look at the Unity window -

![Unity]({{ ehawk823.github.io }}/assets/unity_template.png)

For anyone that's used FinalCut or another video editing platform, this might look familiar. But how could we relate this to rails? Working through this tutorial, I began to think of the viewer as a localhost equivalent, where we can demo our changes in real time. The remainder of the windows effectively serve as a sophisticated text editor - displaying our directories and allowing us to interact with assets that make up the game.

While we can do a lot structurally to assemble the physical components with tools built into unity, at a certain point we need to write some code. This comes into play as we begin to outline how the individual element of our game world interact. Unity comes with a built in text editor, specifically for this purpose. We write scripts define everything from how a player moves, to how a player's score is maintained.

Take a look at the script below -

![UnityCode]({{ ehawk823.github.io }}/assets/unity_code.png)

Here we are defining the frog character's movement based on a direct input from the player. Similar to how code allows us to define the logic and relationships or a given site, the code here permits us to 'unify' the game's physical properties (animations, models, etc.) in such a way that they function within the context of the game.

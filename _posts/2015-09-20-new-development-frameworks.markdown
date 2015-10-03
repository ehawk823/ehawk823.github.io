---
layout: post
title:  "New Development Frameworks"
date:   2015-09-20 12:22:13
categories: jekyll updated
---

Last week, we briefly touched on the idea of containers during our lecture on Heroku deployment. At my previous employer, I'd worked with a company in the containerization space, but I hadn't fully grasped what that meant. I decided to tackle this topic in a blog post to hopefully deepen my understanding of this seemingly complex subject..

![Container]({{ ehawk823.github.io }}/assets/container.gif)

Before diving into containerization, it might be helpful to briefly touch on virtualization. Virtualization refers to the act of creating a virtual operating environment within an existing OS. A computer running Windows might for instance host a virtual machine that looks like the Ubuntu Linux OS. In a typical infrastructure architecture (think AWS or VMWare) you might distribute your software and have it run on virtual machines tied to physical servers. These VM's can be very wasteful from a storage and bandwidth standpoint as each VM runs a full copy of the required OS.

![Docker]({{ ehawk823.github.io }}/assets/Docker.png)

And now to introduce containers! Rather than packaging each individual application with it's own OS, containers allow applications to be deployed in a far leaner manner, operating on a shared instance of a given operating system. This results in efficiency improvements, orders of magnitude greater than those attainable through virtual machines.

![Crab]({{ ehawk823.github.io }}/assets/crab.jpg)

Large tech companies and PaaS providers (such as Heroku) have been taking advantage of containers for years, but this tech has only become widely accessible recently with the advent of Docker and other players in the container space. Docker containers wrap a piece of software with everything needed to run it - code, runtime, system tools, system libraries, etc. These containers share a kernel with other containers, rather than carrying their own guest OS as a VM would.

![Turles]({{ ehawk823.github.io }}/assets/turtles.jpg)

As long as a given endpoint is running Docker (which can operate on Linux/Windows as well as almost any infrastructure and in the cloud), developers can avoid challenges associated with conflicting environments or time spent adapting environments to align with the specifications for a particular app. Another benefit of this efficiency is that teams can more easily collaborate on a given app and engineers at different stages in the product lifecycle (e.g. downstream service teams) don't need to worry about environmental issues creating unnecessary complications.

![Whales]({{ ehawk823.github.io }}/assets/docker-whales.jpg)

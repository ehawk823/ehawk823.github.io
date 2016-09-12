---
layout: post
title:  "Developing for Different Mediums"
date:   2015-11-25 12:22:13
categories: jekyll updated
---

For this post, I decided to look at some of the development and design principles that differ depending on platform and context. Specifically, I'll look at development for mobile devices and VR.

Rather than the obvious distinctions of preferred programming languages and development frameworks for each medium, I decided to focus more on the experiential differences between each platform that a developer must be cognizant of when building their app.

First mobile -

As web developers, we can build apps that function on mobile devices, but their responsiveness and functionality will be severely limited compared to a native mobile app. That said, developing web-based apps that function on mobile devices circumvents the frustrations of the app store approval process and arduous task of developing for multiple platforms.

![Mobile]({{ ehawk823.github.io }}/assets/mobile.png)

Whether you decide to develop a native, web or hybrid mobile app, the user considerations are mostly the same. Perhaps most obviously, factoring in the screen proportions is essential. Your user won't be viewing the content on a screen as large as your laptop or desktop, so the UI and navigation should be simplified. Moreover, the user will primarily be interacting with your app using their fingers, so while the screen might be smaller, the buttons and links should be larger and user input minimized. There are also a range of conventions for mobile design to optimize user comfort, such as placing tabs at the bottom of the app (where your thumb can easily reach them). A unique consideration for native apps is that you'll have to decide what other phone features you'll want to integrate into your apps functionality - e.g. location services, camera, etc.

VR -

Admittedly this is a new development paradigm, so design best practices are still coming together. That said a recurring theme in VR development is the emphasis on building apps that avoid the prospect of simulator sickness, which is defined on the Oculus website as "a combination of symptoms clustered around eyestrain, disorientation, and nausea". To combat this issue, developers should build apps that mimic real head movement, minimize latency, avoid sudden speed changes, and keep objects a comfortable distance from the user.

Once simulator sickness has been accounted for we can begin thinking about how more traditional UI's, similar to those built for web and mobile apps, should function in a VR environment. I've included some recommendations from the Oculus website detailing the best practices for these types of interfaces -

![Oculus]({{ ehawk823.github.io }}/assets/Oculus.png)

It's interesting to consider what the major websites of today might look like manifested in a 3D environment. Displaying lots of text in VR is currently difficult due to resolution limitations, although those barriers should be overcome within the next few years. How will the major websites of today, represent their content in a 3D environment. For instance, would a user's Facebook page one-day be replaced by their own fully customizable 3D space or will sites find a way to migrate their functionality to a virtual UI.

![UI]({{ ehawk823.github.io }}/assets/UI.jpg)

Developers have already begun experimenting with both methods and combining elements from each. For example, the team at Sprawly is attempting to build VR's first search engine, integrating a 3D grove and 2D UI elements that respond to your gaze -

[Sprawly](http://www.sprawly.co/)

Augmented reality might be a more attractive alternative for text-heavy sites. In Microsoft's Hololens demos, we see a user interacting with 2D frames that allow a similar UI to those that more traditional apps provide.

![Hololens]({{ ehawk823.github.io }}/assets/Hololens.jpg)

In any case, I'm excited to see how all of the platforms discussed above converge and how the most prominent websites and apps translate their user experience to newer mediums.

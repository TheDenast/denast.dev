---
title: "Elastic 2D Collision Simulation"
date: 2021-05-01
draft: false
description: "A C++ Project aiming to provide simplified elastic collision simulation for 2D environment"
tags: ["C++", "Embedded"]
---
[Video Preview](/media/collisionsim.mp4)

> I've completed this project back in 2021, so the code and the report may no longer be maching my current stadards.

This project explored the simulation of perfectly elastic collisions among various 2D shapes, focusing on aspects like shape movement, data storage, collision detection, and post-collision behavior in a 2D environment. Utilizing C++ and a single-threaded FPGA processor, the simulation achieved efficient performance by manually managing each pixel's display, employing a global timer loop to control movement and detect collisions at 10 frames per second.

I've also written an IEEE paper on the matter (unpublished) that you can download below.

{{< button href="/docs/collision_ieee.pdf" download="/docs/collision_ieee.pdf" target="_blank" >}}
Download IEEE Paper
{{< /button >}}

---

{{< github repo="thedenast/collision_sim" >}}

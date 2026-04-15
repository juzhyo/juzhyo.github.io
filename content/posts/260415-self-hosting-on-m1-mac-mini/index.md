---
title: "Self-hosting on an M1 Mac mini"
description: "Self-hosting on an M1 Mac mini"
date: 2026-04-15
weight: 1
draft: false
slug: "self-hosting-on-an-m1-mac-mini"
tags: ["self-hosting"]
series: ["Self-hosting"]
series_order: 1

cascade:
  showDate: true
  showAuthor: false
  invertPagination: true
---

## Motivation
Bought an M1 Mac mini off Carousell late last year and have only been using it as a desktop since. Felt that it's under-utilized. Perhaps it can replace my current Intel NUC as my home server. Instead of two devices, I can have one which serves as both desktop and server --- much cleaner this way. The M1 Mac mini is more powerful than the NUC6i3SYB with 16GB RAM (maybe I can run a small, local LLM?), more modern CPU, and better build quality. My concern is that macOS would not be the best at running Docker containers. Also, the M1 Mac mini was released 6 years ago. Not sure when software support for it will end.

Always felt that self-hosting, or having a home server, will be rewarding and essential. Not only can I have control over my data and host my own services. I can also run scripts to automate various tasks. 

## Getting started
I already have a home server running with the NUC. Just need to migrate it over to the Mac mini. Was using Ansible to setup the NUC previously with Debian as the OS. Would have to rewrite the playbook for macOS.

{{< gallery >}}
  {{< figure src="img/d8-hybrid.jpg" alt="Gallery image 1" caption="TerraMaster D8 Hybrid DAS" figureClass="grid-w100" >}}
  <!-- {{< figure src="gallery/02.jpg" alt="Gallery image 2" caption="Second caption" figureClass="grid-w33" >}} -->
  <!-- {{< figure src="gallery/03.jpg" alt="Gallery image 3" caption="Third caption" figureClass="grid-w33" >}} -->
{{< /gallery >}}

As for storage, the 

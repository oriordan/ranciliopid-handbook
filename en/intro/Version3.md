---
layout: default
title: Version 3.0.0
parent: Introduction
grand_parent: EN - Handbook
has_children: false
nav_order: 4
---

# What's new in version 3.x.x ? 
{: .no_toc }

Inhaltsverzeichnis

* TOC
{:toc}


We're happy to announce version v3, which introduces essential concept changes.
The manual has not been fully updated yet, but you can find a brief overview of the most important changes below.


### Software toolkit changes
The Ardunio IDE is no longer actively supported by us. From this version we're relying on Platform IO and VS Code.

You can find the installation video below:
[![Installationsvideo](https://img.youtube.com/vi/KZPjisOEcQ4/hqdefault.jpg)](https://www.youtube.com/watch?v=KZPjisOEcQ4)


## Functional changes

### New setup mode
At first start you can boot the NodeMCU into setup mode. With a display you will see the machine's IP address. Then you can connect to the unit and record(?) it directly via OTA and Platform IO. This mode is automatically activated whenever you turn the machine off and on again within 30 seconds.


### Control interface improvements (Web UI & Blynk)
We have a new web control interface hosted on the NodeMCU's IP address. You can find the IP address on the display or on your router's admin page.
Blynk is still supported, but it is not the central control element of the PID anymore.


## Please contribute!
If you find any bugs, issues or have suggestions, please let us know. 

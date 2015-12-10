---
layout: page
title: Getting Started
permalink: /tutorials/asm/gettingstarted.html
---

The tutorials in this guide assume that you have a decent knowledge of eZ80 assembly. However, if you have no idea where to begin, you will first want to begin with the updated version of [**Asm in 28 Days**](http://media.taricorp.net/83pa28d/lesson/toc.html#lessons), and then introduce yourself to the small changes with the new eZ80 processor, located [**here**]({ site.basurl }/tutorials/asm/ez80diff.html).

The end result of all these tutorials is to construct a simple game of snake, starting with the basics and working towards more advanced things. 

Inside of your *CEasm* directory that you created in the [**setup**]({ site.baseurl }/setup/asmsetup.html) guide, create a new folder called *tutorial_1*. Now, inside the *tutorial_1* directory, create a file called *main.asm*. This is the file in which you will be placing all of the following code.

# The Template

This is the default template for all CE assembly programs. Simply copy and paste into the *main.asm* file.

```asm
#include "..\include\ti84pce.inc"
.assume ADL=1
.db     texttok,tasm84cecmp
.org    usermem

; Start of program code
```

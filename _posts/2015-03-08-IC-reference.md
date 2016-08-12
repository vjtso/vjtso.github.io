---
layout: post
title:  "Gate-Level Basics"
date:   2015-03-08 22:21:49
categories: IC-reference
tags: IC-reference
---
            __
与非 NAND F=AB
            ___
或非 NOR  F=A+B
             _ _
异或 XOR  F=AB+AB
            __  
同或 XNOR F=AB+AB





#### Transmission Gate(TG)
From boolean equation to TG circuit:

Keep in mind of one rule:
When connects the output of two TG together, make sure there always one line being in high impedance whatever the inputs combinations are.

There's a cheating method of doing this, 
Taking F=AB as one example:
![]({{ site.baseurl }}/assets/img/TG1.PNG)
which is quite simple to draw, but uses more transistors.
So what I learnt in school is like this:
![]({{ site.baseurl }}/assets/img/TG2.PNG)


#### Second Order Effects
1. Body Effect

2. Channel Length Modulation(沟道长度调制)

3. 






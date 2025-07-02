---
title: "LQS keyboard"
author: "kubabisi"
description: "Silent low profile custom split keyboard"
created_at: "2025-07-01"
---

# July 1st: Brainstorming and pcb
I started by listing what my keyboard needs to have:
- quiet
- as slim as posible, while being durable to fit in my school bag
- tactile switches - I've tested linear swithes on keyboards in tech shops, but I don't like them - lack of feedback makes me misstype more often
- ~50 keys (number row, 6th column and thumb keys)
- wireless
- usb-c (nearly every device I am using is using it)

Then I searched for switches that would fit in those requirements and I've found them - Kailh Deep Sea Whale mini switches.

Having a list of requirements and switches I started designing.

First I designed the layout in Ergogen. I've used it to make my first keyboard, so I already knew what to do and what I need.
![layout in ergogen](images/ergogen-layout.png)

Once I was happy with the key layout, I started designing the actual circuit. 
BTW: This was my first time using Kicad and designing pcbs.

I've choosen Seeed Studio XIAO nRF52840 as the microcontroller as I want to use ZMK as firmware.

Because I wanted to use Choc v2 switches and Seeed XIAO mcu I needed to find required kicad files before doing anything.
Quickly I've found siderakb's switch footprints and oficial XIAO kicad files.

Schematic is simple. Just switches, diodes and microcontroller. I've also added jumpers to make one pcb for both halves.
![schematic](images/schematic.png)

Then came the time for the pcb. Ergogen generated a base pcb, but I needed to swap all switch footprints to the right ones. (Only later I've read on the Highway website that there is a tool that would have done that for me)

PCB design isn't as hard as I thought, but it is tedious. While I don't think that my pcb is great, it should work just fine.
![pcb front](images/LQS-keyboard-pcb-front.png)
![pcb back](images/LQS-keyboard-pcb-back.png)



Total time spent: ~8 hours
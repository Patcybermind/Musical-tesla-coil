---
title: "Musical tesla coil"
author: "pat/patcybermind"
description: "a solid state tesla coil that plays music"
created_at: "2024-06-28"
---

hours so far: 8

## week of the 22nd:
8 hours
Researched what components i should use and did research on what would work best given the budget and time constraints. At the start the plan was to order everything from amaozn so i twould arrive before undercity so i could get my points and attend
but it turns out you can make a hackpad and get your points immidiately which is what im doing now. 
With that context, there arent many things you can buy off amazon canada and its a bit expensive most of the time. The main problem that bothered me was that, tesla coils work by creating resonance at 100khz-500khz and for that you need to be switching a mosfet
REALLY fast and just like anything, mosfets have a capacitance which means if you want to pull the voltage from high to low or low to high it takes a lot of current to get the voltage down or up fast enough before you need to switch again. Now to power the primary side
this is something that also made me debate if i should use rectified ac from the 120v rms from the wall or downconvert it to 12v or around 24v. the lower the voltage rating on these mosfets i found on amazon the lower the capacitance which meant i could drive them more easily.
Another better and ideal solution would be to use a mosfet driver which i could not find a single one fast enough (fastest was 20khz) on amazon.
Knowing that i wont be using amazon i think ill go with 120v ac rectified and smoothed with capacitors. Though this will need to be a 150 usd 6 point project. It might be possible with 50 usd but im not sure it would end up working and if it did the arcs would be lame :(

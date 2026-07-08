---
title: "QRP Radio Transceiver"
author: "NoxAevi"
description: "Low power radio transceiver"
created_at: "2026-07-8"
---

# 7/8/26: Created design goals

I knew that what I wanted to create generally was a small, low-powered radio that could do both SSB phone and CW communication, but I wanted to flesh out a more detailed description.

The first thing I wanted to do was determine what bands it should support (with the 20m band being a given for it's popularity and availability throughout the day)

When searching for what bands are commonly used for CW, I found that it was generally agreed upon for these four

<img width="618" height="166" alt="image" src="https://github.com/user-attachments/assets/9718b6cb-4802-48d5-8e8f-829e71f8e3ca" />

Then, I did research over what type of radio I would want to make (superhet vs SDR) by first looking at the differences between them and then seeing what other products currently use (qrplabs radio, Icom). Most of them tended to use SDRs, which Icom tending to use FPGAs and qrplabs using an STM32 MCU

After looking at [a website](https://www.onallbands.com/superheterodyne-sdr-hybrid-sdr-which-is-best%EF%BB%BF/) detailing the different types of radios, I learned that there were actually three types of radios (superhet, combining superhet & SDR, only SDR)

To determine which type would be the one I would use for this project, I'm going to do what would allow me to carry out the project the easiest (so demodulating/switching between types of modulation)

Anyways, here's the planning I have so far

<img width="1005" height="651" alt="image" src="https://github.com/user-attachments/assets/7cbb6f18-a894-4154-9491-3147768d1cc4" />

<img width="958" height="189" alt="image" src="https://github.com/user-attachments/assets/8a88ae36-8326-4b6e-8e4a-389fe2191c2a" />



**Total Time Spent:** 0.75 hours

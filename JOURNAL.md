---
title: "Toaster Reflow Oven"
author: "Subhash Muthu"
description: "A Reflow Soldering Oven made from a Toaster Oven."
created_at: "2026-13-06"
---
# June 13th
Day 1.
I guess I should discuss the direction I want for this project. After some research I came up with this:

I want this project to be something that other people can easily replicate. A lot of other projects are out there but the one thing I find in common is that I have to pay for them. Grrr. I want to
make this project completely open so that anybody can replicate what I'm doing at just parts cost.

I've Disassembled the toaster oven and started looking for parts. Based on other builds I think a 40 Amp Solid State Relay(SSR) should be better than a 25 Amp SSR for driving the heating element just 
because it dissipates a little less heat? I'll have to test that. Anyhoo, I also need a K-Type Thermistor and an accompanying MAX31855 chip. I'll probably also need some sort of tape or silicone to insulate
the oven a bit better.

pic of the pcb schematic thus far...
<img width="1006" height="818" alt="image" src="https://github.com/user-attachments/assets/7c5f809d-96ec-48ff-975b-1183b4263adb" />

I'm thinking a small 0.96" OLED display is enough. Sorry everyone in the future squinting their eyes at the screen. This is probably most affordable and least overhead. Besides, WiFi!

pics of the disassembled toaster oven
<img width="4000" height="3000" alt="IMG_20260614_011717984_HDR" src="https://github.com/user-attachments/assets/3c12fb35-99f5-419a-92e4-27e7bab37785" />
<img width="3000" height="4000" alt="IMG_20260614_012529195" src="https://github.com/user-attachments/assets/5800db6b-3baa-431c-af52-a38d59cc211e" />

NVM. I'm doing a full 180 and switching to a 2.2" TFT. ikr? Massive. Its going to be slightly more complex but its gonna be soooo worth it. it uses SPI btw.
Updated Schematic:
<img width="1042" height="853" alt="image" src="https://github.com/user-attachments/assets/3ae6f722-093b-4a00-878a-fbd121a53fd5" />

I should also mention the TFT Breakout Board that i've selected also has a microSD Card slot on it.

Time Spent: 5 Hours

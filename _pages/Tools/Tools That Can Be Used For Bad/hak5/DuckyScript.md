---
title: "DuckyScript"
tags:
    - BruteForce Attack
    - USB
    - hak5
date: "2025-3-30"
thumbnail: "/assets/img/thumbnail/rpi-ducky.jpg"
---

***" DuckyScript 1.0, developed by Hak5 in 2010, is a macro scripting language. It sequentially processes one of two actions: keystroke injection (type a set of keys), and delay (momentarily pause). These actions, written in what is known as a payload, instruct the USB Rubber Ducky on what to do. Either type, or pause.***

***Over the years the DuckyScript language has evolved to include device specific commands. With the introduction of the Bash Bunny in 2017, DuckyScript was coupled with the shell scripting language BASH. Leveraging the Linux base, these Ducky Script payloads allowed the device to perform multi-vector USB attacks.***

***Similarly, DuckyScript was included in the Shark Jack to probe Ethernet networks. The Key Croc uses DuckyScript 2.0 to execute a myriad of hotplug attacks based on live keylogging data. Even third party tools designed in partnership with Hak5 licensed Ducky Script — notably the O.MG Platform of malicious cables and adapters by Mischief Gadgets.***

***With the new USB Rubber Ducky in 2022, DuckyScript 3.0 has been introduced.***

***DuckyScript 3.0 is a feature rich, structured programming language. It includes all of the previously available commands and features of the original DuckyScript.***

***Additionally, DuckyScript 3.0 introduces control flow constructs (if/then/else), repetition (while loops), functions, extensions.***

***Plus, DuckyScript 3.0 includes many features specific to keystroke injection attack/automation, such as HID & Storage attack modes, Keystroke Reflection, jitter and randomization to name a few. "***[^hak5duck]





WIth very simple and relatively cheap tools an entire network can be corrupted with malware. 

With something as simple as a Raspberry Pi Pico can hack an entire computer with something called “DuckyScript”.

This is an example of a setup I have made using this. 



That little device is able to hack my entire computer. In my opinion with all the security I have set up, my computer is a relatively hard thing to hack. 

Currently I have it setup to change my background though it can run any command on a device in a matter of seconds.

This technology can be put into any device that interfaces with a computer. Here is a company making all sorts of these things. (they are also the makers of DuckyScript) 

https://shop.hak5.org 


This is an example of what a BADUSB device running ducky script can do. The BADUSB device is a FlipperZero and the output is from a USBvalve.

<script src="https://asciinema.org/a/NWfC9Mvzzpj3eZfsC7s5Dz1sJ.js" id="asciicast-NWfC9Mvzzpj3eZfsC7s5Dz1sJ" async="true"></script>



[^hak5duck]: Quote from official Hak5 website (shop.hak5.org)
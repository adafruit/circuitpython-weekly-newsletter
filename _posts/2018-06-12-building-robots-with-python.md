---
layout: post
title: "Building robots with Python"
date: 2018-06-12 07:00:00 -0800
categories: weekly
---

## A few random thoughts on building robots with Python

[![Alice]({{ "/assets/alice.jpg" | absolute_url }}){:width="550px"}](https://makezine.com/2011/11/02/zen-and-the-art-of-making/)

A million years ago on Make Magazine I wrote ["Zen and the Art of Making"](https://makezine.com/2011/11/02/zen-and-the-art-of-making/) - Experts stay still; beginners are constantly moving. An expert can point out the difficulty in every project, while the beginner can only see possibilities. I've been thinking about robotics (specifically for young folks) and how it has been at a stand-still in many ways for so long. It's expensive, hard, and unwelcoming. I jotted down some thoughts over the last few weeks while making a robot-a-night, reminds me when I started Hack-a-Day for some the same reasons. My constraint was 30 minutes, materials - junk/trash/recycled part, and I had to film a video with my phone at the end, post it, and the code.

This is a work in progress...

Building robots, especially for beginners, is for the experiences. "Expertise" is a collection of thousands of mistakes, which is later called knowledge. Robotics are imprecise, and robots are built on mistakes.

Robot building projects are experiences that connect skills and chart out the skills to learn. Reading and simulation is not enough! Starting out with a "how a motor works" book is not as useful as making it move in person, or reversing the motion just with changing the polarity.

Every robot building experience is preparation for a future problem to solve that is not known. The physical world is different, everywhere.

Building robots can transform many of the mysterious complexities of the world and "how things work" into smaller, learnable experiences that build on top of each other. It's more like oil painting than architecture.

Building robots is creating real things that combine art, craft, math, and programming skills for specific reason, by example, with working examples.

Robot materials can be cardboard, paper cups, spoons, string...starting with stuff you're going to recycle anyways gives the creator the permission to play, while creating experiences that are familiar combining multiple skills. The more expensive the robot, the less mistakes that can be made!

Block-editors (for code) are just as important as physical building blocks (for example, LEGO-compatibles). Strings in code are just as important as strings on a pulley. Each needs dedicated time and focus to explore, break, fix, and repeat.

Writing code for robotics needs to be real-time, have frequent iterations, most time cannot be spent waiting compiling and sending. This is perfect for CircuitPython. The REPL in the beginner code-editor "Mu", the auto-start after save and the "shows up as a USB drive" features of CircuitPython makes projects easy, fast, and has instant results. It can take less than 5 minutes to have a robot speak "hello world" and move around.

More later - pt.

*Alice came to a fork in the road.  “Which road do I take?” she asked.*

*“Where do you want to go?” responded the Cheshire cat.*

*“I don’t know,” Alice answered.*

*“Then,” said the cat, “it doesn’t matter.”*

– Alice in Wonderland

## CRICKITs of the week!

[![CRICKIT TREK]({{ "/assets/crickittrek.jpg" | absolute_url }}){:width="550px"}](https://youtu.be/oOE2Ht-J2Jc)

CRICKIT "TREK" - To boldly go where no Python has gone before - [video](https://youtu.be/oOE2Ht-J2Jc) & [guide](https://learn.adafruit.com/adafruit-crickit-creative-robotic-interactive-construction-kit/cpx-1701).

MARBLE MADNESS with CRICKIT, it's rollin! - [video](https://youtu.be/enOB2HwDKwM) & [code](https://github.com/adafruit/Adafruit_Learning_System_Guides/blob/master/Crickits/magneat-o/code.py).

Crickit Collapsible House, huff and puff! Watch out piggies' - [video](https://youtu.be/_84qnr2A6Hk).

Crickit Cart Bot Navigation - [video](https://youtu.be/62ywSHoYen0).

## New CircuitPython 3.0.0 Beta Release!

We've released the [next beta version of CircuitPython 3.0.0](https://github.com/adafruit/circuitpython/releases/tag/3.0.0-beta.1). Please test it and let us know how it goes [on Discord](https://adafru.it/discord).

## PLOT of the week!

[![Pulse Plotter Mu]({{ "/assets/mu_pulse_plotter.jpg" | absolute_url }}){:width="550px"}](https://www.youtube.com/watch?v=NghIGWJud58)

Sensor graphing with plotter. CircuitPython + Mu + Heartbeat Pulse [VIDEO](https://www.youtube.com/watch?v=NghIGWJud58) [CODE](https://github.com/adafruit/Adafruit_Learning_System_Guides/blob/master/Sensor_Plotting_With_Mu_CircuitPython/pulse.py) [GUIDE](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/pulse)

In the newsletter here so far, we've had [COLOR](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/color), [POTENTIOMETER](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/potentiometer), [BUTTONS AND SWITCH](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/buttons-and-switch), [CAPACITIVE TOUCH](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/capacitive-touch),  [SOUND](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/sound),  [MOTION](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/motion),  [TEMPERATURE](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/temperature) and [LIGHT](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/light).

## News from around the web!

[![FRACTALS]({{ "/assets/fractals.jpg" | absolute_url }}){:width="550px"}](https://twitter.com/gpshead/status/1005603935413915648)

Greg is working on microcontroller computing fractals to e-Ink in a [CircuitPython interpreter](https://twitter.com/gpshead/status/1005603935413915648).

[Thonny Beta has support for MicroPython and CircuitPython](http://thonny.org/blog/2018/06/05/thonny_and_micropython.html)

[MQTT with Adafruit IO](https://github.com/MikeTeachman/micropython-adafruit-mqtt-esp8266) - Example CircuitPython code for using MQTT with Adafruit IO. Tested with CircuitPython releases 2.3.1 and 3.0.0.

[ASCII art](https://github.com/bbcmicrobit/micropython/blob/e26d7c89d4a96de0fa0a1dd5aec024b31fc4816e/source/microbit/modantigravity.cpp) in Mu with MicroPython.

EduBlocks Editor For microbit - [Getting Started](https://www.kitronik.co.uk/blog/getting-started-edublocks-microbit).

PyDev of the Week: Naomi Ceder from [Mouse vs Python](http://www.blog.pythonlibrary.org/2018/06/11/pydev-of-the-week-naomi-ceder/)

Adafruit CircuitPython Weekly for June 11th, 2018 [Recording](https://youtu.be/L2R_GKuvFwM)

Get your own Blinka PCB pin [from OSH Park](https://oshpark.com/shared_projects/gLEb9MlK)

## Upcoming events!

![Hack Chat]({{ "/assets/hackchat.png" | absolute_url }}){:width="550px"}

June 22nd at 3pm ET the Adafruit team will be doing a "HackChat" on [Hackaday.io](https://hackaday.io/) all about Crickit and CircuitPython. We'll add all the specifics once hackaday posts'em up.

July 23rd to July 29th, 2018 is [EuroPython](https://ep2018.europython.eu/), a community conference with a [call for proposals until May 20th](https://ep2018.europython.eu/en/call-for-proposals/) on every aspect of Python: programming from novice to advanced levels, applications and frameworks, or how you have been involved in introducing Python into your organization.

## New Learn Guides!

[CircuitPython Made Easy on Circuit Playground Express](https://learn.adafruit.com/circuitpython-made-easy-on-circuit-playground-express) from [Kattni](https://learn.adafruit.com/users/kattni)

## Latest releases

CircuitPython's stable release is [2.3.1](https://github.com/adafruit/circuitpython/releases/latest) and its unstable release is [3.0.0-beta.1](https://github.com/adafruit/circuitpython/releases). New to CircuitPython? Start with our [Welcome to CircuitPython Guide](https://learn.adafruit.com/welcome-to-circuitpython).

[20180608](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) is the latest CircuitPython library bundle.

[v1.9.4](https://micropython.org/download) is the latest MicroPython release. Documentation for it is [here](http://docs.micropython.org/en/latest/pyboard/).

[3.6.5](https://www.python.org/downloads/) is the latest Python release. The latest pre-release version is [3.7.0b5](https://www.python.org/download/pre-releases/).

## Contribute!

The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week's draft [on GitHub](https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts) and [submit a pull request](https://help.github.com/articles/editing-files-in-your-repository/) with the changes. Join our [Discord](https://adafru.it/discord) or [post to the forum](https://forums.adafruit.com/viewforum.php?f=60) for any further questions.

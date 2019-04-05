---
layout: post
title: "Contribute to CircuitPython with Git and GitHub!"
date: 2018-07-03 07:00:00 -0800
categories: weekly
---

## Contribute to CircuitPython with Git and GitHub

[![Contribute to CircuitPython with Git and GitHub]({{ "/assets/contribcirpy.jpg" | absolute_url }}){:width="550px"}](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github?view=all)

CircuitPython and many other open source projects use GitHub to maintain the code base. This means if you want to contribute code or documentation, you're going to have to venture into the world of Git and GitHub. Sounds great! Except, GitHub can be confusing at times, and Git is challenging even for expert coders. So, where do you start? You start with this guide! [Contribute to CircuitPython with Git and GitHub](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/overview) takes a proven workflow and breaks it down, step by step, and explains everything along the way. We'll introduce you to all the concepts you need to know, and define all of the terminology we use when discussing the contribution process. You'll learn everything needed to contribute including [forking a repo](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/grab-your-fork), [creating a branch](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/always-work-on-a-branch), [submitting a pull request](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/create-your-pull-request), and [how to handle an open pull request](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/open-pull-request). One of the most important parts of code contribution is the review process, and everyone is welcome to provide feedback. We walk you through each step of the process of both [receiving](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/receiving-a-review) and [giving a review](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/giving-a-review). Even if you've already contributed, it's worth giving this guide a read. You might learn something new to add to your own process!

We firmly believe Code + Community = CircuitPython. But what does this mean? CircuitPython is an open source project, and the beauty of open source projects, is that everyone is welcome to contribute! We've worked hard to create something amazing, but we couldn't have done it alone. Community contributions in every form are an essential part of CircuitPython, and open source as a whole. So if you're ready to contribute, but aren't sure where to start, check out this guide. Before you know it, you'll be contributing like a pro!

## CRICKIT of the week!

[![Trash Panda]({{ "/assets/trashpanda.jpg" | absolute_url }}){:width="550px"}](https://youtu.be/OA4OsgxLPAQ)

Trash Panda "game" made with CRICKIT & CircuitPython. [Code](https://github.com/adafruit/Adafruit_Learning_System_Guides/blob/master/Crickits/climbing_raccoon/code.py) & [video](https://youtu.be/OA4OsgxLPAQ). This Trash Panda, also known as a [raccoon](https://twitter.com/ubs/status/1006901737108770816), game uses capacitive touch, which move the trash panda up if you can climb fast enough and long enough. It moves the steppers, if you stop, the trash panda starts to fall. Don't let that happen. Door sensors detect the top and bottom, NeoPixels light up green for "doing good" or red for "better start climbing better!" When you get to the top, you are transformed and reach the next level of enlightenment.

## New Learn Guides!

[![
CircuitPython on Linux and Raspberry Pi]({{ "/assets/cirpypi.jpg" | absolute_url }}){:width="550px"}](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux?view=all)

[CircuitPython on Linux and Raspberry Pi](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux?view=all). We have a new guide on interfacing hardware with sensors super easy using CircuitPython. We're always looking for ways to make making easier - whether that's making breakout boards for hard-to-solder sensors or writing libraries to simplify motor control.

For a couple years now we've had CircuitPython for microcontrollers like our SAMD21 series with Feather/Trinket/CircuitPlayground/Metro M0, as well as the ESP8266 WiFi microcontroller, nRF52 bluetooth microcontroller and SAMD51 series.

All of these chips have something in common - they are microcontrollers with hardware peripherals like SPI, I2C, ADCs etc. We squeeze Python into 'em and can then make the project portable.

But...sometimes you want to do more than a microcontroller can do. Like HDMI video output, or camera capture, or serving up a website, or just something that takes more memory and computing than a microcontroller board can do...

[Read more](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux?view=all).


[Crickit Powered Minerva Owl Robot](https://learn.adafruit.com/crickit-powered-owl-robot) from [John Park](https://learn.adafruit.com/users/johnpark)

[Blues Playground](https://learn.adafruit.com/blues-playground) from [Jan Goolsbey](https://learn.adafruit.com/users/HarpDude)

[Contribute to CircuitPython with Git and GitHub](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github) from [Kattni](https://learn.adafruit.com/users/kattni)

## Made With Mu - Happy Homemade Horology with Trinket, CircuitPython and Mu

[![Made with Mu]({{ "/assets/muclock.jpg" | absolute_url }}){:width="550px"}](https://madewith.mu/mu/submitted/2018/06/29/clock.html)

Great project over on [madewith.mu](https://madewith.mu/mu/submitted/2018/06/29/clock.html) - After Leila and Emma's digital alarm clock broke, and none of the replacements fitted their requirements, and rather than buy a new one, they used it as an opportunity to learn and make their own. You can read Leila’s full write-up of the project, including source code and circuit designs at her [blog](https://blog.levit.be/we-made-a-clock-with-python/).

## News from around the web!

[![PYBD]({{ "/assets/pybd.jpg" | absolute_url }}){:width="550px"}](https://forum.micropython.org/viewtopic.php?f=19&t=4957)

MicroPython newsletter! A low-volume email containing news and announcements related to MicroPython software and hardware, including new features and new products, the [latest one is here](https://forum.micropython.org/viewtopic.php?f=19&t=4957) and [sign up here](https://micropython.org/newsletter/). Big news in this first one, an overview of the next generation pyboard, the pyboard D-series, or PYBD for short.

The Next Generation of High-Powered Microcontrollers by Alasdair Allan - While the growth of high-level languages on microcontrollers has been slow, (Alasdair) started talking about Javascript on microcontrollers and a possible “third community” well before the ESP-based boards became that community. Over the last year or two we’ve what I can only describe as a watershed moment in the microcontroller world, interpreted languages like Javascript and [Python have become the new normal](https://blog.adafruit.com/2018/06/26/the-next-generation-of-high-powered-microcontrollers/).

[The first issue of micro:mag](https://micromag.cc/issueone/) is here! & [PDF](http://micromag.cc/wp-content/uploads/2018/06/micromag_issue1.pdf). micro:bits In Libraries, micro:bit in Wonderland, Skulls or Snakes Pimoroni’s pin:bit and scroll:bit reviewed! And get to know the Micro:bit Educational Foundation!

New features in Python 3.7 - [Real Python](https://realpython.com/python37-new-features/). [Python 3.7.0](https://www.python.org/downloads/release/python-370/) & [docs](https://docs.python.org/3.7/whatsnew/3.7.html).

PyDev of the Week: Ricky White - [Mouse vs Python](https://www.blog.pythonlibrary.org/2018/07/02/pydev-of-the-week-ricky-white/)

## Upcoming events!

July 23rd to July 29th, 2018 is [EuroPython](https://ep2018.europython.eu/), a community conference with a [call for proposals until May 20th](https://ep2018.europython.eu/en/call-for-proposals/) on every aspect of Python: programming from novice to advanced levels, applications and frameworks, or how you have been involved in introducing Python into your organization.

August 24-28, 2018 is [PyCon.AU](https://2018.pycon-au.org/) in Sydney, Australia. It is the national Python conference for Australia and the home PyCon of MicroPython! Videos of past talks are [here](https://www.youtube.com/user/PyConAU).

## Latest releases

CircuitPython's stable release is [2.3.1](https://github.com/adafruit/circuitpython/releases/latest) and its unstable release is [3.0.0-rc.0](https://github.com/adafruit/circuitpython/releases). New to CircuitPython? Start with our [Welcome to CircuitPython Guide](https://learn.adafruit.com/welcome-to-circuitpython).

[2018702](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) is the latest CircuitPython library bundle.

[v1.9.4](https://micropython.org/download) is the latest MicroPython release. Documentation for it is [here](http://docs.micropython.org/en/latest/pyboard/).

[3.7.0](https://www.python.org/downloads/) is the latest Python release.

## Contribute!

The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week's draft [on GitHub](https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts) and [submit a pull request](https://help.github.com/articles/editing-files-in-your-repository/) with the changes. Join our [Discord](https://adafru.it/discord) or [post to the forum](https://forums.adafruit.com/viewforum.php?f=60) for any further questions.

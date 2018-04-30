---
layout: post
title: "Metro M4 Express!"
date: 2018-03-19 07:00:00 -0800
categories: weekly
---

[![CircuitPython 3.0.0 Logo]({{ "/assets/metro_m4_blinka.jpg" | absolute_url }}){:width="550px"}](https://www.adafruit.com/product/3382)

The [Metro M4 Express](https://www.adafruit.com/product/3382) running CircuitPython was the hot product launch two weeks ago. While the hardware itself is in Beta, CircuitPython is still in Alpha. Last week, we released [CircuitPython 3.0.0 Alpha 6](https://github.com/adafruit/circuitpython/releases/tag/3.0.0-alpha.6). It gets closer to Beta by reintroducing the `nvm` module and audio output support (including I2S). It also introduces real-time clock support and USB HID gamepad support! Please update and let us know how it works for you on [Discord](https://adafru.it/discord)!

## Metro M4 Express Bootloader Fix!

If you managed to order a Metro M4 Express BETA from the very first batch, then please update your bootloader based on [these instructions](https://learn.adafruit.com/adafruit-metro-m4-express-featuring-atsamd51/beta-notes). Without this, there is a risk the bootloader can be corrupted and make it impossible to load new code without a JLink! Subsequent batches won't have this issue.

## PLOT of the week!

![Motion plotter Mu]({{ "/assets/mu_motion_plotter.jpg" | absolute_url }}){:width="550px"}

[VIDEO: Sensor graphing with plotter. CircuitPython + Mu + MOTION](https://www.youtube.com/watch?v=WTCCzxT6kqQ)

[CODE: Sensor Plotting with Mu and CircuitPython - MOTION](https://github.com/adafruit/Adafruit_Learning_System_Guides/blob/master/Sensor_Plotting_With_Mu_CircuitPython/acceleration.py)

[GUIDE: Sensor Plotting with Mu and CircuitPython - MOTION](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/motion)

In the newsletter here so far, we've had [TEMPERATURE and LIGHT](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/light).

## News from around the web!

[Connect a MicroPython based Sensor via MQTT(S) to SAP Leonardo IoT Foundation](https://blogs.sap.com/2018/04/19/connect-a-micropython-based-sensor-via-mqtts-to-sap-leonardo-iot-foundation/)

[BBC micro:bit MicroPython documentation, some recent updates](https://github.com/bbcmicrobit/micropython/blob/master/docs/index.rst) & [readthedocs version](http://microbit-micropython.readthedocs.io/en/latest/)

[Updates for mu are happening! Mu is a small, simple editor for beginner Python programmers. Written in Python and Qt5](https://github.com/mu-editor/mu)

[Did you know you can use the radio on a micro:bit to send messages to other micro:bits or build multiplayer games?](http://microbit-micropython.readthedocs.io/en/latest/tutorials/radio.html)

[MakeCode and MicroPython resources](http://multiwingspan.co.uk/micro.php)

[First steps with micropython using ESP32 and ESP8266 micro controller](https://github.com/jsdungeon/micropython)

[StarTrek game in MicroPython!](https://twitter.com/te3game/status/989875992876302336/photo/1)

[micro:bit film festival](https://twitter.com/BGSICT/status/989794110725910528)

[Python weekly this week includes a garage door opener with MicroPython](https://us2.campaign-archive.com/?u=e2e180baf855ac797ef407fc7&id=7835cfd778). [Join here](https://www.pythonweekly.com/)

[uGame 10 back in stock](https://hackaday.io/project/27629-game/log/145483-in-stock-again) [on Tindie](https://www.tindie.com/products/deshipu/game-10-game-console-kit/)

[ESP8266/NodeMCU - Installing MicroPython, video](https://www.youtube.com/watch?v=aP33PRQesbQ)

## New Learn Guides!

[How to Use PVA Filament](https://learn.adafruit.com/how-use-to-pva) from @Noe and @Pedro

[Building CircuitPython](https://learn.adafruit.com/building-circuitpython) from @dhalbert

[Labo Piano Light FX](https://learn.adafruit.com/labo-piano-light-fx) from @CollinCunningham

## LEEKS! Sneak peeks!

![CRICKIT]({{ "/assets/crickit.jpg" | absolute_url }}){:width="550px"}

We have a [couple](https://www.instagram.com/p/BiIBwJPgU41/?taken-by=adafruit) [videos](https://www.instagram.com/p/BiIBJbMAz2a/?taken-by=adafruit) on the @adafruit Instagram of "CRICKIT" our upcoming CircuitPython-friendly robotics platform that can turn anything like a cardboard box into a robot!

![BLINKA PAPER BETA]({{ "/assets/blinkpaper.jpg" | absolute_url }}){:width="550px"}

We're working on some papercraft projects with BLINKA, the CircuitPython helper snake, [here's a "beta"](https://www.dropbox.com/sh/9nct4dx9zlbhqj3/AAD7OIImuEZi4m9lmQpivH4La?dl=0) of one you can download and cut out, try it out and let us know what ya think!

## Upcoming events!
May 2018 - [The PyCon 2018 conference](https://us.pycon.org/2018/about/), which will take place in Cleveland, is the largest annual gathering for the community using and developing the open-source Python programming language. It is produced and underwritten by the Python Software Foundation, the 501(c)(3) nonprofit organization dedicated to advancing and promoting Python. Through PyCon, the PSF advances its mission of growing the international community of Python programmers. Adafruit is a sponsor, we'll see you in the goodie bag :)

## Latest releases

CircuitPython's stable release is [2.2.4](https://github.com/adafruit/circuitpython/releases/latest) and its unstable release is [3.0.0-alpha.6](https://github.com/adafruit/circuitpython/releases). New to CircuitPython? Start with our [Welcome to CircuitPython Guide](https://learn.adafruit.com/welcome-to-circuitpython).

[20180430](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) is the latest CircuitPython library bundle.

[v1.9.3](https://micropython.org/download) is the latest MicroPython release. Documentation for it is [here](http://docs.micropython.org/en/latest/pyboard/).

[3.6.5](https://www.python.org/downloads/) is the latest Python release.

## Contribute!

The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week's draft [on GitHub](https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts) and [submit a pull request](https://help.github.com/articles/editing-files-in-your-repository/) with the changes. Join our [Discord](https://adafru.it/discord) or [post to the forum](https://forums.adafruit.com/viewforum.php?f=60) for any further questions.

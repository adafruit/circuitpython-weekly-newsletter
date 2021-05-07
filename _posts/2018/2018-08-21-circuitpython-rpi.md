---
layout: post
title: "CircuitPython libraries on the Raspberry Pi!"
date: 2018-08-21 07:00:00 -0800
categories: weekly
---

# CircuitPython libraries on the Raspberry Pi!

[![CircuitPython's Blinka loves Raspberry Pi]({{ "/assets/blinkapi.gif" | absolute_url }}){:width="550px"}](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux)

Kattni, Brennen and Ladyada have been hard at work over the last few weeks to bring our [90 or so CircuitPython libraries](https://pypi.org/search/?q=%22adafruit-circuitpython%22) to the Raspberry Pi and "normal" Python (usually referred to as CPython or just Python). Many guides are now updated with CircuitPython instructions that work both on CircuitPython and CPython. Libraries [are available](https://pypi.org/search/?q=%22adafruit-circuitpython%22) through the standard Python `pip install` process.

This has been a great way to verify that CircuitPython is indeed a subset of CPython. It unifies our library style across CircuitPython and CPython to make it easier to grow from a simple microcontroller CircuitPython to the more advanced CPython on Linux.

The work isn't finished quite yet. In the coming weeks more guides will be updated with CircuitPython library support. Check out the Updated Guides section below to see all of the week's updates. Follow the [CircuitPython on Linux and Raspberry Pi](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux) guide to get started. The legacy Python libraries will also be archived on GitHub in favor of the CircuitPython versions.

## News from around the web!

[![cornelius]({{ "/assets/821cornelius.jpg" | absolute_url }}){:width="550px"}](https://tinkerboi.net/post_id/19)

For day 77/100 of coding in #Python for #100DaysOfcode, meet [Cornelius 2.0!](https://twitter.com/TheTinkerboi/status/1029475838952198145) There is a brief summary of how it was made, and some CircuitPython [code snippets here](https://tinkerboi.net/post_id/19) & [video](https://www.youtube.com/watch?v=Uwf73L_A_6U).

GitHub's blog ["Release Radar" featured Mu 1.0!](https://blog.github.com/2018-08-17-release-radar-july-2018/)

FPGA MicroPython (FuPy) - "The aim of this project is to make MicroPython run on FPGAs using the LiteX & Migen+MiSoC technologies... full stack development (FPGA gateware & soft CPU firmware) in Python!" - [fupy.github.io](https://fupy.github.io/).

PyDev of the Week: Jessica Ingrassellino from [Mouse vs. Python](http://www.blog.pythonlibrary.org/2018/08/20/pydev-of-the-week-jessica-ingrassellino/)

[Adafruit CircuitPython Weekly for August 20th, 2018](https://youtu.be/XBIzLuUPkbU)

## Hallowing - A new member of the family

[![this is hallowing]({{ "/assets/821hallowing.png" | absolute_url }}){:width="550px"}](https://learn.adafruit.com/adafruit-hallowing)

Are you the kind of person who doesn't like taking down the skeletons and spiders until after January? This is electronics at its most spooky! The Adafruit HalloWing is a skull-shaped ATSAMD21 board with a ton of extras built in to make for an adorable wearable, badge, development kit, or the engine for your next cosplay or prop.

On the front is a cute 1.44" sized 128x128 full color TFT. Our default example code has our spooky eye demo running but you can use it for anything you like to display in glorious color.

There's also 4 fang-teeth below the display, these are analog/capacitive touch inputs with big alligator-clip holes.

It has CircuitPython build support so you can pick your favorite development language! The extra 8 MB of SPI Flash is great for sound effects projects where you want to play up to 3 minutes of WAV files - [Adafruit HalloWing M0 Express](https://www.adafruit.com/product/3900) & [learn guide](https://learn.adafruit.com/adafruit-hallowing).

## It's not out yet :)

[![grand central mega]({{ "/assets/821mega.jpg" | absolute_url }}){:width="550px"}](https://blog.hackster.io/adafruits-new-grand-central-board-a-return-to-the-arduino-mega-3f1273b0030)

Adafruit’s New “Grand Central” Board, a Return to the Arduino MEGA? - [hackster.io](https://blog.hackster.io/adafruits-new-grand-central-board-a-return-to-the-arduino-mega-3f1273b0030)

## New Learn Guides!

[![operation]({{ "/assets/821operation.jpg" | absolute_url }}){:width="550px"}](https://learn.adafruit.com/adabot-operation-game)

[Adabot Operation Game](https://learn.adafruit.com/adabot-operation-game) from [John Park](https://learn.adafruit.com/users/johnpark)

[Adafruit IO Environmental Monitor for Feather or Raspberry Pi](https://learn.adafruit.com/adafruit-io-air-quality-monitor) from [Brent Rubell](https://learn.adafruit.com/users/brubell)

[Adafruit Hallowing](https://learn.adafruit.com/adafruit-hallowing) from [Ladyada](https://learn.adafruit.com/users/adafruit2)

[Circuit Playground Express Automatic Sunglasses](https://learn.adafruit.com/circuit-playground-express-auto-sunglasses) from [Dave Astels](https://learn.adafruit.com/users/dastels)

[Make It Log](https://learn.adafruit.com/make-it-data-log-spreadsheet-circuit-playground) from [Mike Barela](https://learn.adafruit.com/users/MikeBarela)

[Make It Switch](https://learn.adafruit.com/make-it-switch) from [Mike Barela](https://learn.adafruit.com/users/MikeBarela)

## Updated Guides - Now With More Python!

**You can use CircuitPython on Raspberry Pi!** We're updating all of our CircuitPython guides to show how to wire up sensors to your Raspberry Pi, and load the necessary CircuitPython libraries to get going using them with Python. We'll be including the updates here so you can easily keep track of which sensors are ready to go. Check it out!

[Adafruit AMG8833 8x8 Thermal Camera Sensor](https://learn.adafruit.com/adafruit-amg8833-8x8-thermal-camera-sensor)

[Adafruit BNO055 Absolute Orientation Sensor](https://learn.adafruit.com/adafruit-bno055-absolute-orientation-sensor)

[Adafruit CCS811 Air Quality Sensor](https://learn.adafruit.com/adafruit-ccs811-air-quality-sensor)

[IS31FL3731 16x9 Charlieplexed PWM LED Driver](https://learn.adafruit.com/i31fl3731-16x9-charliplexed-pwm-led-driver)

[Adafruit LIS3DH Triple-Axis Accelerometer Breakout](https://learn.adafruit.com/adafruit-lis3dh-triple-axis-accelerometer-breakout)

[Adafruit LSM9DS1 Accelerometer + Gyro + Magnetometer 9-DOF Breakout](https://learn.adafruit.com/adafruit-lsm9ds1-accelerometer-plus-gyro-plus-magnetometer-9-dof-breakout)

[Adafruit 20W Stereo Audio Amplifier - MAX9744](https://learn.adafruit.com/adafruit-20w-stereo-audio-amplifier-class-d-max9744)

[Adafruit PCA9685 16-Channel Servo Driver](https://learn.adafruit.com/16-channel-pwm-servo-driver)

[Adafruit Si5351 Clock Generator Breakout](https://learn.adafruit.com/adafruit-si5351-clock-generator-breakout)

[Adafruit Color Sensors](https://learn.adafruit.com/adafruit-color-sensors/overview)

[Adafruit VEML6070 UV Sensor Breakout](https://learn.adafruit.com/adafruit-veml6070-uv-light-sensor-breakout)

[Adafruit VL6180X Time of Flight Micro-LIDAR Distance Sensor Breakout](https://learn.adafruit.com/adafruit-vl6180x-time-of-flight-micro-lidar-distance-sensor-breakout)

[Adafruit DRV2605 Haptic Controller Breakout](https://learn.adafruit.com/adafruit-drv2605-haptic-controller-breakout)

[Adafruit Si4713 FM Radio Transmitter with RDS/RDBS Support](https://learn.adafruit.com/adafruit-drv2605-haptic-controller-breakout)

## Help bring CircuitPython to other languages!

One of the exciting features of CircuitPython 4.x is translated control and error messages. Native language messages will help non-native English speakers understand what is happening in CircuitPython even though the Python keywords and APIs will still be in English. We were inspired by the [awesome translation work](https://mu.readthedocs.io/en/latest/translations.html) done in [mu 1.0.0](http://madewith.mu/mu/releases/2018/07/20/mu-1.html). (They even [discussed the benefit translating error messages](https://github.com/mu-editor/mu/issues/507).) We saw this and loved the idea of both mu and CircuitPython being in one's native language.

So, we've added the mechanics to CircuitPython that allow us to translate strings at build time. However, that's not enough! We need folks to translate the strings themselves.

If you want to help, then please post to the [main issue on GitHub](https://github.com/adafruit/circuitpython/issues/1098) and join us [on Discord](https://adafru.it/discord). Thanks!

## Upcoming events!

Circuit Python: Visualizing Computer Science Principles with Physical Computing by Wanjun. Tuesday, August 21, 2018, 7:00 PM to 9:00 PM - Houston, TX. USA - [PyHou.](https://www.meetup.com/python-14/events/250807263/)

[JupyterCon Community Sprint](https://www.eventbrite.com/e/jupytercon-community-sprint-day-tickets-48679310127) from 9:00am to 5:00pm on Saturday, August 25, at the Hilton Midtown (Murray Hill) - NYC, USA.

August 24-28, 2018 is [PyCon.AU](https://2018.pycon-au.org/) in Sydney, Australia. It is the national Python conference for Australia and the home PyCon of MicroPython! Videos of past talks are [here](https://www.youtube.com/user/PyConAU).

September 15-19, 2018 is [PyCon UK 2018](https://2018.pyconuk.org/) in Cardiff. [draft programme](https://2018.pyconuk.org/programme/)

September 22-23, 2018 is [World Maker Faire](https://makerfaire.com/new-york/) in New York City. Dan, Kattni and Scott from CircuitPython will be attending. Coordinate with them via [Discord](https://adafru.it/discord).

September 27th, 2018 is [Open Source Hardware Summit](https://2018.oshwa.org/) in Boston. Dan, Kattni and Scott from CircuitPython will be attending. Coordinate with them via [Discord](https://adafru.it/discord).

October 27, 2018. As part of PyCon DE 18 PyLadies and MicroPython will be running a
beginner friendly full day hands-on workshop on MicroPython and the
Internet of Things - [Meetup](https://www.meetup.com/de-DE/PyData-Suedwest/events/253574767/).

## Latest releases

CircuitPython's stable release is [3.0.0](https://github.com/adafruit/circuitpython/releases/latest). New to CircuitPython? Start with our [Welcome to CircuitPython Guide](https://learn.adafruit.com/welcome-to-circuitpython).

[20180820](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) is the latest CircuitPython library bundle.

[v1.9.4](https://micropython.org/download) is the latest MicroPython release. Documentation for it is [here](http://docs.micropython.org/en/latest/pyboard/).

[3.7.0](https://www.python.org/downloads/) is the latest Python release.

## Contribute!

The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week's draft [on GitHub](https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts) and [submit a pull request](https://help.github.com/articles/editing-files-in-your-repository/) with the changes. Join our [Discord](https://adafru.it/discord) or [post to the forum](https://forums.adafruit.com/viewforum.php?f=60) for any further questions.

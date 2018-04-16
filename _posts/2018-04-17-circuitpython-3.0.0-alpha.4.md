---
layout: post
title: "CircuitPython 3.0.0 Alpha 4!"
date: 2018-04-17 07:00:00 -0800
categories: weekly
---

## CircuitPython 3.0.0 Alpha 4!

![CircuitPython 3.0.0 Logo]({{ "/assets/circuitpython300a.png" | absolute_url }}){:width="550px"}

[3.0.0 is the latest major revision of CircuitPython](https://github.com/adafruit/circuitpython/releases/tag/3.0.0-alpha.4) and features new support for the SAMD51 (aka M4) and preliminary support for the nRF52 BLE chipset. It also features better memory utilization so more can be loaded in the same amount of space.

This is an alpha release of 3.0.0. Alpha releases do not have the complete API from 2.x and are only meant for testing. (Beta release will have the full API but still need work.) Please use the [latest stable release](https://github.com/adafruit/circuitpython/releases/latest) when first starting with CircuitPython. It is stable.

When you find a bug please [check the current known issues](https://github.com/adafruit/circuitpython/issues) and [file an issue](https://github.com/adafruit/circuitpython/issues/new) if something isn't already known.

To install follow the instructions in our new [Welcome to CircuitPython!](https://learn.adafruit.com/welcome-to-circuitpython/installing-circuitpython) guide. To install the latest libraries, see [this page](https://learn.adafruit.com/welcome-to-circuitpython/circuitpython-libraries) in that guide.

Try [the latest version of the Mu editor](https://learn.adafruit.com/welcome-to-circuitpython/installing-mu-editor) for creating and editing your CircuitPython programs and for easy access to the CircuitPython serial connection (the REPL).

### New Features in CircuitPython 3.0.0
Support for SAMD51 based M4 boards [from Adafruit](https://www.adafruit.com/product/3382). Thanks @tannewt, @dhalbert, @siddacious and all the M4 testers.

Preliminary support for nRF52 BLE capable boards. Thanks @glennrub, @tralamazza, @microbuilder, @arturo182, @hathach and @jerryneedell.

Long-lived heap allocations are better compacted. ([Video](https://www.youtube.com/watch?v=gSfmVdRejTk)) Thanks @tannewt and @dhalbert.

Read the microcontroller's unique id through [`microcontroller.cpu.uid`](https://circuitpython.readthedocs.io/en/latest/shared-bindings/microcontroller/Processor.html#microcontroller.Processor.uid). Thanks @sommersoft!

UART can now be created with only one direction. Thanks @dhalbert!

Files to prevent mac from indexing the drive are created automatically. Thanks @jepler!

`*` and `*=` implemented for `array.array`. Thanks @jepler!

Implemented seeking to non-zero locations. Thanks @aykevl and @jepler.

Detect when USB has been plugged in with [`supervisor.runtime.serial_connected`](https://circuitpython.readthedocs.io/en/latest/shared-bindings/supervisor/Runtime.html#supervisor.Runtime.runtime.serial_connected). Thanks @sommersoft and @dhalbert.

Change file system label (CIRCUITPY by default) using [`storage.getmount("/").label`](https://circuitpython.readthedocs.io/en/latest/shared-bindings/storage/__init__.html#storage.VfsFat.label).

Add [`storage.erase_filesystem()`](https://circuitpython.readthedocs.io/en/latest/shared-bindings/storage/__init__.html#storage.erase_filesystem) to make erasing the file system easy. Thanks @dhalbert!
atmel-samd: usb_hid support include Consumer Controls (aka multimedia keys). Thanks @dhalbert.

Code has been reorganized to ease sharing main code across ports.


## PLOT OF THE WEEK!

![PLOT OF THE WEEK!]({{ "/assets/micropython___circuitpython_MuPlotterLight.png" | absolute_url }}){:width="550px"}

VIDEO: [Sensor graphing with plotter. CircuitPython + Mu + LIGHT](https://www.youtube.com/watch?v=8zCRmguw-_c)

GUIDE: [Sensor Plotting with Mu and CircuitPython - LIGHT](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython)

## News from around the web!
[Get Familiar with CircuitPython with These Great Resources](https://makezine.com/2018/04/12/great-circuit-python-resources/)

[More CircuitPython BLINKA stickers for iOS](https://blog.adafruit.com/2018/04/13/brand-new-adafruit-stickers-for-imessage-2/). [Get the app here](https://itunes.apple.com/us/app/adafruit-stickers/id1291627278?mt=8)

[Mr Zbit's Useful micro:bit links](http://www.zbit-connect.co.uk/links.html)

[A Python Interpreter Written in Python by Allison Kaptur](http://aosabook.org/en/500L/a-python-interpreter-written-in-python.html)

[Over 9,500 developers from almost 150 countries participated to map an accurate landscape of the Python community](https://www.jetbrains.com/research/python-developers-survey-2017/)

[Solar Powered Internet Connected Lawn Sprinkler Project](http://www.movingelectrons.net/blog/2017/10/18/solar-powered-internet-connected-lawn-sprinkler.html). Ideal for watering your flower bed or just keeping bunnies out of your backyard.

[NeoPixel Manicure Guide from @sophy](https://learn.adafruit.com/neopixel-manicure/overview)

[Sensor Plotting with Mu Guide by @kattni](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython)

[LED Trampoline Guide by @Noe, @Pedro and @kattni](https://learn.adafruit.com/led-trampoline)

[Cosplay Glow Fur Raver Bandolier Guide by @Erin St Blaine](https://learn.adafruit.com/cosplay-glow-fur-raver-bandolier)

[Python 2.7.15 release candidate 1 is now available](https://pythoninsider.blogspot.com/2018/04/python-2715-release-candidate-1-is-now.html)

[CircuitPython Weeky Meeting Recording for April 16th, 2018](https://youtu.be/Ai6quAO89o0)

## Upcoming events!
May 2018 - [The PyCon 2018 conference](https://us.pycon.org/2018/about/), which will take place in Cleveland, is the largest annual gathering for the community using and developing the open-source Python programming language. It is produced and underwritten by the Python Software Foundation, the 501(c)(3) nonprofit organization dedicated to advancing and promoting Python. Through PyCon, the PSF advances its mission of growing the international community of Python programmers. Adafruit is a sponsor, we'll see you in the goodie bag :)

## Latest releases
CircuitPython's stable release is [2.2.4](https://github.com/adafruit/circuitpython/releases/latest) and its unstable release is [3.0.0-alpha.4](https://github.com/adafruit/circuitpython/releases). New to CircuitPython? Start with our [Welcome to CircuitPython Guide](https://learn.adafruit.com/welcome-to-circuitpython).

[20180415](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) is the latest CircuitPython library bundle.

[v1.9.3](https://micropython.org/download) is the latest MicroPython release. Documentation for it is [here](http://docs.micropython.org/en/latest/pyboard/).

[3.6.5](https://www.python.org/downloads/) is the latest Python release.

## Contribute!
The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week's draft [on GitHub](https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts) and [submit a pull request](https://help.github.com/articles/editing-files-in-your-repository/) with the changes. Join our [Discord](https://adafru.it/discord) or [post to the forum](https://forums.adafruit.com/viewforum.php?f=60) for any further questions.

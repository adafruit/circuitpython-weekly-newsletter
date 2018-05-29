---
layout: post
title: "CircuitPython 3.0.0 Beta Available!"
date: 2018-05-29 07:00:00 -0800
categories: weekly
---

[![CircuitPython 3.0.0 Logo]({{ "/assets/circuitpython300a.png" | absolute_url }}){:width="550px"}](https://github.com/adafruit/circuitpython/releases/tag/3.0.0-beta.0)

Last week, CircuitPython released their first 3.0.0 Beta release. Unlike the previous alpha releases, this release can do everything the existing 2.0 can do and more! [3.0.0 is the latest major revision of CircuitPython](https://github.com/adafruit/circuitpython/releases/tag/3.0.0-beta.0) and features new support for the SAMD51 (aka M4), real-time clock support, storage enhancements and long integer support on Express and M4 boards. It also features better memory utilization so more can be loaded in the same amount of space.

While in the beta phase, everyone is encouraged to try the new release, update existing code, and test projects. When you find a bug please [check the current known issues](https://github.com/adafruit/circuitpython/issues) and [file an issue](https://github.com/adafruit/circuitpython/issues/new) if something isn't already known.

To install follow the instructions in our new [Welcome to CircuitPython!](https://learn.adafruit.com/welcome-to-circuitpython/installing-circuitpython) guide. To install the latest libraries, see [this page](https://learn.adafruit.com/welcome-to-circuitpython/circuitpython-libraries) in that guide.

## Interview with Numworks

[![Numworks]({{ "/assets/numworks.jpg" | absolute_url }}){:width="550px"}](https://blog.adafruit.com/2018/05/25/adafruit-interviews-numworks-python-programmable-calculator-micropython/)

Adafruit interviews Numworks – The folks who made a Python Programmable calculator!

Adafruit has fallen in love with the NumWorks Python Programmable calculator. We’ve blogged about NumWorks and we carry their [terrific calculator in the shop](https://www.adafruit.com/product/3790).

The calculator is designed to be moddable (for when you don't want to use it just for exams), with 3D models, firmware operating system source code, schematics and board layout details available to the public under a Creative Commons License. It is even possible to build your own 3D-printed collaborative calculator! There is also an [emulator online](https://www.numworks.com/simulator/).

Adafruit asked some questions of Romain Goyet, founder of NumWorks, to find out more about the company and their products. [Hackaday](https://hackaday.com/2018/05/18/open-source-calculator-teaches-us-about-quality-documentation/) did an article a week or so ago about NumWorks discussing the extensive documentation on the design and build of the device.

[Full interview here](https://blog.adafruit.com/2018/05/25/adafruit-interviews-numworks-python-programmable-calculator-micropython/).

## PLOT of the week!

[![Potentiometer Plotter Mu]({{ "/assets/mu_potentiometer_plotter.jpg" | absolute_url }}){:width="550px"}](https://youtu.be/_NXcJ30KhSI)

Sensor graphing with plotter. CircuitPython + Mu + Potentiometer [VIDEO](https://youtu.be/_NXcJ30KhSI) [CODE](https://github.com/adafruit/Adafruit_Learning_System_Guides/blob/master/Sensor_Plotting_With_Mu_CircuitPython/potentiometer.py) [GUIDE](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/potentiometer)

In the newsletter here so far, we've had [BUTTONS AND SWITCH](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/buttons-and-switch), [CAPACITIVE TOUCH](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/capacitive-touch),  [SOUND](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/sound),  [MOTION](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/motion),  [TEMPERATURE](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/temperature) and [LIGHT](https://learn.adafruit.com/sensor-plotting-with-mu-and-circuitpython/light).

## CRICKITS

[![CRICKITS of the week]({{ "/assets/trapeze.jpg" | absolute_url }}){:width="550px"}](https://www.youtube.com/playlist?list=PLjF7R1fz_OOW4YvQEoRLmocKUuOgvI-wh)

Crickit is our CircuitPython runnin' Creative Robotics & Interactive Construction Kit. It's an add-on to our popular Circuit Playground Express that lets you #MakeRobotFriend using CircuitPython, MakeCode, Arduino, etc.. robotics, arts, crafts, audio animatronics, sensors, agriculture/robot farming, physical computing, kinetic sculptures, science experiments, telescope control...

Each week we'll have some the video from around the fruit' as we experiment! [Video playlist here](https://www.youtube.com/playlist?list=PLjF7R1fz_OOW4YvQEoRLmocKUuOgvI-wh).

Unchained Melody - How to make (ghost) slime with Crickit. Ladyada was unable to get to sleep. Feeling restless she decided to visit her workshop and make some slime to help soothe her soul. Then her companion showed up to lend a hand and have fun together! - [video](https://youtu.be/mSn3j91k93c).

Robot trapeze with CRICKIT. This Flying Trapeze bot uses a servo claw to grip onto a willing gymnast, and release it into the air when the detected acceleration has reached a sufficient peak! - [video](https://youtu.be/zpqr9nGbG9o).

CRICKIT R.O.B. Robotic Operating Buddy. We picked up a Nintendo R.O.B. robot from our local online auction site and when it appeared we decided to figure out how to get it working. There's 3 motors inside, and the R.O.B. already comes with motor drivers and end-stops, so instead of driving the robot directly, we decided to control the R.O.B. using Circuit Playground Express (CPX) and Crickit! - [video](https://youtu.be/ffAuebA5WAo).

A Star Wars "force wave" for motors. This project is pretty simple, it looks to see when the light sensor is shaded by your hand and changes the motor from running to off or vice versa - [video](https://youtu.be/z_C2dkLVfIY).

"Sound" motor control. Ladyada will blow your house down little piggies! To everything ... turn, turn, turn - [video](https://youtu.be/h-pKfdNgQkI).

## LEEKS!

We are making a CircuitPython based gaming platform! 

[![Pygame Leek]({{ "/assets/pygame.png" | absolute_url }}){:width="550px"}](https://blog.adafruit.com/2018/05/25/we-are-making-a-circuitpython-based-gaming-platform-adafruit/)

With so many robots going on we wanted to take a little break and design some new hardware. This is a spin on our 2.4″ TFT Featherwing that expands it into a full gaming platform. It will make make a great companion to the upcoming SAMD51 Feather, or with the ESP32 feather. Currently we’re thinking 70mm x 100mm (2.75″x4″) would be a nice pocketable size.

There’s a 320×240 color 2.4″ TFT w/resistive touch (captouch is a bit more $ still but we’ll look into it), SD card slot for storing game assets/music/files, 8 multiplexed buttons w/no-ghosting, on/off switch, analog stereo headphone out, when not plugged in a mono speaker, and 1200mAh battery (feather has built in battery charging).

We think this could make for a very nice CircuitPython game platform – the SAMD51 can buffer a full frame of video and then DMA it out in the background so that all the CPU time is spent on making things blink and beep.

We’re still sketching out the design, see our current schem/board, and we wanted to see what the community could suggest – what’s your favorite DIY portable game system? Post up in the comments on the [Adafruit blog](https://blog.adafruit.com/2018/05/25/we-are-making-a-circuitpython-based-gaming-platform-adafruit/) or stop by [Discord](https://adafru.it/discord).

## News from around the web!

@deshipu [wrote up a great recap of a CircuitPython memory debugging adventure](https://hackaday.io/project/86818-game-turbo/log/146645-debugging-circuitpython)

[MicroPython-powered Lucky Cat](https://martinfitzpatrick.name/article/lucky-spinning-arm-message-cat/)

[MicroPython-powered Worm Robot](https://www.youtube.com/watch?v=9fHB7VB73dg) from OutoftheBOTS_ on the [MicroPython forum](https://forum.micropython.org/viewtopic.php?f=5&t=4782)

micro:bit broadcast Final Issue #34. It's the final one, HOWEVER, there is an [official one](https://microbit.us14.list-manage.com/subscribe?u=e1c30f24b90ff3d70275cfff2&id=4595d5f877), and an [awesome list](https://github.com/carlosperate/awesome-microbit). All the previous ones are [here](https://microbit-broadcast.embeddedlog.com/).

## Upcoming events!

June 8th to June 10th, 2018 is the [PyLondinium](https://pylondinium.org/) conference in the UK, organised by PSF volunteers in the City of London. There are at least MicroPython sessions: [Micropython Gotchas](https://pylondinium.org/talk.html?talk_id=7) & [MicroPython used in industrial applications](https://pylondinium.org/talk.html?talk_id=15).

July 23rd to July 29th, 2018 is [EuroPython](https://ep2018.europython.eu/), a community conference with a [call for proposals until May 20th](https://ep2018.europython.eu/en/call-for-proposals/) on every aspect of Python: programming from novice to advanced levels, applications and frameworks, or how you have been involved in introducing Python into your organization.

## New Learn Guides!

[Storage humidity and temperature monitor](https://learn.adafruit.com/storage-humidity-and-temperature-monitor) from @dastels

[Animatronic Hand](https://learn.adafruit.com/animatronic-hands) from @JohnPark

[Makey Paper Craft](https://learn.adafruit.com/makey-paper-craft) from @Noe and @Pedro

[Installing Microsoft MakeCode for Adafruit](https://learn.adafruit.com/installing-makecode-for-adafruit) from Brennen Bearnes

[Adafruit pIRkey](https://learn.adafruit.com/adafruit-pirkey-python-programmable-infrared-usb-adapter) from @ladyada

[Debugging CircuitPython On SAMD w/Atmel Studio 7](https://learn.adafruit.com/circuitpython-samd-debugging-w-atmel-studio-7) from @sommersoft

[Controlling a Classic Nintendo R.O.B. Robot Using Circuit Playground Express](https://learn.adafruit.com/controlling-a-classic-nintendo-r-o-b-robot-using-circuit-playground-express) from Mike Barela

[Trash Panda](https://learn.adafruit.com/trash-panda-circuit-python-crickit) from @Dano

## Latest releases

CircuitPython's stable release is [2.3.1](https://github.com/adafruit/circuitpython/releases/latest) and its unstable release is [3.0.0-beta.0](https://github.com/adafruit/circuitpython/releases). New to CircuitPython? Start with our [Welcome to CircuitPython Guide](https://learn.adafruit.com/welcome-to-circuitpython).

[20180525](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) is the latest CircuitPython library bundle.

[v1.9.4](https://micropython.org/download) is the latest MicroPython release. Documentation for it is [here](http://docs.micropython.org/en/latest/pyboard/).

[3.6.5](https://www.python.org/downloads/) is the latest Python release. The latest pre-release version is [3.7.0b4](https://www.python.org/download/pre-releases/).

## Contribute!

The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week's draft [on GitHub](https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts) and [submit a pull request](https://help.github.com/articles/editing-files-in-your-repository/) with the changes. Join our [Discord](https://adafru.it/discord) or [post to the forum](https://forums.adafruit.com/viewforum.php?f=60) for any further questions.

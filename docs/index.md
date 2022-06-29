# Project 03: Raspberry Pi


# Description
Building open embedded linux image for Raspberry Pi 4 and interfacing of Ultrasonic sensor with it.


# Duration
40 hours / 1 week


# Skills
* General Electronics
* Electronics Circuits
* Programming
* Open Embedded Linux
* Yocto
* Ultrasonic sensor


# Attachments
* Getting_Started_with_Embedded_Linux-_Using_the_Yocto_Project_to_Build_your_Own_Custom_Embedded_Linux_Distribution.pdf
* yocto-dev-manual.pdf


# Forewords
10 Fun Facts About Raspberries!

1. According to legend, raspberries were originally white. The nymph Ida pricked her finger while picking berries for the crying infant Jupiter, and raspberries have since been tinged red with her blood.

2. Makes the botanical name of the raspberry, Rubus idaeus, make a lot more sense. Rubus means “red,” and idaeus means “belonging to Ida.”

3. A raspberry is made up of many tiny bead-like fruits called “drupelets” clustered around a center core. Each drupelet contains one seed, and an average raspberry has 100 to 120 seeds. {Who knew?}

4. Raspberries are either red, purple, gold or black in color. Golden raspberries are a bit sweeter than the other varieties.

5. An old myth about raspberries originates in Germany and claims there are magical qualities of raspberries. It was believed that to tame a bewitched horse, one would have to tie a wild raspberry twig around the horse’s body.

6. It has been suggested that drinking raspberry leaf tea shortens the second stage of labor. {Oh please!}

7. Unlike many other fruits, unripe raspberries do not ripen after they are picked. If you want a ripe raspberry, you need to be patient!

8. The main difference between raspberries and blackberries is that raspberries have a hollow core in the middle while blackberries do not.

9. In the US, about 90% of all raspberries sold come from Washington, California and Oregon.

10. Blackberries are not the same as “black raspberries.” Blackberries have a “core” that stays in the fruit when it is picked, and, unlike black raspberry canes which grow upright, blackberry canes are long and trailing.

Now let's have some Raspberry Pi!


# Introduction
This project is the opportunity of using Yocto to create an embedded Linux image for Raspberry Pi 4. Yocto provides a set of powerful tools that allow you to tailor Linux to meet all your embedded hardware and software needs. There is a very steep learning curve to the Yocto tools, even if you're already pretty familiar with Linux and embedded systems. Call it Hacking Rapberry 4 because you're going to be going away from the easy-to-install images that are available for the board, and instead tinker around with the bootloader, device tree, kernel, and root filesystem using Yocto. And at last you have to use your custom build image for Raspberry Pi 4 that can be interfaced with an Ultrasonic sensor.


# Objectives
* Use Yocto
* Create a custom image with necessary packages that can be distributed on a large number of boards.
* Generate a customized device tree, ramdisk root filesystem, or bootloader.
* Gain a better understanding of what basic files are needed to get Linux up and running on a Raspberry Pi.


# Common Instructions
Safety first! Electronics is a potentially dangerous hobby. Any circuit that works with 120 VAC power from an electrical outlet is especially dangerous and could potentially kill you. Here are some safety guidelines to keep you safe as you work:
* Never work on a circuit while power is applied.
* Do not connect power to a circuit until the circuit is finished and you have carefully checked your work.
* If you smell anything burning, immediately disconnect the power and examine your circuit to find out what went wrong.
* Keep your work area dry.
* Always wear safety goggles.
* Be careful around large capacitors; they can continue to hold voltage long after they are disconnected from power.
* Be especially careful when you solder because a hot soldering iron can easily burn you.
* Always work in a well-ventilated space.
* Have safety equipment such as a fire extinguisher, a first-aid kit, and a phone nearby.


# Mandatory part
* You must interface ultrasonic sensor with Raspberry Pi 4 running Raspberry Pi Image (prebuilt).
* You must replace Raspberry Pi Image with a custom build Open Embedded Linux image built using Yocto.
* You must document a How To guide and do a 15 mins presentation.


# Bonus part
* Interface Speed sensor, temperature sensor with Raspberry Pi 4


# Submission & Peer evaluation
How to do peer evaluation

---
title: 'Using the Board Manager'
difficulty: beginner
description: 'Learn how the new board manager tool works, and how to easily install the boards you want to use in the Arduino IDE 2.0.'
tags:
 - Installation
 - Tools
author: 'Karl Söderby'
---

The board manager is a great tool for installing the necessary cores to use your Arduino boards. In this quick tutorial, we will take a look at how to install one, and choosing the right core for your board! 

You can easily download the editor from the [Arduino Software page](https://www.arduino.cc/en/software#experimental-software). 

You can also follow the [downloading and installing the Arduino IDE 2.0](/en/Tutorial/getting-started-with-ide-v2/ide-v2-downloading-and-installing) tutorial for more detailed guide on how to install the editor.

## Requirements

- Arduino IDE 2.0 installed. 

## Why Use the Board Manager?

The board manager is a tool that is used to install different cores on your local computer. So what is a **core**, and why is it necessary that I install one?

Simply explained, a core is written and designed for specific microcontrollers. Arduino offers several different types of boards, and these boards may also have different types of microcontrollers. 

For example, an Arduino UNO has an **ATmega328P**, which uses the **AVR core**, while an Arduino Nano 33 IoT has a **SAMD21** microcontroller, where we need to use the **SAMD core**.  

In conclusion, to use a specific board, we need to install a specific core. 

## Installing a Core

Installing a core is quick and easy, but let's take a look at what we need to do. 

**1.** Open the Arduino IDE 2.0. 

**2.** With the editor open, let's take a look at the left column. Here, we can see a couple of icons. Let's click the on the **Arduino board** icon.

![The board manager.](assets/installing-a-core-img01.png)

**3.** A list will now appear of all available cores. Now let's say we are using an **Nano 33 BLE** board, and we want to install the core. Simply enter the name in the search field, and the right core (Mbed OS Nano) will appear, where the Nano 33 BLE features in the description. Click on the **"INSTALL"** button.

![Navigating the board manager.](assets/installing-a-core-img02.png)

**4.** This will begin an installation process, which in some cases may take several minutes. 

![Installation may take a few minutes.](assets/installing-a-core-img03.png)

**5.** When it is finished, we can take a look at the core in the boards manager column, where it should say **"INSTALLED"**.

![Board is installed.](assets/installing-a-core-img04.png)

Congratulations! You have now successfully downloaded and installed a core on your machine, and you can start using your Arduino board! 

### More Tutorials

You can find more tutorials in the [Arduino IDE 2 documentation page](/software/ide-v2/).
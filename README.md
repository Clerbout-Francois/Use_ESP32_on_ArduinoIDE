# Use ESP32 on Arduino IDE

If it is the first time you use a microcontroller ESP32 on Arduino IDE, you will need to follow this steps in order to be able to upload code on it.

<a name="table_of_contents"/>

## Table of Contents
1. [Introduction](#introduction_)
2. [Instructions](#instructions_)


<a name="introduction_"/>

## Introduction

![alt text](https://github.com/Clerbout-Francois/Use_ESP32_on_ArduinoIDE/blob/main/images_ESP32/ESP32_diagram.png?raw=true)

_Figure 1: ESP32 NodeMCU Development board Pinout Diagram._

The ESP32 is a small electronic board, called a microcontroller, easy to use thanks to its similarities with the Arduino board which is much more widespread.

The ESP32 is arguably the microcontroller board that has the best size/connectivity/input/output compromise. It is suitable for the production of prototypes and not only to the realization of "finished and definitive" projects, it is also very cheap. It is a reference in the maker universe for these many reasons, so it is very easy to find help on the Internet to use this card.

I think it is a formidable tool for the miniaturization of connected projects. 

The avantages of this microcontroller over an Arduino board is that it contains within its architecture a (built-in) module Wi-Fi as well as its Bluetooth chip (which can be used in a BLE mode for _Bluetooth Low Energy_).

You can program it using the Arduino IDE. For that, I will explain how to add it on the software.

<a name="instructions_"/>

## Instructions

If you have already download Arduino IDE, please go directly to the following steps. If no, you can download it on the official website of Arduino [here](https://www.arduino.cc/en/software) and be sure to choose the correct option (depending of your computer).

You have to add the ESP32 on the Arduino IDE.

Open tab File > Preferences (Fichier > Préférences in french) and you will have to paste this link https://dl.espressif.com/dl/package_esp32_index.json in the Additional Board Manager URL (URL de gestionnaire de cartes supplémentaires in French) as it is explained on the next figures.

![alt text](https://github.com/Clerbout-Francois/Use_ESP32_on_ArduinoIDE/blob/main/images_ESP32/IDE_1.png?raw=true)

_Figure 2: Tab File > Preferences._

![alt text](https://github.com/Clerbout-Francois/Use_ESP32_on_ArduinoIDE/blob/main/images_ESP32/IDE_2.png?raw=true)

_Figure 3: Paste the URL on Arduino IDE._

Once you have done all this steps, always on the Arduino IDE open tab Tool > Board Type > Board Manager (onglet Outil > Type de carte > Gestionnaire de carte in french).

![alt text](https://github.com/Clerbout-Francois/Use_ESP32_on_ArduinoIDE/blob/main/images_ESP32/IDE_3.png?raw=true)

_Figure 4: Tab Tool > Board Type > Board Manager._

Then, search the ESP32 package in the Board Manager (Gestionnaire de carte in french) and install the last version. Do not interrrupt the download !!

![alt text](https://github.com/Clerbout-Francois/Use_ESP32_on_ArduinoIDE/blob/main/images_ESP32/IDE_4.png?raw=true)

_Figure 5: Search and install ESP32 package._

Once you have done all this steps you just have to add the ESP32 on Arduino IDE : open tab Tool > Map Type (onglet Outil > Type de carte in french) and choose the correct ESP32 board according to the one you have (most often it will be the DOIT ESP32 DEVKIT V1 or the ESP32 Dev Module).


![alt text](https://github.com/Clerbout-Francois/Use_ESP32_on_ArduinoIDE/blob/main/images_ESP32/IDE_5.png?raw=true)
![alt text](https://github.com/Clerbout-Francois/Use_ESP32_on_ArduinoIDE/blob/main/images_ESP32/IDE_6.png?raw=true)
_Figure 6: Choose the correct ESP32 board._

Please do not hesitate to contact me if you have any question.

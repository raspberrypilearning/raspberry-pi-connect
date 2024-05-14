## Introduction

Raspberry Pi Connect provides a way to connect to your Raspberry Pi computer from any web browser. 

--- collapse ---
---
title: What you will need
---
### Hardware

+ Raspberry Pi 5, Raspberry Pi 4 or Raspberry Pi 400 computer
+ Monitor
+ Keyboard 
+ Mouse
+ Another computer you wish to connect to your Raspberry Pi from

### Software

+ Raspberry Pi OS Bookworm (64-bit)
+ Web browser, on the computer you are connecting from

--- /collapse ---

## Set up a Raspberry Pi ID
--- task ---

In a web browser, visit [https://id.raspberrypi.com/sign-up](https://id.raspberrypi.com/sign-up) and fill in the form to register for a Raspberry Pi ID.

**Note:** A Raspberry Pi ID is an account on raspberrypi.com, which is separate to an account you may already have on this site, raspberrypi.org 

--- /task ---

## Install Raspberry Pi Connect
--- task ---

On your Raspberry Pi, open a terminal. Type in each of the the commands below, one by one, to install the latest version of Raspberry Pi Connect. 

--- code ---
---
language: bash
line_numbers: false
---
sudo apt update
sudo apt upgrade
sudo apt install rpi-connect
--- /code ---

--- /task ---

--- task ---

Once you have installed Raspberry Pi Connect, restart your Raspberry Pi by typing the reboot command.

--- code ---
---
language: bash
line_numbers: false
---
sudo reboot
--- /code ---

--- /task ---

## Link your Raspberry Pi to your Raspberry Pi ID
Once your Raspberry Pi has rebooted, you will see a new icon

--- task ---



--- code ---
---
language: bash
line_numbers: false
---
sudo apt update
sudo apt upgrade
sudo apt install rpi-connect
--- /code ---

--- /task ---
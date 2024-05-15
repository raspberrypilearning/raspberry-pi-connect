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

In a web browser on any computer, visit [https://id.raspberrypi.com/sign-up](https://id.raspberrypi.com/sign-up) and fill in the form to register for a Raspberry Pi ID.

**Note:** A Raspberry Pi ID is an account on raspberrypi.com, which is separate to an account you may already have on this site, raspberrypi.org 

--- /task ---

## Install Raspberry Pi Connect
--- task ---

With your Raspberry Pi connected to a monitor, keyboard and mouse, open a terminal. Type in each of the the commands below, one by one, to install the latest version of Raspberry Pi Connect. 

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
Once your Raspberry Pi has rebooted, you will see a new icon on the desktop for Raspberry Pi connect.

--- task ---
Click on the icon and select "Sign in".

![Raspberry Pi connect icon](/images/rpiconnect_icon.jpg)

--- /task ---

--- task ---
Sign in with your Raspberry Pi ID.

![Sign in to Raspberry Pi connect](/images/sign_in.jpg)

--- /task ---

## Access your Raspberry Pi remotely

Now that your Raspberry Pi is registered with your Raspberry Pi connect account, you can use a browser to access it from anywhere. 

--- task ---

Open a browser window and visit [https://connect.raspberrypi.com](https://connect.raspberrypi.com).

Log in with your Raspberry Pi account.

--- /task ---

--- task ---

Find your Raspberry Pi in the list and click the "Connect" button

![Connect to the Raspberry Pi](/images/connect.jpg)

If you connect more than one Raspberry Pi in this way, you will see each machine in the list and can choose which one to connect to. 

--- /task ---

A new window will appear, and after you have been connected you will see your Raspberry Pi's desktop. You can now use the Raspberry Pi as normal, via the browser.

![Use the Raspberry Pi via screen share](/images/sign_in.jpg)
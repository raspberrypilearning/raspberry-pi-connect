## Introduction

Raspberry Pi Connect provides a way to connect to your Raspberry Pi computer from any web browser. 

--- collapse ---
---
title: What you will need
---
### Hardware

+ Raspberry Pi 5, Raspberry Pi 4 or Raspberry Pi 400 computer
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

## Install Raspberry Pi connect
--- task ---

On your Raspberry Pi, open a terminal

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



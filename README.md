# 2420-assignment-3
## Table of Contents
1. [Introduction](#introduction)
2. [Instructions](#instructions)
3. [Web Server Result](#Web_Server_Result)

## Introduction
In this repository, you will find a file named `setup`. Running this file will set up a bash script that generates a static `index.html` file containing system information that will automatically run every day at 5:00 AM PST. Then displaying the `index.html` on a web server hosted on your Arch Linux droplet using Nginx. Additionally, it includes a `ufw` firewall configuration for system security.

## Instructions
To start off, you will need to clone this repository into your home directory.
Use the following command to clone the repository:
```
https://github.com/Abungo-w/2420-assignment-3.git
```
Then go into the new directory you just cloned named `2420-assignment-3` and run the file named `setup`.
Use the following command to run the setup file:
```
sudo ./setup
```
> **_NOTE:_**  Make sure your linux system is upto date before you run the setup file.

## Web Server Result
This is what the webpage should look like when you enter your Arch Linux droplet IP address on a web browser.
![The webpage for index.html](./assets/success-screenshot.png)

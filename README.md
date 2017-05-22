# OpenBMC
The OpenBMC project can be described as a Linux distribution for embedded devices that have a BMC; typically, but not limited to, things like servers, top of rack switches or RAID appliances. The OpenBMC stack uses technologies such as Yocto, Open-Embedded, Systemd and DBus to allow easy customization for your server platform.

## Prerequisite
Make sure you have node.js installed in your system. You can install it from https://nodejs.org/en/ 
We recommend v7.10.0 or higher. Once installed, you can check the version number by 

`node -v`

## Repo
The code repo can be found in
`https://github.com/iftekharuli/openbmc`

## Download the source
`git clone git@github.com:iftekharuli/openbmc.git`

## Installation
You can go to project directory and run- 
`npm-install`

## Minify vendors
`npm run-script minifyvendors`

## Distribution
`npm run-script distribution`

## Running
'npm run-script serve'

This will run it locally in http://localhost:8080
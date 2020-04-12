# distro.tools

This is a collection of shell scripts for easy management of your Linux install. The goal is to provide scripts for every possible use case from updating your system to configuring some special things. Feel free to provide your scripts.

## How to use

It's simple. Just type this into your terminal and replace `script` with the script to execute:

    wget -qO- distro.tools/script | sh

when the script doesn't need sudo, or

    sudo sh -c 'wget -qO- distro.tools/script | sh'

when the script needs sudo privileges.

## How to contribute

To request a new script, just create an [issue](https://github.com/jlelse/distro.tools/issues).

To add a script, just clone this [repository](https://github.com/jlelse/distro.tools) and create a pull request. If I ([jlelse](https://github.com/jlelse)) like it, I will accept it.

## Overview of scripts

These scripts are made to work with amd64 and aren't guaranteed to work with other architectures.

### All

Scripts applicable on most distributions:

#### Install

`install/docker-compose` (sudo) - Install Docker Compose  
`install/golang` (sudo) - Install Go *(requires tar)*  
`install/gradle` (sudo) - Install Gradle *(requires jq, unzip)*  
`install/hugo` (sudo) - Install Hugo (extended version) *(requires tar)*  
`install/lazygit` (sudo) - Install lazygit *(requires tar)*  
`install/node` (sudo) - Install NodeJS using n  
`install/postman` (sudo) - Install Postman *(requires tar)*  
`install/telegram` (sudo) - Install Telegram *(requires tar, xz-utils)*  
`install/vscode` (sudo) - Install Visual Studio Code *(requires tar)*  

### Ubuntu

Scripts focused on Ubuntu and derivates:

`ubuntu/update` (sudo) - Update your Ubuntu system including Snaps and Flatpaks  

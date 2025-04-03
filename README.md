# DiscordAPT
A Github Pages hosted APT/Debian repository for installing Discord  

Pulls the latest `deb` file from Discord nightly.


## Notice
This repository is a bit tricky to setup for beginners. For an easier (and more maintained) way to install discord via command-line please go look at the [Snapcrafters community project](https://github.com/snapcrafters/discord).


## Setup
```bash
curl -s --compressed "https://grandmoff100.github.io/DiscordAPT/discordapt.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/discordapt.gpg > /dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/discordapt.list "https://grandmoff100.github.io/DiscordAPT/discordapt.list"
sudo apt update
```

## Install
```bash
sudo apt install discord
```

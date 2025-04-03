# DiscordAPT
A Github Pages hosted APT/Debian repository for installing Discord  

Pulls the latest `deb` file from Discord nightly.


## Notice
This repository is no longer needed as of April 1, 2025. Please go look at the [Snapcrafters community project](https://github.com/snapcrafters/discord).


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

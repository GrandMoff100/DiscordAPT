# DiscordAPT
A Github Pages hosted APT repository for installing discord.


## Usage
```bash
curl -s --compressed "https://grandmoff100.github.io/DiscordAPT/discordapt.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/discordapt.gpg > /dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/discordapt.list "https://grandmoff100.github.io/DiscordAPT/discordapt.list"
sudo apt update
```

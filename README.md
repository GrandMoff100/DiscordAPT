# DiscordAPT
A Github Pages hosted APT repository for installing discord.


## Importing The Key

```bash
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://grandmoff100.github.io/Release.gpg > /etc/apt/keyrings/discordapt.gpg
```

## Adding the package to your APT repos

```bash
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/discordapt.gpg] https://grandmoff100.github.io/ /" | sudo tee /etc/apt/sources.list.d/discordapt.list > /dev/null
```

## Install the package
```bash
sudo apt install discord
```

# Nitro.Self V3

[![GitHub release](https://img.shields.io/github/v/release/noto-rious/Nitro.Self-V3)](https://github.com/noto-rious/Nitro.Self-V3/releases)

Multi-Account Discord Nitro sniper and Giveaway joiner written in Go.

Main Snipe functionality credit goes to ![@Vedzaa](https://github.com/Vedzaa).  
Multi-Account threading along with code-caching for dupe protection and a few other nick-nacks are courtesy of me.

It also sends a DM to giveaway host when won.

You can now enable or no Giveaway joiner and setup a cooldown of x hours each x nitros applied.

![Screenshot](screenshot.png)

### Usage

Edit `settings.json`
```
{
  "token": "", // Your main token here
  "nitro_max": 2, // Max Nitro codes redeemed before cooldown
  "cooldown": 24, // in Hour
  "giveaway_sniper": true // Enable giveaway sniping or not.
  "snipe_on_main": true // Enable sniping on the main account or not.
}

```

```
 go mod download
 go build
 ./Nitro.Self-V3
 ```
 
### How to obtain your token
https://github.com/Tyrrrz/DiscordChatExporter/wiki/Obtaining-Token-and-Channel-IDs#how-to-get-a-user-token

### Disclaimer
This can get your account banned if you run multiple instance at the same time and/or claim too much Nitros in a too short amount of time. Use it at your own risks.

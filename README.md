# otobo-dark-skin
A dark skin for OTOBO

![OTOBO Dark Skin](/screenshot.png?raw=true)

OTOBO is a fork based on the ((OTRS)) Community Edition.

- https://otobo.de
- https://github.com/RotherOSS/otobo

## Motivation
At the time of this release, only one default skin is included in OTOBO, and the colors used there are way too bright and shiny for me personally. So I decided to create a dark skin for OTOBO based on the files included in the default skin.

It's possible that it doesn't work well with all add-on packages, since I focused exclusively on packages I use, which are the following so far:
- FAQ
- Survey

## Installation
### OTOBO Package Manager
The skin plugin can be installed using the `OTOBO Package Manager` (Admin > Administration > Package Manager). 
Please download the `OPM` file from [Releases](https://github.com/relkai/otobo-dark-skin/releases) and install it using the `Install Package` button.

### OTOBO System configuration 
OTOBO offers a powerfull `System configuration` (Admin > Administration > System configuration) to change the behavior of the frontend. 

If you want this skin to be the default one for all new users, change the following system configuration setting to `OtoboDarkSkin`:
``` 
Loader::Agent::DefaultSelectedSkin
```

If you want to change the logo shown in the header of the agent interface, change the following system configuration setting:
```
AgentLogoCustom###OtoboDarkSkin
```

<h1 align=center>Discord Custom Gradient Names</h1>

## Importing
To import, add this **at the top** of your QuickCSS / CustomCSS
```css
@import url('https://discord-custom-gradient-names.github.io/gradient/main.css');
```
or go into your powercord themes folder and paste `git clone https://github.com/Discord-Custom-Gradient-Names/gradient.git`, and then refresh discord

*P.S.: theme devs, feel free to add this to your theme without consent. To do so, add the snippet above with your imports, also if you want to, you can send over a PR to add your theme to the (soon™) list of themes using Discord Custom Gradient Names*


## Attention all BetterDiscord Users!
If you are using BetterDiscord, you MUST have a plugin by DevilBro running, as we require his library for certain, but important data attributes (`user_by_bdfdb`).

## Adding your Custom Gradient Name to the Database
To add it, use [this generator](https://discord-custom-gradient-names.github.io/gradient/app/)(only works in chrome) and paste the result in the ``#gradient-name-requests`` channel in discord, or shoot us over a Pull Request with your Custom Gradient Name (must follow template below!) at the end of the [main.css](https://github.com/Discord-Custom-Gradient-Names/gradient/main.css) file. Rotation is optional, and defaults to left-to-right.

Template to follow for manual PR: 
```css
/*YOUR_USERNAME#YOUR_DISCRIMINATOR_TAG*/
[user_by_bdfdb*="YOUR_USER_ID_HERE"],
[data-user-id*="YOUR_USER_ID_HERE"],
[data-author-id*="YOUR_USER_ID_HERE"] {
  --name-dummy-transparent: transparent; --name-dummy-1: 1;
  --name-gradient: COLOR1, COLOR2;
  --name-gradient-angle: ROTATION;
}
```

## Support Server
[![Discord Server](https://discordapp.com/api/guilds/754130139415183401/widget.png?style=banner2)](https://discord.gg/Cka4prH)

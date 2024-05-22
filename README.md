# zeioth dotfiles config for hyprland
Clone the directory into `~/.config` and use it as base for your config. Or just for reference.

## FEATURES

 * Complex setup where most likely you will find the solution to most common issues you encounter while setting up hyprland.
 * Pre-binded modes to manage `screenshots` (local and/or to the cloud),
  `displays`, `move`, `resize`, `shutdown`.
 * Variables isolated from the rest of the config.
 * Feature rich. Delete what you don't need.

## YOU MUST

* Go to `./hardware.d/displays` and setup your displays there.

## YOU SHOULD

Read `hypr.config`. From there is quite easy to understand everything.

## COOL TO TWEAK (BUT NOT NECESSARY)

You can go into `./modes.d/displays` and modify the file to work as you desire. You will find examples about how to change the number of enabled monitors (very likely you just want to enable one while gaming)

# FAQ

* **How to debug**: On hyprland.conf, comment all lines except one. Then uncomment the next one. Until everything works.
* **Why not just have everything into just a single config file?** You certainly can.
    I prefer to separate it into files so it's easier to find the stuff.

# HOW TO USE MAN

`man ./help.man` for help about the config.

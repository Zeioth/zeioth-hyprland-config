# zeioth dotfiles config for hyprland
Clone the directory into `~/.config` and use it as base for your config. Or just for reference.

## FEATURES

 * pre-binded modes to manage `screenshots` (local and/or to the cloud),
  `displays`, `move`, `resize`, `shutdown`.
 * variables isolated from the rest of the config.
 * feature rich. Delete what you don't need.

## YOU MUST

* Go to `./aliases.d/01-system-aliases` and replace the display name with yours.
* Go to `./hardware.d/displays` and setup your displays there
  your displays there.

## YOU SHOULD

Read 'hypr.config'. From there is quite easy to understand everything.

## COOL TO TWEAK (BUT NOT NECESSARY)

You can go into `./modes.d/displays` and modify the file to work as you desire. You will find examples about how to:

  * Change resolutions on the fly
  * Change the number of enabled monitors (very likely you just want to enable one while playing)

# FAQ

* **How to debug**: On hyprland.conf, comment all lines except one. Then uncomment the next one. Until everything works.
* **Why not just have everything into just a single config file?** You certainly can.
    I prefer to separate it into files so it's easier to find the stuff.

# HOW TO USE MAN

`man ./help.man` for help about the config.
`man 5 hypr`     for a complete reference.

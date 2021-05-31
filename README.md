# linux-gaming-setup-scripts

A collection of scripts to help you install games on Linux, including recommendations for an optimal performance.

## How to setup

We highly recommend using a custom build of Wine through Wine-TKG, due to its performance improvements over the official version. You can follow a guide on how to setup
in their repository's *README* (https://github.com/Frogging-Family/wine-tkg-git).

Clone this repository and find out the game you want to install. Edit the `settings.properties` file according to your preferences then run the scripts in this order:
1. Go the game folder using the `cd` command.
1. Install the game using `./install` (for Genshin Impact, run `run_launcher` then install the game)
2. Apply the necessary patches to run the game in the smoothest way possible using `./apply_patches`
3. Run the game using `./launch`

## About piracy

We do not provide any downloads for pirated games. You can still use them using our scripts, but you are on your own to get them.

## Utility

### osu!

There is a script called `./create_link` that create a link to the osu! folder in your home directory called `.osu`. This is useful for skin and beatmap management in an easier way.

# scrotplus
Easy-to-use Linux Screenshotter

---

`scrotplus` is an easy to use and setup screenshotter for linux meant to replace the standard screenshot program that comes with your Desktop Environment such as [xfce4-screenshooter](https://git.xfce.org/apps/xfce4-screenshooter/).

## Installation

To install `scrotplus` clone the repo by doing:

`$ git clone https://github.com/numpadd/scrotplus/`

then move the `scrotplus` program to your `/usr/bin` directory or run the make file with

`$ make`

#### Advice

I would recommend assigning the program to a keybind so it's easier to use

## Usage

Just run it or bind it to a keybind and the cursor will change to a crosshair and you can select what you want to screenshot.

## Dependencies

* `maim` - after so much trouble i might've found the best linux screenshot tool
* `xclip`

### Note:
* It [doesn't](https://cdn.discordapp.com/attachments/515300853079474186/568473698034647041/unknown.png) work on *BSD, mainly due to xclip not working properly. (Apparently it does now and it's all just `xclip`'s fault.)

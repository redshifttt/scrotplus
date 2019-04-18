<h1 align="center">scrotplus</h1>
<p align="center">Easy-to-use Linux Screenshotter</p>

---

`scrotplus` is an easy to use and setup screenshotter for linux meant to replace the standard screenshot program that comes with your Desktop Environment such as [xfce4-screenshooter](https://git.xfce.org/apps/xfce4-screenshooter/).

# Installation

To install `scrotplus` clone the repo by doing:

`$ git clone https://github.com/numpadd/scrotplus/`

then by moving the `scrotplus` program to your `/usr/bin` directory. Alternatively you can also symlink the program by doing:

`$ sudo ln -s ~/path/to/scrotplus /usr/bin/scrotplus`

or you could just make it executable then and there:

`$ chmod +x scrotplus`

After that just restart bash by typing into your terminal:

`$ source ~/.bashrc`

or by just restarting your terminal emulator.

### Advice

I would recommend assigning the program to a keybind so it's easier to use

# Usage

The first time you run the program it will create a directory in your `/home` folder called `.scrots/` which is where it stores the scrots. It will then change your cursor into a crosshair from which you select the part of the screen you want to screenshot. It will then capture said section and store it in the `~/.scrots` folder with the date and time of capture (yyyy-mm-dd_H:M:S) that way it auto organises itself. Also after capture it automatically saves the image to your primary clipboard for easy sharing on things such as Discord etc.

# Dependencies

* `escrotum`
* `libnotify` (optional. If you don't want notifications you can just comment out the last line of the program.)
* `xclip`

### Note:
* It [doesn't](https://cdn.discordapp.com/attachments/515300853079474186/568473698034647041/unknown.png) work on *BSD. 

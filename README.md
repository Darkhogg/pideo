Pideo
=====

**Pideo** is a small interactive script I made that allows you to play videos
stored in external storage drives on your Raspberry Pi.

Usage
-----

To launch the script simply run `piplay` from a terminal.  A list will pop up
so you can select an available device.  The selected device will be mounted
and a similar menu will let you choose which file to play.

Currently avery file appears on the menus and there's no support for subtitles.


Installation
------------

If you are using Arch Linux ARM on you Raspberry Pi, you should install it using
the [`pideo` AUR package][pideo-aur].

  [pideo-aur]: https://aur.archlinux.org/packages/pideo/

In any other case, just copy the `pideo` file to `/usr/bin`.  The best way of
doing this is using the following commands:

```shell
git clone https://github.com/Darkhogg/pideo.git
sudo install -m755 pideo/pideo /usr/bin/pideo
```

[![Build Status](https://travis-ci.org/lubuntu-team/lubuntu-artwork.svg?branch=ubuntu%2Fcosmic)](https://travis-ci.org/lubuntu-team/lubuntu-artwork)
## Automatic build testing
Automatic build are on Travis : https://travis-ci.org/lubuntu-team/lubuntu-artwork


## Organisation of the source
==========================

This branch contains all the theme of Lubuntu. A prefix with 4 digits is used
to identify the release of each items, each current items which don't have
digits. After each release, all items are copied with the digits.

When it's possible, symlink are used to link current item, with the last one with a digit.
Example : 
For the logout banner, the default file is usr/share/lubuntu/images/logout-banner.png
but for 12.04 release, it's just a link to the file usr/share/lubuntu/images/1204-logout-banner.png



## Map of the source
=================

Icon theme (unique for all themes) : usr/share/icons/lubuntu
GTK & Openbox theme (Lubuntu-default is the current one) : usr/share/themes
Wallpapers (lubuntu-default-wallpaper is the current one) : usr/share/lubuntu/wallpapers
Logout banner (logout-banner.png is the current one) : usr/share/lubuntu/images
Menu button (lubuntu-logo.png is the current one) : usr/share/lubuntu/images
Lxpanel background (lubuntu-background.png is the current one) : usr/share/lxpanel/images
LXDM theme (Lubuntu is the current one) : usr/share/lxdm/themes



## How to propose changes
======================
1- Branch the main branch, by doing "git branch the_name_your_new_branch"
2- Do your modification, and commit by doing "git commit the_changed_file", and by writing a
message explaining your changes. 
3- If you need to add a new file, use "git add the_file" before "git commit"
4- You can make any numbers of commit you want. It's even better to have many
small commits, than one big commit
5- When it's finish, just push your branch anywhere on launchpad
(see https://help.launchpad.net/Code/UploadingABranch)

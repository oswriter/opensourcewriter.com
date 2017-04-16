+++
date = "2017-04-10"
title = "Budgie Screenshot Applet Brings Better UnixPorn"
description = "Take a shot of your desktop, a window, or region"
tags = ["Budgie Desktop"]
draft = "false"

+++

If you've read other posts on this blog--or visited any social media feed where someone is talking about desktop Linux--you recognize the importance of the screenshot. In addition to showing off your customized desktops--aka [UnixPorn](https://www.reddit.com/r/unixporn/), screenshots are useful when trying to explain how to execute a particular task or diagnose a problem.

## Full Control Over Your Screenshots

[Budgie](https://budgie-desktop.org/home/), the principal [Solus](https://solus-project.com) desktop environment, has its own native screenshot tool called, appropriately enough, [Budgie Screenshot Applet](https://github.com/cybre/budgie-screenshot-applet). It is available as a separate package in the Solus Software Center. Once installed, you can add the "Screenshot Widget" to your panel by using Raven, the Budgie sidebar configuration tool.

![Raven - Screenshot Widget](/images/2017-04-10-bsa-raven.png)

When you click the widget's icon, you are presented with three screenshot options: full-screen, current window, or selection. If you pick the latter, the mouse pointer turns to a cross-hair that lets you designate a rectangular area for the screenshot. By default the applet takes an immediate picture, but you can change this in the settings.

![Budgie Screenshot Applet - Main Menu](/images/2017-04-10-bsa-main-menu.png)

Indeed, the settings menu is quite comprehensive. You can create both "global" and "individual" settings for a number of items, including time delay (in seconds), whether to include the pointer, the folder to save images to, and even whether to automatically upload your images to a cloud service like [Imgur]. The individual settings let you set different time delays for different screenshot types--e.g., 5 seconds for windows and 10 seconds for selections--as well as designate which monitor to use for full-screen shots.

![Budgie Screenshot Applet - Global Settings](/images/2017-04-10-bsa-global.png)

There is also a recent screesnhot history that you can view directly in the applet. Within the history you can edit the title of the image, upload it to the cloud, or delete it. You can also clear the entire history and reset the global settings with a single click.

## Budgie Screenshot Applet for MATE?

Obviously, Budgie Screenshot Applet requires the Budgie Desktop, which is native to [Solus](https://git.solus-project.com/packages/screenshot-applet/). There is also a build for [Ubuntu Budgie](https://launchpad.net/~budgie-remix/+archive/ubuntu/ppa/+build/10711585). The developer of the Budgie Screenshot Applet is [Stefan Ric](https://github.com/cybre), who recently told me he is working on a port for the [MATE](http://mate-desktop.org/) desktop. Ric  has licensed the Budgie Screenshot Applet under the [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html). 

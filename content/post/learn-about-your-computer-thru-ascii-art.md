+++
date = "2017-05-01"
description = "Neofetch is highly customizable system info script"
tags = ["System Utilities"]
title = "Learn About Your Computer Thru ASCII Art"

+++

[Solus](https://solus-project.com) has a number of very simple tools that enhance your desktop computing experience. One of the best is [Neofetch](https://github.com/dylanaraps/neofetch), a program written in Bash, the basic command language interpreter used by all Linux-based operating systems. When you run Neofetch from inside a terminal, it displays two things: a list of basic information about your system, and a rendering of your operating system's logo in ASCII art, i.e. text characters.

![Neofetch readout for Solus sailboat](/images/2017-05-01-neofetch.png)

Obviously, I'm running Solus so Neofetch displays the classic sailboat logo. But you can actually tell Neofetch to display another Linux distribution's logo by adding a ``--ascii_distro 'Distribution'`` flag. For example, here's my Neofetch output with the [Xubuntu](https://xubuntu.org/) mouse logo:

![Neofetch readout with Xubuntu mouse](/images/2017-05-01-neofetch-xubuntu.png)

ASCII art aside, Neofetch is really about giving you a quick rundown of your computer's vital statistics. On the hardware side it tells you the computer's CPU and graphics card models, which can be useful when trying to diagnose a problem. It also displays software information such as the running version of the [Linux kernel](https://kernel.org) and the total number of packages installed.

Neofetch can be easily customized to provide additional information. In Solus the default configuration file is located at ``/etc/neofetch/config``. Many options can be altered directly from the command line using flags such as the one described above.

[Neofetch](https://git.solus-project.com/packages/neofetch/) is not just for Linux either. It works on any operating system that supports the Bash shell, including macOS, Android, BSD, and even Windows. The creator and lead developer is [Dylan Araps](https://github.com/dylanaraps). He's made Neofetch available under the [MIT License](https://opensource.org/licenses/MIT).

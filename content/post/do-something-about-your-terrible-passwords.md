+++
date = "2017-05-08"
description = "Pwgen creates passwords which can be easily memorized by a human."
tags = ["Security Applications"]
title = "Do Something About Your Terrible Passwords"

+++

People hate using strong passwords. I know plenty of professionals who use their children's names to secure computers containing valuable client data. Nobody likes dealing with passwords, but you have a responsibility to take "digital hygiene" seriously.

Personally, I use a simple tool called [pwgen](https://sourceforge.net/projects/pwgen/) whenever I need to create a new password. Pwgen is a command-line utility that basically spits out a list of "human readable" passwords. That is to say, they are easy to memorize relative to a truly random string of characters.

By default, pwgen produces a list of 160 possible passwords containing eight characters each using only letters and numbers. Here is an example from my terminal.

![Passwords! Semi-random passwords!](/images/2017-05-08-pwgen.png)

You can alter the output using a number of command-line options. For example, if you input ``pwgen -sy 12 1``, pwgen will produce a single, 12-character password that is completely random (`-s` stands for "secure") and contains at least one symbol (`-y`):

		oswriter@nwt ~ $ pwgen -sy 12 1
		2=+gyBvM^!nd 

Pwgen is written by [Theodore Ts'o](https://thunk.org/tytso/), who is also one of the oldest Linux kernel developers. He based pwgen on a prior program by Brandon S. Allbery. Pwgen is available for [Solus](https://git.solus-project.com/packages/pwgen/) and just about every other Linux distribution under the [GNU General Public License version 2](https://opensource.org/licenses/GPL-2.0).
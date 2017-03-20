+++
date = "2017-03-20"
title = "Learn About Horoscopes With OpenAstro.org"
description = "OpenAstro.org is full-featured, open source astrology software"
tags = ["Desktop Software"]

+++

These days, astrology is associated with badly written newspaper columns. But humans have studied the movement of planets and other celestial objects for thousands of years. Indeed, the development of the modern calendar is partly rooted in astrology.

[OpenAstro.org](http://www.openastro.org/?Home) is a [Python](https://www.python.org/)-based program for creating actual horoscopes, i.e. astrological charts. OpenAstro won't predict your future. But it's a surprisingly complex tool for learning more about contemporary western astrology.

## Charting the "Birth" of Linux

When you launch OpenAstro.org for the first time, it asks you to set a city and country as a home location. This is used to generate a "Here and Now" horoscope. Specifically, it displays a radix chart.

The radix consists of two circles. The outer circle displays the 12 signs of the *zodiac*, which you're probably familiar with if you've ever read a newspaper horoscope. In astrology, the zodiac illustrates the apparent yearly rotation of the sun around the Earth. Each sign represents a period of approximately one calendar month.

The inner circle displays the locations of the planets--which in astrology includes the sun and moon--relative to the earth. This circle is also subdivided into 12 unequal slices representing *houses*, which are based on the Earth's 24-hour rotation. According to [astrolibrary.org](https://astrolibrary.org/houses/),  the houses "are symbolic of the all the departments that make up human life."

The "Here and Now" chart is the default each time you run OpenAstro.org. But the most common analytical tool in astrology is a *natal chart*, which is the horoscope for the exact date and time of your birth. OpenAstro.org has a built-in database that lets you enter any number of dates. Of course, these do not have to be birthdays. In fact, astrolibrary.org explains that in ancient times, horoscopes were "cast for the time of certain events, such as wars, crownings, or festivals."

Along those lines, I created a radix chart for a critical event in modern technology history--[Linus Torvalds' email announcing his work on the original Linux kernel](https://groups.google.com/forum/#!msg/comp.os.minix/dlNtH7RRrGA/SwRavCzVE7gJ). This works nicely since there is an exact date, time, and place for this event: Torvalds sent the email from Helsinki, Finland, on August 25, 1991, at 8:57:08 PM GMT. 

![](/images/2017-03-20-openastro.png)

OpenAstro.org also lets you create other types of astrological charts, such as a *synastry*, which is basically one natal chart laid on top of another. This is used to determine a couple's "compatibility" with one another. Please note that OpenAstro.org does not help you interpret these charts, but astrolibrary.org has a decent crash course on the basics of understanding natal and synastry charts, as well as other astrological concepts.

## Where Can I Get OpenAstro.org?

Besides [Solus](https://git.solus-project.com/packages/openastro/commit/?id=300e59f55e12d6f99d8d4a8a08d62c84017e6cc7), OpenAstro.org is available for [Ubuntu 16.04](http://releases.ubuntu.com/16.04/) and earlier releases through a [personal package archive](http://openastro.org/?Ubuntu_Repository). The most recent release (v. 1.1.49) was on March 11, 2017. The creator and lead developer is [Pelle van der Scheer](https://launchpad.net/~pellesimon). He's licensed OpenAstro.org under the [GNU General Public License v. 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
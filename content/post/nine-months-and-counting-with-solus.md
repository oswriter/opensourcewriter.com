+++
date = "2017-07-29"
tags = ["Budgie Desktop", "Ikey", "Debian", "Ubuntu MATE", "BunsenLabs", "Martin Wimpress", "i3", "gtk", "Qt"]
categories = ["Editorials"]
title = "Nine Months and Counting With Solus"
description = "Solus ended my Linux distro-hopping, thanks in large part to lead developer Ikey Doherty's philosophy of aggressive pragmatism."
+++

According to my ``/var/log/eopkg.log`` file, I installed [Solus](https://solus-project.com/) on this computer--my main work machine--on October 19 of last year. After more than nine months in production, it's safe to say that I'm highly satisfied with how Solus has performed. Indeed, I have not given serious consideration to switching to another Linux distribution since I made the move to Solus.

Like many Linux users, my first distribution was Ubuntu, specifically the recently expired 12.04 LTS release. But within a few months I fell into the trap of "distrohopping"--trying virtually every Linux project for a few weeks, days, or even hours--hoping to find something better. While many Linux folks swear by distrhopping, I personally found it a miserable slog.

Eventually I settled on CrunchBang, a minimalist distribution based on [Debian](https://www.debian.org/). But the original developer discontinued the project--which was subsequently revived by the user community as [BunsenLabs](https://www.bunsenlabs.org/), now a fine distribution in its own right--so I went back to hopping for awhile.

### From Ubuntu MATE to Solus

That led me back to Ubuntu, more precisely [Ubuntu MATE](https://ubuntu-mate.org/), the derivative run by [Martin Wimpress](http://wimpress.org), whom I'd heard speak on a number of Linux podcasts (including the [Ubuntu Podcast](http://ubuntupodcast.org/) that he co-presents). There's a lot to be said for a charismatic project leader when you're trying to distinguish between hundreds of Linux distributions, and Wimpress' calm and friendly demeanor made for an easy sell.

I was perfectly pleased with Ubuntu MATE for many months, even as I later moved most of my daily workflow from the MATE desktop proper to the [i3 window manager](https://i3wm.org/). Unfortunately, following the Ubuntu 16.04 LTS release, I began to have problems with my wifi--i.e., it kept disconnecting at random intervals without explanation. To this day it's still a problem, as I learned when I tested Ubuntu MATE 17.04 on a used ThinkPad I recently acquired.

As I began experiencing Ubuntu problems, I started to hear more about Solus. [Ikey Doherty](https://plus.google.com/+IkeyDoherty), the Solus founder and project leader, was also a frequent guest on Linux podcasts. In particular, I remember listening to him on one podcast--which I shall not identify here--where the host was challenging him on his refusal to adopt a particular technology. Ikey held his ground politely but firmly and offered a fairly detailed, yet still comprehensible to laypersons like myself, explanation of why this particular technology was not appropriate for Solus.

Around this time, Solus also moved to expand its desktop offerings from Budgie alone to also include MATE and i3. Since the latter two were already part of my workflow, it made sense to at least give Solus a try as a replacement for Ubuntu MATE. And as I noted above, I haven't looked back since.

### Ikey's Aggressive Pragmatism

The first thing that Ikey's podcast exchange signaled to me was that this was a guy who cared deeply about process, i.e. how things were put together. In retrospect that should have been obvious, as he went to the trouble to build an entire Linux distribution "from scratch" without relying on an existing package management system. But it's easy to dismiss what Solus has accomplished as a project by pointing to useless metrics like the total number of packages available.

I would describe Ikey's approach to Solus as "aggressive pragmatism." His objectives are certainly aggressive, notably the [planned move from GTK to Qt for Budgie 11](https://budgie-desktop.org/2017/01/25/kicking-off-budgie-11/). Yet there's also the pragmatic side exhibited by the forthcoming Budgie 10.4 release that makes substantial user-experience improvements to the existing desktop.

You learn pretty quickly that everything Ikey does is for a good reason.
Part of his process is constantly re-evaluating his process to make sure that Solus isn't simply treading water. A good example of this was last year's move from a static point-release model to a rolling release. As [Ikey explained the decision](https://solus-project.com/2016/07/24/replacement-of-release-schedule/), "We’re really good at keeping things stable and really bad at not being a rolling release."

### The Unique Position of Solus

I recall being skeptical of the rolling-release move at first, based mostly on an earlier experience with Arch, which I tried in between my CrunchBang and Ubuntu MATE phases. Now, I have nothing but respect for Arch Linux, but as an intermediate-level user, it's daunting to face the prospect of the package manager having a meltdown every time you run an update. Fortunately, after nine months of running "rolling" Solus, I can't think of a single update that failed to install properly or break my machine.

Of course, the term "rolling release" itself is something of a misnomer. What we're really talking about is a single public distribution channel. This approach is hardly radical. Windows 10 basically operates this way at the consumer level. The only reason it seems problematic for Linux is that established distributions like Ubuntu and Debian maintain "long-term" release cycles, primarily to satisfy their server-based users. Since Solus isn't for servers, that's not an issue.

The truth is that if you're a desktop-specific distribution like Solus, there's no reason not to be a "rolling" release. After all, desktop hardware continues to advance and thus requires continuous adaptation. The fact that many other desktop-focused distributions are tied to long-term releases--and I won't name names--is really a testament to the work Ikey and the Solus team put into building their own infrastructure.

Solus is in a truly unique position: The only stable, integrated, and independent desktop Linux on the market today. And with [Ikey's recent transition to working full-time on Solus](https://solus-project.com/2017/06/13/we-are-growing/), I expect the project to enter a period of expanded growth and interest. Solus is no longer the "future of desktop Linux," as [I wrote on an earlier incarnation of this blog](https://web.archive.org/web/20161107215512/http://opensourcewriter.com/is-solus-the-future-of-desktop-linux/), but its living, breathing present.

+++
date = "2017-08-20"
tags = ["Solus", "Budgie Desktop", "Ikey", "elementary", "Ubuntu MATE", "Linux Mint", "Pantheon", "Cinnamon", "GNOME", "Snaps", "Flatpak", "GTK", "Qt"]
categories = ["Big Picture"]
title = "Solus 3 and the Road Ahead"
+++

August 15 marked the release of [Solus 3](https://solus-project.com/2017/08/15/solus-3-released/), which is so numbered because it is the "third iteration" of the Linux-based operating system since its move to a "rolling" release model in 2016. This release comes with the latest version of the [Budgie Desktop](https://budgie-desktop.org/2017/08/18/release-of-budgie-10-4/) (10.4) and also provides built-in support for [Snaps](https://snapcraft.io/docs/snaps/intro), the self-contained packaging format sponsored by Canonical Ltd., the parent company of [Ubuntu](https://www.ubuntu.com/). Solus 3 also represents a shift away from default installation of the long-term support branch of the [Linux kernel](https://www.kernel.org/) (4.9.x) to the latest stable release (4.12.8 as of this writing).

Both the Budgie 10.4 release and the support for Snaps represent a course correction from where Solus was heading just four months ago, when the project released what it then called a "snapshot" of its operating system. At that time, Solus planned to begin development of Budgie 11--replacing the GTK+ toolkit with Qt--and incorporate [Flatpak](http://flatpak.org/), a rival self-contained package distribution system to Snaps backed by Red Hat, Inc., as a means of providing third-party application support. Now, Flatpak has fallen somewhat out of favor with the Solus developers--project leader [Ikey Doherty said](https://dev.solus-project.com/T4235) it is "no longer the universal app solution we initially agreed to adopt, [but] rather, it is a *meta-distro*"--while Budgie 11 remains on the proverbial drawing board. And based on a recent [cryptic social media post](https://plus.google.com/u/1/+IkeyDoherty/posts/P5C3aQn37VS) by Ikey, he may be reconsidering the move to Qt as well.

### Solus and the Current Desktop Linux Market

That said, Solus clearly wants to move the Budgie Desktop past its GNOME roots. As Ikey's "meta-distro" remark not-so-subtly hinted, Flatpak has become a vessel for the GNOME developers to create an ecosystem where individual distributions cannot interfere with their work. And while Solus now has a GNOME-specific edition, it is clear there has not been the same degree of collaboration between those two projects as there has been with the developers of the MATE desktop, which has been available in Solus since last year.

Of course, the GNOME team is probably not that concerned with its growing estrangement from Solus. After all, Ubuntu recently abandoned its own GNOME-based Unity desktop in favor of resuming the use of "classic" GNOME as its default desktop environment, starting with the forthcoming 17.10 release. And as long as GNOME is backed by Red Hat, it's unlikely to be devoid of support or resources anytime soon.

On the flip side, Solus is hardly the first project to break away from the GNOME way of doing things. Ten years ago, GNOME was the major alternative to KDE on the Linux desktop. But following the first release of GNOME 3 in 2011--effectively a rebooting of the project--there has been a proliferation of alternative desktops, including MATE (the continuation of GNOME 2), Cinnamon, Pantheon, LxQT, Lumina, and of course, Budgie.

In a practical sense, these desktops are more alike than different. Indeed, Budgie, Cinnamon, MATE, and Pantheon are all presently GTK-based, and each relies, to varying degrees, on GNOME software. All four of these desktops are also the centerpieces of distributions that have emerged as serious competitors for what was Ubuntu's Unity edition: Solus for Budgie, Linux Mint for Cinnamon, Ubuntu MATE, and elementary OS for Pantheon.

What distinguishes Solus in that group is that it is the only non-Ubuntu derivative. Mint and elementary both track Ubuntu's long-term release cycle, while Ubuntu MATE is considered an "official" derivative by Canonical. Solus is independent and vertically integrated, meaning that its desktop environment, package management system, and development toolchain are wholly managed within the project. So while the Ubuntu derivatives have focused primarily on developing their own desktop applications, Solus has been occupied with building up its infrastructure

This does raise an obvious question: How will Solus handle desktop applications in Budgie 11? Mint and elementary have already expended significant effort on their own integrated applications, such as a default text editor and file manager, while Budgie 10.4 continues to rely on GNOME's work. That doesn't seem sustainable once Solus moves away from GTK.

### Solus Moving Forward as a Business

Another question arises from Ikey's decision to label this latest incarnation of Solus as a "release" rather than a "snapshot," and to assign it a clear version number, something that has not been done since [Solus 1.2.1](https://solus-project.com/2016/10/19/solus-1-2-1-shannon-released/) and the dawn of the Rolling Era last October. The Solus developers are famous for their refusal to give fixed release dates or even estimated times for completion. There has always been a "it's done when it's ready" mentality. But could that change following Solus 3?

After all, Solus is no longer a small upstart Linux distribution maintained by a single developer. It is a maturing project on the cusp of incorporation, as [Ikey himself announced in early August](https://www.patreon.com/posts/quick-update-13580753). He said the initial purpose for incorporating is to "provide future employment opportunities" for himself and the other developers--i.e, getting paid for their work--as well as to provide an "open and transparent legal entity to serve [] the users of and contributors to Solus."

The prospect of Solus as a business could prompt a rethinking of the "no release dates" policy. Consider that Canonical established its position within the desktop Linux market through a fixed, every-six-months release schedule. It is now synonymous with the Ubuntu brand.

And branding is a major concern for any business regardless of size. Branding is not simply plastering your logo on everything; it is establishing consistent expectations for users. And as Solus continues to gain users--and even new developers--there will be likely be increasing pressure on Ikey and the development team to establish a higher degree of certainty with respect to things like updates and releases than there is at present.

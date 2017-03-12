+++
date = "2017-03-06"
title = "Improve Your Blogging with Ghostwriter"
description = "Ghostwriter is a Qt-based Markdown editor"
tags = ["Text Editors"]

+++

I'm a professional blogger. I'm paid to write between 10 and 20 posts for clients each week. This means I spend a lot of time working in a text editor--which, since I started using [Solus](https://solus-project.com), is [Ghostwriter](https://wereturtle.github.io/ghostwriter/).

## Working With Markdown

For many years I used [LibreOffice Writer](https://www.libreoffice.org/discover/writer/) to draft my blog posts. But you don't really need a full-service word processor for blogging. There are basically two things I need: support for [Markdown](https://daringfireball.net/projects/markdown/syntax) and a running display of the current word count.

The latter is important because, in my work, I'm usually commissioned to write a post containing a certain number of words. So it's helpful to know as you're writing how much further I have to go. As for Markdown, it's my preferred method for drafting any web content. Markdown lets you write files in plain text using specific syntax to indicate headers, formatting, links, and so forth. 

For example, here is how I typed the headline and first paragraph of this section in Ghostwriter using Markdown:

	## Working With Markdown
	
	For many years I used [LibreOffice Writer](https://www.libreoffice.org/discover/writer/) to draft my blog posts. But you don't really need a full-service word processor for blogging. There are basically two things I need: support for [Markdown](https://daringfireball.net/projects/markdown/syntax) and a running display of the current word count.
	
Many Linux text editors, such as [Atom](https://atom.io/) and [gedit](https://wiki.gnome.org/Apps/Gedit), support Markdown syntax natively. But Ghostwriter is a Markdown-specific editor and offers a live, see-it-as-you-go preview of the finished HTML.

![](/images/2017-03-03-ghostwriter.png)

By default Ghostwriter formats its live preview in the style used by [Github](https://github.com/), but you can import the custom style sheet (CSS) from your own blog or website to get a more accurate rendering. You can also copy or export the converted HTML code if your blog platform does not accept Markdown directly, although many do, including [Ghost](https://ghost.org/) and [Hugo](https://gohugo.io/) (which this site uses).

Markdown advertises itself as a "distraction-free" editor. You can run it full-screen with plenty of white-space around your text. There is also a "Hemingway" setting that prevents you from using the backspace key--so you're forced to keep writing and not constantly correct yourself as you type.

Despite the uncluttered interface, Ghostwriter comes with a full set of features, including live spellcheck, automatic saving and backups, and a number of heads-up displays (HUDs) to provide document information and navigation. There is also a handy reference guide to bring you up to speed on Markdown syntax.

## Where Can I Get Ghostwriter?

Aside from [Solus](https://git.solus-project.com/packages/ghostwriter/), Ghostwriter is also available prepackaged for Windows and Ubuntu-based Linux distributions. The lead developer goes by the Github username [wereturtle](https://github.com/wereturtle), and he's licensed the [Ghostwriter source code](https://github.com/wereturtle/ghostwriter) under the [GNU General Public License v. 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). Please note that if you compile Ghostwriter from source, there are a number of [Qt 5.x](https://doc.qt.io/qt-5/index.html) packages that need to be installed first.
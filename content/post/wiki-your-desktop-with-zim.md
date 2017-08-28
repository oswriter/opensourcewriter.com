+++
date = "2017-04-24"
title = "Wiki Your Desktop With Zim"
description = "Zim is a graphical text editor used to maintain a collection of wiki pages."
categories = ["Reviews"]
tags = ["Zim", "Jaap Karssenberg"]

+++

Leading up to (and after) the release of the new [Solus snapshots](https://opensourcewriter.com/post/download-the-latest-solus-snapshots-now/) last week, there were complaints from some quarters of the Linux media that Solus was still "not ready" because it lacked sufficient software packages to satisfy user demand. According to this worldview, if even one user might find a program useful, Solus has an obligation to include it in its repositories. To these folks, a good Linux operating system is like a 24-hour diner where you have to keep hundreds of dishes on the menu at all times, regardless of quality or the amount of kitchen staff.

This diner mentality can be summed up, "Solus doesn't have one obscure package I like to use, so it must not be a complete operating system." I know I had this attitude at one point. I held off transitioning to Solus for months because I was using two packages in my daily workflow that were not available in Solus. And I knew one of those packages would never fit into Solus because of certain technical issues.

## Plain Text in a Simple Graphical Interface

So when I finally moved to Solus, I had to change my workflow and look for a new tool that met my needs. In this case, I wanted a simple program to manage my professional writing schedule. I'm not talking about a calendar, since I don't deal with hourly appointments. Rather, I was looking for a digital notebook to organize and store to-do lists and other data (images, web links, et al.) related to my weekly assignments.

The search ultimately led me to [Zim](http://zim-wiki.org/), a desktop wiki editor, which has turned out to be much better for my workflow than what I used before. Zim provides a simple graphical interface to create individual wiki-style pages. All you do is type and format your text in a WYSIWYG window. You do not need to know any special formatting. Of particular use to me is Zim's built-in support for checkbox lists, which are obviously handy when tracking weekly tasks.

![A screenshot within a screenshot!](/images/2017-04-23-zim-alt.png)

Zim automatically saves everything you type in plain-text files with wiki formatting. You can also insert and resize images directly into the files. Zim organizes everything in a single "notebook" folder, which allows you to group individual pages within subfolders. Here is an illustration of how my Zim notebook looks as a tree:

    .
    ├── Home
    │   ├── Archive
    │   │   ├── Week_of_April_14.txt
    │   │   └── Week_of_April_21.txt
    │   └── Archive.txt
    ├── Home.txt
    ├── LBW
    │   ├── Week_of_April_28.txt
    │   ├── Week_of_May_12.txt
    │   ├── Week_of_May_19.txt
    │   └── Week_of_May_5.txt
    ├── LBW.txt
    ├── notebook.zim
    ├── Open_Source_Writer
    │   └── compass.png
    ├── Open_Source_Writer.txt
    └── .zim

Since Zim uses wiki formatting, you can insert and use navigational links within the notebook. If you click on a link to a page that does not already exist, Zim creates it automatically. Zim also has a number of plugins that add functions such as a daily journal, a table of contents, and support for mathematical expressions.

## Learn More About Zim

In addition to [Solus](https://git.solus-project.com/packages/zim/), Zim is available for Ubuntu and most other major Linux distributions, as well as Windows and FreeBSD. The lead developer is [Jaap Karssenberg](https://launchpad.net/~jaap.karssenberg). He's licensed Zim under the [GNU General Public License version 2](https://opensource.org/licenses/GPL-2.0) or greater.

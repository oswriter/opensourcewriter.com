+++
categories = ["Reviews"]
tags = ["Newsbeuter", "Andreas Krennmair"]
date = "2017-03-27"
title = "Take Back Your Web Reading With Newsbeuter"
description = "Newsbeuter is a terminal-based RSS reader."

+++

Before social media made everyone's friends, interests, and "likes" a matter of public record, [RSS](http://www.rssboard.org/) enabled individuals to gather content from around the web in a simple (and private) manner. Although RSS is not as visible as it once was--consider [Google's decision to kill Google Reader in 2013](https://googleblog.blogspot.com/2013/03/a-second-spring-of-cleaning.html)--there are still many actively developed applications that gather and organize RSS feeds. My personal favorite is a console-based utility called [Newsbeuter](http://newsbeuter.org/).

## As Simple as Making a List

Newsbeuter reads a list of RSS-feed URLs that you provide and displays the contents in a Linux terminal. The first time you run Newsbeuter, you will likely see an error message, since there is no list created during installation. You can import an existing list--in the form of an OPML file--or simply create one by opening a text editor and saving the finished list at ``~/.newsbeuter/urls``.

Newsbeuter lets you categorize feeds using tags appended to the end of the URL. For example, I categorize my feeds based on *law*, *linux*, and *podcasts*. Here's a selection from my ``urls`` file:

		http://feeds.feedburner.com/tncourts/opinions law
		https://charlottesville29.com/feed/
		http://www.scotusblog.com/feed/ law
		http://www.datamation.com/rss.xml linux
		http://smlr.us/?feed=rss linux podcast
		http://missionlog.libsyn.com/rss podcast
		http://distrowatch.com/news/dw.xml linux

As you can see, Newsbeuter supports multiple tags per entry. I tagged the [Sunday Morning Linux Review](http://smlr.us) feed, with both *linux* and *podcast*, since it's [both a floor wax **and** a dessert topping](https://www.youtube.com/watch?v=wPO8PqHGWFU). Once in the Newsbeuter console, you can toggle a list of categories/tags by pressing 't'.

By default, Newsbeuter displays a numbered list of feeds in the order specified in your ``urls`` file. You can highlight an individual feed and press 'r' to update it; pressing a capital 'R' updates all feeds at once. There is a wide range of keyboard commands and configuration options built-in to Newsbeuter, which you can learn about through the project's [comprehensive documentation](http://newsbeuter.org/doc/newsbeuter.html).

## Your Own Web Content Database

RSS feeds are not just for blogs. I use Newsbeuter to keep track of podcasts, [Reddit](https://reddit.com) posts, and updates to software packages. In my [legal writing](https://skipoliva.com) work, I even use Newsbeuter to get the latest court decisions, such as [this feed](http://feeds.feedburner.com/tncourts/opinions) from the Tennessee Administrative Office of the Courts:

![](/images/2017-03-27-newsbeuter.png)

Newsbeuter stores all the content it downloads in an [SQLite](https://www.sqlite.org/) database located at ``~/.newsbeuter/cache.db``. This makes it handy to backup or move your Newsbeuter setup to another machine. But one thing I've noticed: the longer you use Newsbeuter, the longer it takes to start, which I assume is related to the increased size of the database.

## Learn More About Newsbeuter

Newsbeuter is packaged for [Solus](https://git.solus-project.com/packages/newsbeuter) and most major Linux and BSD distributions. The creator and lead developer is [Andreas Krennmair](https://github.com/akrennmair). He's licensed Newsbeuter under the [MIT License](https://opensource.org/licenses/MIT).

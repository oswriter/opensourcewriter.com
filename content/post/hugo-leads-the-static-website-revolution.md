+++
title = "Hugo Leads the Static Web Revolution"
tags = ["Programming"]
description = "Hugo is a fast and modern static website engine built in GoLang"
date = "2017-03-13"

+++

The first time I created a website, back in the mid-1990s, it required manually coding HTML. This later gave way to specialized HTML editors such as the now-defunct Microsoft FrontPage. By the mid-2000s, I used [WordPress](https://wordpress.org/) to create blogs. Indeed, just about every blog that I ghostwrite for professionally uses WordPress.

WordPress is a dynamic content generator. This means it accesses a database to create a page every time a user visits the website. It's not a bad system, but it can be slow and insecure. After all, an attacker can not only compromise your web server, but also the database or any outside plugins installed on top of WordPress.

## Building a Blog From the Terminal

For this (among other reasons) I've moved to [Hugo](https://gohugo.io/), a static content generator, for creating this blog and [my professional website](https://skipoliva.com). Fortunately the [Solus](https://solus-project.com/) developers think along the same lines, as they recently moved their own public website to Hugo.
A "static" content generator is just what it sounds like. You generate the content once on your local computer and then upload it to your web server. There are no databases or other special software requirements. I maintain this blog on a [DigitalOcean](https://www.digitalocean.com/) server running [Apache](https://httpd.apache.org/download.cgi) and that's it.

Hugo is a command-line utility. For example, to create this site I opened a terminal and entered `hugo new site opensourcewriter.com`. This created a new directory with the basic skeleton for the website. (To see how a Hugo directory looks for a live website, visit [my Github repository](https://github.com/oswriter/opensourcewriter.com) for this blog.) Hugo does not come with a default theme or template. I don't know much about CSS or layouts so I downloaded a preexisting theme called [Cactus](https://github.com/digitalcraftsman/hugo-cactus-theme) from [Hugo's library](http://themes.gohugo.io/) and modified it to my needs.

Hugo recognizes [Markdown syntax](https://daringfireball.net/projects/markdown/syntax) natively, which is handy since I already [write my blog posts](https://opensourcewriter.com/post/improve-your-blogging-with-ghostwriter/) using Markdown. Hugo also has a built-in web server that lets you see a "live" rendering of your website as you build it. To enable this feature you enter `hugo serve` from the terminal and point your web browser to `localhost:1313`.

![](/images/2017-03-13-hugo.png)

When your site is ready, enter `hugo` without any additional arguments. This generates the static website in a separate `/public` directory, which you can then upload to your server. What I like about this setup is I don't need to worry about losing my website. If something goes wrong with the web server, I can easily regenerate the site from its source files and upload to it to a new host in less than two minutes.

## Need More Information About Hugo?

Hugo is available for multiple platforms, including Solus and most popular Linux distributions, as well as FreeBSD, Windows, and macOS. The creator and lead developer is [Steve Francia](https://github.com/spf13). He's licensed Hugo under the [Apache License v. 2.0](https://github.com/spf13/hugo/blob/master/LICENSE.md). 
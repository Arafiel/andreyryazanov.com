---
layout: blog_item
title: "Creating Static Sites with Jekyll"
author: Andrey
headerImage: jekyll.jpg
tags: [jekyll, static site, angularJS]
permalink: "blog/:title"
---

I went to a meetup called {{static is}} the new dynamic recently hosted at  [WorkMarket](https://www.workmarket.com "WorkMarket") in NYC this past week which has inspired me to learn more about static website generators as alternatives to standard CMS.  The two in particular which caught my eye were [Hugo](https://gohugo.io/ "Hugo") and [Jekyll](http://jekyllrb.com "Jekyll").  If I’d gone to this meetup a week or two earlier, chances are I would have gone with the newer option offered by Hugo based on the fact that it’s a more recent addition to the ecosystem and because it’s written in Go rather than Jekyll’s Ruby (which I don’t particularly like dealing with).

That said, I’ve chosen to go with Jekyll because they recently released a much-upgraded version in the form of Jekyll 3.0, combined with the fact that it is generally much more supported by services such as [Cloud Cannon](http://cloudcannon.com "Cloud Cannon") and the US Government’s own [Federalist](https://federalist.18f.gov "Federalist").

<h3>Why Static?</h3>
As I learned while building this website the last time around, even a minor amount of traffic tends to tax shared servers when you’re running a dynamic website.  This particular website was previously created using a mix of PHP, MySQL, and AngularJS.  The Angular worked great…but half the time posts still took forever to load because my hosting provider (Dreamhost) took forever to return the blog content from the MySQL database.  Also, I'd lately been getting timeout errors trying to get the website to load at all, so figured it was time to change hosting and methodology.

<h3>What is Jekyll?</h3>
Jekyll is a static site generator which allows you to have much the same functionality as a standard CMS, but doing the page generation during the build process rather than dynamically generating pages as a user visits them.  The end result (theoretically) is that you could run even a high-traffic site on a very crappy server (think Raspberry Pi).  Whether that’s the case or not…I’m planning on finding out in the near future.

<h3>What am I Doing?</h3>
Recreating my personal website and blog using Jekyll & Git Pages without using a real hosting provider.  How’s that going to work out and am I going to need to get it properly hosted either on my current Dreamhost or in an EC3 instance on Amazon…I don’t know, but I intend to find out.

<h3>Where is the progress going?</h3>
As I said, I’m just starting, but you can follow my progress on github here:
[https://github.com/Arafiel/andreyryazanov.com](https://github.com/Arafiel/andreyryazanov.com "Andrey Ryazanov Repo") or on the actual resulting website at [https://www.andreyryazanov.com](https://www.andreyryazanov.com "Andrey Ryazanov").

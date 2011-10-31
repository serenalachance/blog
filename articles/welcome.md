Hello, and let me be the first to welcome you to the launch of **serenalachance.org** (and also available at the somewhat shorter **serena.la**)! One of the main reasons that I've put this site together is that when I get dressed up as Serena, the first and foremost thing I feel like doing is writing, and so I thought one day, why not a blog!

For the most part I'll try not to fall into the trap of writing about just myself (you know, like some other blogs: I went to the club, I biked to the store, I'm at cocktail hour, ...), but at the same time, part of this blog's purpose will be to act as a journal for Serena's progression over the years.

Roadmap
-------

That's not to say that I'm happy with leaving this site just a blog either. With the exception of some nice activity on Facebook and Flickr, it seems to me that there's room in the online trannysphere for a nice community outside of what the other types of transgendered groups have built for themselves (not that these are bad; just that they generally cover different topics than trannies like to chat about). Of course, this is just an idea that I've played with, and isn't really solidified yet.

Expect new developments here to be part of one of two categories:

* **Discussion and community**: getting the community engaged in something other than commenting on each other's (admittedly hot) Flickr photos!
* **Experiments**: various social API mashups with a particular focus on fun things (and girls, that includes us).

Expect blog posts to cover mostly hot traps and big heels :)

Technical
---------

Now for the technical portion of this article (feel free to skip). The site's backend is written in [Rails](http://rubyonrails.org/) behind [Nginx](http://nginx.org/) and [Phusion Passenger](http://www.modrails.com/). It currently runs an [SQLite](http://www.sqlite.org/) database, but uses full page caching to ensure massive throughput. Articles are stored to the database, but are read in using a manually-triggered task so that I can write them in [Vim](http://www.vim.org/) and revision them with [Git](http://git-scm.com/). The whole package runs on a 512 MB Linode VPS imaged with [Archlinux](http://www.archlinux.org/).

Enjoy! [&mdash; Serena](mailto:s@serenalachance.org)

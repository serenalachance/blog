I just pushed a small layout and backend update to [serenalachance.org](//serenalachance.org) mostly aimed at making updating this site easier and therefore lessening the disincentive for me to update it.

A few notes on the backend changes:

  * [pjax](https://github.com/defunkt/jquery-pjax) provides fast transitions between any pages on the site using `pushState`. It also degrades gracefully for the less technically inclined.
  * [AWS Cloudfront](http://aws.amazon.com/cloudfront/)! Images on the site should load blazingly fast no matter where you are in the world.
  * Article masters were always managed in Git, but they previously needed to be loaded from the local file system with a Rake task. Unfortunately, Rake is slow, and with my Internet era attention span just updating articles was distracting. Articles are now pushed to a simple API via Curl, and it's _fast_.
  * Caching is now achieved via Memcache rather than static HTML. Don't worry, it's still pretty quick.

The frontend has also changed a little bit:

  * [Columnal](http://www.columnal.com/) now handles my positioning. It's a responsive grid system that is easy to work with and looks great on all screens. Also, I just hate positioning things myself.
  * Hyphentation is now handled by the CSS3 property rather than an ugly JavaScript bundle.
  * Body is now left aligned rather than centered because eventually I'll be moving in the direction of better usage of screen real estate. This leaves room for a fully fluid layout (even if it only appears on some pages).
  * Link colors should be a little more consistent so it's obvious what is clickable and what isn't. This goal wasn't achieved 100%, but it's better than it used to be.
  * Tried to make white space (or black space in this case) everywhere a little more consistent. This goal also is still a bit of a work in progress.

Now that wasn't so bad was it? Point form lists are great. Now lets try to get back to the content people actually care about.

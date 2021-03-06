Whisky Oriented Development
========

This is the basic website for the Whisky Oriented Development group. I encourage everyone to change this as needed.

---

### Add yourself to the members listing

You can add yourself to the members page (and are encouraged to do so), by forking this repo, adding a new markdown
page for yourself (use jamie-starke.md as an example), and then creating a pull request.

### Get started

If you want to run this on your local machine to test things out before you commit them, the steps are:

1. [Fork the repository](https://github.com/WhiskyDev/whiskydev.github.io/fork).
2. Clone the repository to your computer.<br /> `git clone https://github.com/username/whiskydev.github.io`
3. `bundle install`
4. **Using older versions of Jekyll**<br />
  Build and run jekyll using `jekyll --server --auto`.<br />
  **Using [Jekyll 1.0](http://blog.parkermoore.de/2013/05/06/jekyll-1-dot-0-released/)**<br />
  Build Jekyll using `jekyll build`.<br />
  Then run Jekyll using `jekyll serve --watch`, go to http://localhost:4000 for your site.

---

### Make it yours

1. Much of the configurable site information is stored in `_config.yml`, you should be able to set up almost everything from it.
2. Change about.md for the basic site information.
3. For domain settings, see [the guide from GitHub](https://help.github.com/articles/setting-up-a-custom-domain-with-pages).
4. New posts can be added 

---

### GitHub Pages stuff

The `gh-pages` branch of this repository is [the project page](http://scribble.muan.co), which **should not** be used as your blog, so use `master` branch for your blog. This is assuming your blog repository will be called [your-username].github.io, if tis is not the case, you will need to delete the `gh-pages` repository and create a branch off the `master` branch. Hope that's clear.

---

### Options

When writing a post, there are 3 options you can add to the header.

1. **disqus: y**<br />
  If disqus is set to 'y', at the end of the post there will be a disqus thread, just like this one. To use disqus, you MUST [set up your own disqus account](http://disqus.com/).

2. **share: y**<br />
  An option for showing tweet and like button under a post.

3. **date**: 2013-05-06 18:07:17<br />
  Date is not a required header since Jekyll reads the file name for date, this was added in only for the **signoff time**. (as shown at the end of this post) If you don't want the signoff time, go into `/includes/signoff.html` remove the `<span>`, and remove `{% include signoff.html %}` from `/layouts/post.html`.

---

### Theme

Scribble: A jekyll theme. [Want a demo? click and read instruction. :point_left:](http://scribble.muan.co/2013/05/06/scribble-the-jekyll-theme/)
<br />
[More themes](https://github.com/muan/muan.github.com/releases).

![screenshot](http://scribble.muan.co/images/screenshot.png)

There is no clever design philosophy to talk about, I tried to find something to work with, and 'scribble' came to my mind. 

This theme uses Open Sans powered by Google Web Fonts, and was written in plain HTML, SCSS & CoffeeScript, though .scss & .coffee files wouldn't be included in the theme. 

The theme is mobile optimised but I did not check browser compatibility. It looks great in Chrome, Safari and Firefox though.

### The end

Like it? [Tell me](http://twitter.com/muanchiou).<br/>
Question? [Use GitHub Issues](https://github.com/muan/scribble/issues).

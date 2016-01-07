<<<<<<< HEAD
# Fengzhichu Theme

A jekyll theme for personal blog which based on [Type theme](https://github.com/rohanchandra/type-theme) and [ibireme's blog](http://blog.ibireme.com). Add several useful features. Fengzhichu Theme is powered by [Jekyll](http://jekyllrb.com/) and freely
hosted in [Github pages](https://pages.github.com/).

## Check the live demo

[Fengzhichu Theme Live Demo](https://fengzhichu.com)

## Screenshots
![Home page](img/Screenshot1.png)
![Pst page](img/Screenshot2.png)
![Archive page](img/Screenshot3.png)
![Category page](img/Screenshot4.png)
![About page](img/Screenshot5.png)

## How to use it
* Star & Fork the [repo](https://github.com/fengzhichu/fengzhichu-theme).
* Rename repo as 'yourusername.github.io'.
* You can delete gh-pages branch if you want.
* Clone your <b>master branch</b> to local directory.
* Custom the '_config.yml' to your style.
* Install jekyll can refer 'ruby_install_by_rvm.sh', modify to suit your need.
* Run jekyll serve -w.

## Customization

###_config.yml
Some important configurations.
* imageurl: Randomly change image which display on top of site.
  * By default image changes everytime when open your site or reflash it. If you want to change image daily or weekly, just append '/daily' or 'weekly' to imageurl.
* title: Display on browse tab.
* hometitle: The first menu name of navigation bar.
* yoursitetitle: Your LOGO place here.
* visiblewords: Number of words which you want to display in post of homepage.
* sechby:
  * category: "Posted in" #Words before Category name.
  * tag: "with" #Words before Tag name.
  * example: Posted in 'Category name' with 'Tag name'.

###Tags
Add new tag.
* Annotate your post entry front-matter block as usual:
```yml
---
layout: post
title: How To Use Tags And Categories On GitHub Pages Without Plugins
category: programming
tags: [github, github-pages, jekyll]
---
```
* Add an entry in your _data/tags.yml for every tag.
```yml
- slug: github-pages
  name: GitHub Pages
```
* Create a .md file which name is your Tag slug for every tag.
```yml
---
layout: blog_by_tag
tag: github-pages
permalink: /blog/tag/github-pages/
---
  ```

###Categories
Similar as Tags.

## Thanks
* Theme template: [type-theme](https://github.com/rohanchandra/type-theme)
* Navigation bar: [ibireme's blog](http://blog.ibireme.com)
* Features of Tag and Category: [HOW TO USE TAGS AND CATEGORIES ON GITHUB PAGES WITHOUT PLUGINS](http://www.minddust.com/post/tags-and-categories-on-github-pages/)

## Enjoy
- If you like, please star it. Thank you!
- Enjoy it!

## Copyright & License
Copyright (C) 2015 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 
=======
Scribble
========

A jekyll theme. [Want a demo? click and read instruction. :point_left:](http://scribble.muan.co/2013/05/06/scribble-the-jekyll-theme/)
<br />
[More themes](https://github.com/muan/muan.github.com/releases).

![screenshot](http://scribble.muan.co/images/screenshot.png)

There is no clever design philosophy to talk about, I tried to find something to work with, and 'scribble' came to my mind. 

This theme uses Open Sans powered by Google Web Fonts, and was written in plain HTML, SCSS & CoffeeScript, though .scss & .coffee files wouldn't be included in the theme. 

The theme is mobile optimised but I did not check browser compatibility. It looks great in Chrome, Safari and Firefox though.

---

### Get started

1. [Fork the repository](https://github.com/muan/scribble/fork).
2. Clone the repository to your computer.<br /> `git clone https://github.com/username/scribble`
3. `bundle install`
4. **Using older versions of Jekyll**<br />
  Build and run jekyll using `jekyll --server --auto`.<br />
  **Using [Jekyll 1.0](http://blog.parkermoore.de/2013/05/06/jekyll-1-dot-0-released/)**<br />
  Build Jekyll using `jekyll build`.<br />
  Then run Jekyll using `jekyll serve --watch`, go to http://localhost:4000 for your site.

---

### Make it yours

1. I have extract most user specific information to `_config.yml`, you should be able to set up almost everything from it.
2. Change about.md for blog intro.
3. For domain settings, see [the guide from GitHub](https://help.github.com/articles/setting-up-a-custom-domain-with-pages).

---

### GitHub Pages stuff

The `gh-pages` branch of this repository is [the project page](http://scribble.muan.co), which **should not** be used as your blog, so use `master` branch for your blog. This is assuming your blog repository will be called [your-username].github.io, if this is not the case, you will need to delete the `gh-pages` repository and create a branch off the `master` branch. Hope that's clear.

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

### The end

Like it? [Tell me](http://twitter.com/muanchiou).<br/>
Question? [Use GitHub Issues](https://github.com/muan/scribble/issues).
>>>>>>> d60260b49b00f6662144f5ca5d05c4def5ce5248

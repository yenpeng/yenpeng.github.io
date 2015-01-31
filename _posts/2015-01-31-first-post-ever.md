---
layout: post
title: "Hello, World"
quote: Herein marks the birth of a new log for aspirations.
image: /media/2015-01-31-first-post-ever/cover.jpg
video: false
---

#This is the ice-breaking post


Welcome to the <em>#firstpostever</em>, the pioneer to all the posts that would succeed this from here onwards. 



This is basically a pet project kickstarted at a whim of curiosity, quickly turning into an odd burgeoning labour of love as I wade through the learning curve of setting up and editing my own website.



I am a finance and accounting person with zero knowledge in IT and coding, trying my hand at something completely new to me. Whilst I had some prior experience dabbling in HTML during my active blogging years, the highly assistive interface in Blogspot does not come close to the nitty gritty of editing layouts and content in an **actual** text editor.



Jekyll, Markdown, _more advanced_ HTML... all Greek to me now, but with a dose of persistence I am sure they will too, become mother tongue  eventually.



It has been a confusing and rewarding process thus far, and I am far from done. This baby's gonna need a lot of TLC, and I am taking my time (sweet long hours into the night!) in knocking things into shape, one commit at a time. With of course, a stash of code cheat sheets by the side and caffeine.



{% include image.html url="/media/2015-01-31-first-post-ever/teachme.jpg" width="100%" description="That's right." %}


## Usage

### Main variables

The global variables are set on the `_config.yml` file.

To start, you need to change at least the variable `url` on the file.

#### Social links

To add a social link you just need to add the following code inside the variable `social`:

```
  - icon:	[the genericon name for the social network]
    url:	[the url to follow]
    desc:	[a small description for the link (e.g. "Follow me on twitter")]
```

#### Menu

To add a menu item you just need to add the following code inside the variable `menu`:

```
  - title:	[title of the menu item]
    url:	[the url to follow]
```

#### Others

You'll find a lot of other variables inside the file, e.g.:

- the site `title`, `description`, `icon` and default `cover` image.
- text of the `copyright` message.
- the number of posts per page (`paginate`).
- the `permalink`'s structure (see [the docs](http://jekyllrb.com/docs/pagination/)).


### Default YAML tags

- `layout:`<i>`post, page`</i> `or `<i>`fullscreen`</i>: defines the layout of the page.
- `title: [string]`: title of the post.
- `quote: [string]`: a small description of the post to be shown above the title.
- `dark:`<i>`true`</i> `or `<i>`false`</i>: use black font (instead of white) for the header (default value is false).
- `image: [url] or `<i>`false`</i>: a cover image for the post (default value is _false_).
- `video:`<i>`true`</i> `or `<i>`false`</i>: add a cover video for the post (default value is _false_).
- `video_mp4: [url]`: the URL for the mp4 video.
- `video_webm: [url]`: the URL for the webm video.
- `video_ogv: [url]`: the URL for the ogv video.

## Versions

Here is a `<table>` with all Thinny's versions:
<table>
  <thead>
    <tr>
      <th>Version</th>
      <th>Codename</th>
      <th>Platform</th>
      <th>Release date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>[0.3](https://github.com/camporez/Thinny/releases/tag/v0.3-alexandra)</td>
      <td>[Alexandra](http://nikita2010.wikia.com/wiki/Alexandra_Udinov)</td>
      <td>Ghost 0.3.x</td>
      <td>November 2013</td>
    </tr>
    <tr>
      <td>[2.0](https://github.com/camporez/Thinny/releases/tag/v2.0-bianca)</td>
      <td>[Bianca](http://memoriaglobo.globo.com/programas/entretenimento/novelas/caras-bocas/caras-bocas-bianca-isabelle-drummond.htm)</td>
      <td>Jekyll</td>
      <td>January 2014</td>
    </tr>
    <tr>
      <td>[2.1](https://github.com/camporez/Thinny/releases/tag/v2.1-cosette)</td>
      <td>[Cosette](http://lesmiserables.wikia.com/wiki/Cosette)</td>
      <td>Jekyll</td>
      <td>March 2014</td>
    </tr>
    <tr>
      <td>2.2</td>
      <td>[Dolores](http://en.wikipedia.org/wiki/Dolores_Haze)</td>
      <td>Jekyll</td>
      <td><i>Soon (see the [issues list](https://github.com/camporez/camporez.github.io/issues?milestone=3))</i></td>
    </tr>
  </tbody>
</table>

-----

## And lastly...

> This is still a premature baby.

I have yet to decide on the direction of this website. 
At the moment I am still focusing on learning up the tricks and tools in modifying the base template and putting up minor pieces of content.



{% include image.html url="/media/2015-01-31-first-post-ever/babysteps.jpg" width="100%" description="Little steps, is all I'm saying. Check back for more updates." %}




# H3xl00m-blog

A theme for Jekyll to build a personal blog, based on [Bootstrap 3](http://getbootstrap.com/), [Font Awesome](http://fortawesome.github.io/Font-Awesome/) and [jQuery](http://jquery.com/).  

* Clean
* Responsive
* Mobile First
* Syntax Highlighting 
* Jekyll 3 Supported
* SEO Friendly

## Screenshots


<!-- more -->

## Usage

### Installation

- Start by cloning the github repo using `git clone`
- You must have jekyll installed to run this, use `gem install jekyll` for installing it
- Use `jekyll serve` to run the site live.

### Configration

```
# Site settings
title: H3xl00m's Personal Site
name: H3xl00m's Personal Site
url: "http://H3xl00m.github.io"
email: H3xl00m@gmail.com
description: H3xl00m's Personal Site.
baseurl: "" # the subpath of your site, e.g. /blog/
twitter_username: H3xl00m
github_username:  H3xl00m
LinkedIn_username: H3xl00m
rss_url: "/feed.xml"
logo_image: "/images/logo.png"
# Build settings
gems: [jekyll-paginate]
markdown: rdiscount
highlighter: pygments
permalink: /:title/
paginate: 8
paginate_path: page/:num
```

### Creating Posts

For creating posts add this snippet in front of your post's markdown file:

```
---
layout: post
title:  "your title here"
tags: your tags here
class: post
---
```

Add content below this and save the post in `_posts` directory (you will have to create it).

### Page excluded from top bar nav

By default, created pages will show on the top bar nav. If you want page excluded from top bar nav, you just add`excludedFromNav: true` in the page as below: 

```
---
layout: page
title: Labs
permalink: /labs/
excludedFromNav:true
---
```

## License

Feel free to fork and contribute to the project, just create a pull request.

Open sourced under [MIT License](LICENSE) 


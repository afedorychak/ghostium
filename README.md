# Ghostium

[Ghostium](https://github.com/oswaldoacauan/ghostium/) is a theme focused on content based on [Medium](https://medium.com) design/ux.

![mobile view](/images/screenshot_mobile.png)

![screenshot](/images/tn.png)

## Features

* Focused on content
* Fully responsive
* HTML5 semantics, WAI-ARIA and Rich Snippets(microdata) roles
* Asynchronous content loading
* Disqus comments
* Syntax Highlight with [Prism](http://prismjs.com/)
* Google Universal Analytics snippet
* OpenGraph and Twitter Cards meta's
* Baseline HTML5 features, DNS prefetching, responsive meta
* One-file CSS/JS for performance


### Setup

1. Fork or [download](https://github.com/cxfksword/ghostium/archive/master.zip) this theme repo
3. Add config to your site `config.toml` file

```
baseurl = "http://hugo.spf13.com/"
title = "Hugo Themes"
canonifyurls = true
paginate = 10

[author]
name = "hugo"
avatar = "/img/avatar.jpg"

[params]
# site description, will show under navigation
description = "A Free Ghost Theme focused on content based on Medium. Let´s ghost!"

# site cover image url
cover = "/img/cover.jpg"

# RSS / Email (optional) subscription links (change if using something like Feedburner)
subscribe_rss = "/index.xml"

# Disqus Comments
disqus_short_name = ""

# google analytics
google_analytics_tracking_id = ""

# Enable Pjax for asynchronous (AJAX) content loading
enable_pjax = false

# social links
facebook_user = ""
googleplus_user = ""
twitter_user = ""
github_user = ""
instagram_user = ""
linkedin_user = ""
weibo_user = ""
```

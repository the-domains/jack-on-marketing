---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2016-02-16T18:09:14.073Z'
dateModified: '2016-02-16T18:08:52.082Z'
title: '302s in site moves? It’s OK, if you must'
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2016-02-16-302s-in-site-moves-its-ok-if-you-must.md
published: true
url: 302s-in-site-moves-its-ok-if-you-must/index.html
_type: Article

---
# 302s in site moves? It's OK, if you must

In John Mueller's webmaster hangout on 6 Nov 2015, I noticed a few comments on website moves which are interesting and go against standard recommendations for SEO.

In a site move (new domain name), Google considers 302s and 301s as equivalent.

"It's not the case that 302s do something magical to block the flow of PageRank" -- John Mueller

302s in a sitemove will pass PageRank as the redirects will be seen as a moved domain, not a temporary redirect. I'm assuming the requirement is also that the change of address (site move) is set in Google Search Console under site settings:
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/248ca0b8-8cf0-4505-bf40-9b3adb157a7e.jpg)

How long it takes for the new URLs to show rather than old ones is hard to say. John Mueller says it's from hours to maybe a day.

"What will probably happen is that for some URLs on your site, it will take a little bit longer, for some it will go a lot faster."

This is based on how Google crawls a website, indicating that the moved page needs to be recrawled after the change of address setting & redirects are live before the move takes effect.

The full move can take up to half a year, maybe longer.

If a site:oldsite.com advanced query is used, the indexed pages won't drop out of the SERPs entirely until the site's indexed pages are fully recrawled. Conversely, a site:newsite.com query will show a fast initial growth in indexed pages, and then a trickle of further URLs added over time.

Note that [301s are recommended by Google][0] in their guidance for site moves.

"Set up server-side redirects (301-redirect directives) from your old URLs to the new ones. The Change of address tool won't function without it."

_In other words, it's still best practice to use 301s._

But if you're not able to use 301 redirects, you can use 302 redirects in site moves without losing PageRank.

[0]: https://support.google.com/webmasters/answer/6033086?hl=en&ref_topic=6033084
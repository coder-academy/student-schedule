#### Week 5 Wednesday Day 3
<hr>
## Wednesday's Subject
Term 1 Project #1

---

## Wednesday's Challenge

Add files and metatags to your portfolio website for search engine and social media optimisation.

### robots.txt

robots.txt file is to specify how you would like your site to be 
crawled, what pages should be found and indexed during the 
crawl and what should not be.

- [Which robots Google uses to crawl the web](https://support.google.com/webmasters/answer/1061943?hl=en)
- [Google — Controlling crawling and indexing](https://developers.google.com/webmasters/control-crawl-index/docs/getting_started?csw=1)

Some examples:

- http://www.abc.net.au/robots.txt
- https://www.commbank.com.au/robots.txt

```
User-agent: *
Disallow:

Sitemap: https://YOUR_GITHUB_USERNAME.github.io/sitemap.xml
```

### Sitemaps

Sitemap

Sitemaps are an easy way for webmasters to inform search engines 
about pages on their sites that are available for crawling.
In its simplest form, a Sitemap is an XML file that lists URLs 
for a site, allowing search engines to more intelligently crawl
the site.

[Google — Learn about sitemaps](https://support.google.com/webmasters/answer/156184?authuser=1)

Examples:

- http://abr.business.gov.au/sitemap.xml
- http://www.smh.com.au/sitemap.xml

```
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"
xmlns:xhtml="http://www.w3.org/1999/xhtml"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9
http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd">
  <url>
    <loc>https://YOUR_GITHUB_USERNAME.github.io/</loc>
  </url>
  <url>
    <loc>https://YOUR_GITHUB_USERNAME.github.io/ANY_OTHER_PAGES_YOU_HAVE_AND_REPEAT/</loc>
  </url>
</urlset>
```

### Meta tags & Social network sharing

Metadata will not be displayed on the page but it will be machine parsable.
Meta elements are typically used to specify page description, author of
the document, last modified and other meta data.

There are also meta tags used by social networks such as Facebook, to display a summarised version of your page when it gets shared.
It gets displayed with a title, description, and main image.

Read more about the social media ‘open graph’ tags here: https://blog.kissmetrics.com/open-graph-meta-tags/

You can check your tags with a tool provided by Facebook here: https://developers.facebook.com/tools/debug/

```
<!DOCTYPE html>
<html>
  <head>
    <!-- Required for correct encoding for international character sets, or even emoji -->
    <meta charset="utf-8">
    <!-- Make your website actual size on mobile devices -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Description displayed in a Google result, maximum 135 to 150 characters -->
    <meta name="description" content="YOUR NAME is a junior web developer specialising in Ruby on Rails and the MEAN Stack">
    <!-- Who create this website, or wrote the content on the page -->
    <meta name="author" content="WRITE YOUR NAME">
    
    <!-- Title as used when sharing your page on a social media network such as Facebook -->
    <meta property="og:title" content="Your eye-catching title here">
    <!-- The type of content on this page -->
    <meta property="og:type" content="website">
    <!-- Description for social media -->
    <meta property="og:description" content="Your entertaining and descriptive copy here, if your meta description is good, use it.">
    <!-- Hero image for social media -->
    <meta property="og:image" content="http://www.YOUR_WEBSITE.com/image-name.jpg" >
    
    <!-- The traditional title, still useful for users and for Google -->
    <title>Welcome to my great page</title>
  </head>
  <body>    
  </body>
</html>
```

Note: keywords meta tag is not worth it: https://webmasters.googleblog.com/2009/09/google-does-not-use-keywords-meta-tag.html


## Learning Resources

### Google Crawling
- [Which robots Google uses to crawl the web](https://support.google.com/webmasters/answer/1061943?hl=en)
- [Google — Controlling crawling and indexing](https://developers.google.com/webmasters/control-crawl-index/docs/getting_started?csw=1)
- [Google — Learn about sitemaps](https://support.google.com/webmasters/answer/156184?authuser=1)

### Meta Description Guides
- https://yoast.com/meta-descriptions/
- https://moz.com/learn/seo/meta-description

### Open Graph
- https://blog.kissmetrics.com/open-graph-meta-tags/
- http://ogp.me/

### Facebook’s Shared Link Debugging Tool
- https://developers.facebook.com/tools/debug/
- Pro tip: create a work-specific Facebook account, separated from your personal one

---

# Coder Factory Academy
<p align="center"><img src="https://github.com/coder-factory-academy/cf-guidline-css/blob/master/CFA.png"></p

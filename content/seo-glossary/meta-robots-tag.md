---
title: Meta Robots Tag
---



## What is it?

Meta Robots Tag:

A Meta Robots Tag is an HTML element that provides instructions to search engine crawlers on how to treat a web page. It is placed in the header section of a web page's HTML source code and is used to control the behavior of search engine robots when they visit the page. The tag can contain various directives, such as "index" or "noindex," which tell the robots whether to include or exclude the page from their search engine results. Other directives, like "follow" or "nofollow," indicate whether to follow or not follow the links on the page. The Meta Robots Tag is an essential tool for webmasters to manage the visibility and indexing of their web pages in search engine results.

## Here are some examples:

The Meta Robots Tag is used in the HTML code of a website to provide instructions to search engine robots on how to crawl and index the page. Here are some examples of where the Meta Robots Tag is used:

1. To prevent a page from being indexed and cached:

```html
<meta name="robots" content="noindex, nofollow">
```

2. To allow a page to be indexed but not cached:

```html
<meta name="robots" content="index, nofollow">
```

3. To allow a page to be indexed and cached, but not followed:

```html
<meta name="robots" content="index, follow">
```

4. To allow a page to be indexed, cached, and followed:

```html
<meta name="robots" content="all">
```

5. To specify a specific robot to follow a link:

```html
<a href="https://example.com" rel="nofollow">Link</a>
```

6. To specify a specific robot to not follow a link:

```html
<a href="https://example.com" rel="nofollow">Link</a>
```

7. To specify a specific robot to index a page:

```html
<meta name="robots" content="index">
```

8. To specify a specific robot to not index a page:

```html
<meta name="robots" content="noindex">
```

9. To specify a specific robot to follow a link only if it's a desktop device:

```html
<a href="https://example.com" rel="nofollow" data-robots="desktop">Link</a>
```

10. To specify a specific robot to follow a link only if it's a mobile device:

```html
<a href="https://example.com" rel="nofollow" data-robots="mobile">Link</a>
```

## In Summary

The Meta Robots Tag is an HTML tag used to provide instructions to search engine crawlers on how to index and display a web page in search engine results. It is placed in the <head> section of an HTML document and can contain various directives, such as "index" (allow indexing), "noindex" (disallow indexing), "follow" (allow following of links), and "nofollow" (disallow following of links). The tag is essential for controlling the visibility and indexing of a web page, as well as managing the flow of link juice and preventing duplicate content issues.
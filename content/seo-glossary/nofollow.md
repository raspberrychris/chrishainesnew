---
title: Nofollow
---



## What is it?

Nofollow: A nofollow link is a hyperlink with a specific attribute that instructs search engines not to follow or crawl the linked page. This attribute is typically used to discourage spamming, prevent duplicate content issues, or manage the flow of link juice within a website. Nofollow links can still be clicked and visited by users, but they do not contribute to the ranking of the target page in search engine results.

## Here are some examples:

(Nofollow) is used in the following examples:

1. In the HTML code of a website, to indicate that a specific link should not be followed by search engines:

```html
<a href="https://example.com" rel="nofollow">Link to an example website</a>
```

2. In the HTTP headers of a web server, to indicate that a specific URL should not be crawled by search engines:

```
X-Robots-Tag: nofollow
```

3. In the robots.txt file of a website, to indicate that a specific directory or file should not be crawled by search engines:

```
Disallow: /directory/
Disallow: /file.html
```

4. In the JavaScript code of a website, to manipulate the `rel` attribute of a link:

```javascript
document.getElementById("link").setAttribute("rel", "nofollow");
```

5. In the CSS code of a website, to style links with the `nofollow` attribute:

```css
a[rel="nofollow"] {
  color: red;
  text-decoration: none;
}
```

## In Summary

(Nofollow) is a HTML attribute that can be added to links to indicate that the linked page should not be considered for search engine ranking or indexing. This attribute is often used when linking to external sources that are not relevant or necessary for the main content of the page, such as advertisements, sponsored content, or external resources that may not be trustworthy. By adding the (Nofollow) attribute, webmasters can help search engines understand the relevance of the linked page and improve the overall quality of search results.
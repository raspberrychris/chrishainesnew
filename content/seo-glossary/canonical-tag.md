---
title: Canonical Tag
---



## What is it?

Canonical Tag: A canonical tag, also known as a canonical link element, is an HTML attribute used to specify the preferred or canonical version of a web page. It is typically used to resolve issues with duplicate or near-duplicate content, which can occur when a single piece of content is accessible through multiple URLs. By specifying a canonical tag, search engines and other systems can determine the original and authoritative version of the content, ensuring that users are directed to the correct source and that the website's search engine rankings are not negatively affected by duplicate content.

## Here are some examples:

A canonical tag (also known as a "canonical link" or "canonical URL") is an HTML element that helps webmasters prevent duplicate content issues and inform search engines about the preferred version of a web page. Here are some examples of where a canonical tag is used:

1. Homepage: A website's homepage can have multiple URLs (e.g., www.example.com, www.example.com/index.html, www.example.com/home.html). To indicate the preferred version, a canonical tag can be added to the HTML head section of the non-preferred versions, pointing to the preferred version's URL.

```html
<link rel="canonical" href="https://www.example.com/" />
```

2. Paginated content: If a blog post or an article is divided into multiple pages, a canonical tag can be used on each page to indicate the URL of the first page (the one with the most content).

```html
<link rel="canonical" href="https://www.example.com/post/page-1" />
```

3. Sorting and filtering: If a web page displays a list of products or posts with sorting and filtering options (e.g., by price, date, etc.), a canonical tag can be used to indicate the URL of the unfiltered version of the page.

```html
<link rel="canonical" href="https://www.example.com/products" />
```

4. AMP pages: If a website has AMP (Accelerated Mobile Pages) versions of its content, a canonical tag can be used on the AMP page to indicate the URL of the non-AMP version.

```html
<link rel="canonical" href="https://www.example.com/post" />
```

5. Duplicate content due to URL parameters: If a web page's URL contains parameters that do not change the content (e.g., session IDs, source codes, etc.), a canonical tag can be used to indicate the URL without the parameters.

```html
<link rel="canonical" href="https://www.example.com/post?source=facebook" />
```

By using a canonical tag, webmasters can help search engines understand the relationship between different URLs and prevent potential penalties for duplicate content.

## In Summary

Canonical tags are a crucial aspect of SEO and website optimization. They help search engines understand the structure and content of a website, making it easier for users to find the information they're looking for. Canonical tags are used to indicate the preferred or canonical version of a web page, ensuring that search engines index and display the correct version of the content. This helps prevent duplicate content issues and improves the overall user experience.
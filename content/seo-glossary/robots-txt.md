---
title: Robots Txt
---



## What is it?

Robots.txt is a text file used by webmasters to communicate with search engine crawlers, such as Googlebot, Bingbot, and Yahoo! Slurp. It is placed in the root directory of a website and provides instructions on which pages or files the crawler should visit and which ones it should avoid. The file is named "robots.txt" and has a .txt extension.

The purpose of robots.txt is to help search engines index a website more efficiently by providing information about the structure of the site and the preferences of the webmaster. It allows webmasters to control the crawling process and prevent search engines from accessing certain areas of their site, such as administrative pages or duplicate content.

Robots.txt files can contain two main types of instructions:

1. User-agent: This directive specifies which search engine crawlers the instructions apply to. It can be a specific crawler, such as "Googlebot," or a general term like "robot" or "crawler."

2. Disallow: This directive tells the specified crawler not to visit the pages or files listed. The format is "Disallow: /path/to/page," where "path/to/page" is the URL of the page or file that should be avoided.

Here's an example of a simple robots.txt file:

```
User-agent: *
Disallow: /admin/
Disallow: /duplicate-content/
```

This robots.txt file applies to all search engine crawlers and instructs them not to visit the "/admin/" and "/duplicate-content/" directories on the website.

In summary, robots.txt is a crucial tool for webmasters to manage the indexing of their websites by search engines. It helps improve the efficiency of the crawling process and ensures that search engines only index the pages and files that are relevant and necessary for users.

## Here are some examples:

Robots.txt is used to instruct search engine crawlers on how to index and crawl a website. Here are some examples of where robots.txt is used:

1. To block specific pages or folders from being indexed:

```
User-agent: *
Disallow: /private/
Disallow: /admin/
```

2. To allow only specific pages or folders to be indexed:

```
User-agent: *
Allow: /
Allow: /public/
Allow: /news/
```

3. To block specific search engines from crawling the website:

```
User-agent: bingbot
Disallow: /
```

4. To set a specific crawl rate for search engines:

```
User-agent: *
Crawl-delay: 5
```

5. To indicate the location of the sitemap:

```
Sitemap: https://example.com/sitemap.xml
```

6. To provide additional information or comments:

```
# This robots.txt file is used to control the behavior of search engine crawlers.
# For more information, see https://www.robotstxt.org/robotstxt.html
```

Remember to place the robots.txt file in the root directory of your website to ensure it is accessible to search engine crawlers.

## In Summary

Robots.txt is a text file used by webmasters to communicate with search engine crawlers, such as Googlebot, Bingbot, and Yandexbot. It is placed in the root directory of a website and contains instructions on which pages or files the crawlers should visit and which ones they should avoid. This helps in managing the crawl budget, preventing duplicate content issues, and ensuring that sensitive or personal information is not indexed by search engines.
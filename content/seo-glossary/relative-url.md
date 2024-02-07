---
title: Relative Url
---



## What is it?

A relative URL, also known as a relative link, is a web address that points to a resource (such as a web page, image, or document) within the same domain or subdomain as the current page. It is a way to link to other resources on the same website or within the same web application without specifying the entire URL. Relative URLs are often used to create navigation menus, link to related content, or reference static resources like images or stylesheets. They provide a more efficient way to organize and link to content within a website, as they require less typing and are easier to understand and maintain.

## Here are some examples:

Relative URLs are used when linking to resources within the same domain or subdomain. Here are some examples:

1. Linking to a page within the same website:

```
<a href="./page2.html">Page 2</a>
<a href="../page3.html">Page 3</a>
<a href="../../page4.html">Page 4</a>
```

2. Linking to a resource (image, CSS file, or JavaScript file) within the same domain:

```
<img src="./image.jpg" alt="Image">
<link rel="stylesheet" href="./styles.css">
<script src="./script.js"></script>
```

3. Linking to a resource within a subdomain:

```
<a href="https://subdomain.example.com/page2.html">Page 2 on subdomain</a>
<img src="https://subdomain.example.com/image.jpg" alt="Image on subdomain">
<link rel="stylesheet" href="https://subdomain.example.com/styles.css">
<script src="https://subdomain.example.com/script.js"></script>
```

In these examples, the relative URLs are used to link to resources within the same domain or subdomain, making it easier for the browser to locate and load the resources.

## In Summary

(Relative Url) is a concept in web development that refers to a URL (Uniform Resource Locator) which is relative to the current page or context. It is a way to identify a resource or page without specifying the entire absolute URL. Relative URLs are often used in HTML and CSS files to link to other resources, such as images, stylesheets, or scripts, without having to specify the full path to the resource. This makes it easier to manage and maintain the website, as you can simply update the relative URL if the resource moves to a new location.
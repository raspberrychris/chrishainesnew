---
title: Hreflang
---



## What is it?

Hreflang (Hypertext Reference Language) is an HTML attribute that specifies the language of a linked document. It is used to help search engines and web browsers understand the language of the target document, ensuring that users are presented with content in their preferred language. The hreflang attribute is typically used in conjunction with the "href" attribute, which specifies the location of the target document.

Here's an example of how the hreflang attribute can be used in an HTML document:

```html
<a href="https://example.com/en/page" hreflang="en">English</a>
<a href="https://example.com/es/page" hreflang="es">Spanish</a>
<a href="https://example.com/fr/page" hreflang="fr">French</a>
```

In this example, the hreflang attribute is used to specify the language of the target document for each link. This information can be used by search engines to index the documents according to their language, and by web browsers to present the user with content in their preferred language.

Hreflang is an essential tool for webmasters and developers who want to create multilingual websites and ensure that their content is accessible to users from different countries and cultures. By using the hreflang attribute, they can help search engines and web browsers understand the language of their content, improving the overall user experience and making the web more inclusive and accessible to everyone.

## Here are some examples:

(Hreflang) is used to specify the language of a linked document. Here are some examples of where (Hreflang) is used:

1. In the head section of an HTML document:

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Example Document</title>
  <link rel="alternate" href="https://example.com/es" hreflang="es">
  <link rel="alternate" href="https://example.com/fr" hreflang="fr">
  <link rel="alternate" href="https://example.com/de" hreflang="de">
</head>
<body>
  ...
</body>
```

2. In the body section of an HTML document, inside a link element:

```html
<body>
  ...
  <a href="https://example.com/es" hreflang="es">Spanish</a>
  <a href="https://example.com/fr" hreflang="fr">French</a>
  <a href="https://example.com/de" hreflang="de">German</a>
  ...
</body>
```

3. In the head section of an XML document:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Example Document</title>
  <link rel="alternate" href="https://example.com/es" hreflang="es">
  <link rel="alternate" href="https://example.com/fr" hreflang="fr">
  <link rel="alternate" href="https://example.com/de" hreflang="de">
</head>
<body>
  ...
</body>
```

4. In the body section of an XML document, inside a link element:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Example Document</title>
</head>
<body>
  ...
  <a href="https://example.com/es" hreflang="es">Spanish</a>
  <a href="https://example.com/fr" hreflang="fr">French</a>
  <a href="https://example.com/de" hreflang="de">German</a>
  ...
</body>
```

## In Summary

Hreflang is an HTML attribute that specifies the language of a linked document. It is used to help search engines and web browsers understand the language of the linked document, making it easier for users to find and access content in their preferred language. The attribute can be added to any HTML element that contains a link, such as <a>, <area>, <link>, and <script> elements.
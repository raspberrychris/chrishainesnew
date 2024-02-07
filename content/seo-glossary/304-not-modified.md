---
title: 304 Not Modified
---



## What is it?

304 Not Modified

A 304 Not Modified response status code indicates that the server has not modified the requested resource since the last time it was accessed. This code is typically returned when a client sends a conditional request, such as an "If-Modified-Since" or "If-None-Match" header, and the server determines that the resource has not been modified since the specified time or entity tag.

In other words, a 304 Not Modified response means that the client's cached version of the resource is still valid and up-to-date, and no new data needs to be transferred from the server. This can help improve performance and reduce network overhead by avoiding unnecessary data transfers.

## Here are some examples:

1. When a client requests a resource that has not been modified since the last time it was accessed, the server can return a 304 Not Modified response to indicate that the client can use the previously downloaded version of the resource. This is often used for resources that change infrequently, such as images or static web pages, to reduce network traffic and server load.

2. In a web application, when a user requests a page that they have already viewed, the server can return a 304 Not Modified response to indicate that the page has not changed since the last time the user viewed it. This can help improve the performance of the application by reducing the need to regenerate the page for the user.

3. When a client requests a resource that is dependent on another resource that has not been modified, the server can return a 304 Not Modified response for the dependent resource. For example, if a web page includes an image that has not been modified, the server can return a 304 Not Modified response for the image, indicating that the client can use the previously downloaded version of the image.

4. In an API, when a client requests data that has not been modified since the last time it was accessed, the server can return a 304 Not Modified response to indicate that the client can use the previously received data. This can help improve the performance of the API by reducing the need to retrieve and return the unchanged data.

5. When a client requests a resource that is cached by an intermediate cache, such as a proxy server or a browser cache, the cache can return a 304 Not Modified response if the resource has not been modified since the last time it was accessed. This can help improve the performance of the network by reducing the need to retrieve the resource from the origin server.

## In Summary

304 Not Modified is a HTTP status code that indicates the server has not modified the requested resource since the last time it was accessed. This code is typically returned when a client sends a conditional request, such as a GET request with an "If-Modified-Since" header, and the server determines that the resource has not been modified since the specified date. In this case, the server will return the 304 status code along with the unmodified resource, if any.
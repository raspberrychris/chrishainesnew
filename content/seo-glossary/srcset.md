---
title: Srcset
---



## What is it?

Srcset (Srcset Attribute)

Srcset, or the Srcset attribute, is an HTML attribute that allows web developers to specify a set of image sources for an HTML `img` element. It is used to provide multiple image sources with different resolutions, sizes, or formats, ensuring that the browser can choose the most appropriate image source based on the user's device and network conditions.

The Srcset attribute is commonly used in responsive web design to provide different image sources for different screen sizes and resolutions. This helps in optimizing the website's performance and ensuring that the images are displayed correctly on various devices and browsers.

Here's an example of how the Srcset attribute can be used in an HTML `img` element:

```html
<img src="image1.jpg" srcset="image1-small.jpg 320w, image1-medium.jpg 640w, image1-large.jpg 1280w" alt="Image">
```

In this example, the Srcset attribute provides three different image sources with different widths (320w, 640w, and 1280w). The browser will choose the most appropriate image source based on the user's device width and network conditions. If the user's device has a width of 320 pixels or less, the browser will use the `image1-small.jpg` source. If the device width is between 321 and 640 pixels, the `image1-medium.jpg` source will be used. And if the device width is 641 pixels or more, the `image1-large.jpg` source will be used.

The Srcset attribute is an essential tool for web developers to create responsive and performant websites, ensuring that the images are displayed correctly and efficiently on various devices and browsers.

## Here are some examples:

Srcset is used in the context of responsive images, where multiple images of different sizes and resolutions are provided to ensure the best possible image quality and performance on various devices and screen sizes. Here are some examples of where srcset is used:

1. In an HTML `img` element:

```html
<img src="image.jpg" srcset="image-small.jpg 320w, image-medium.jpg 640w, image-large.jpg 1280w" alt="Image description">
```

In this example, the browser will choose the most appropriate image from the srcset based on the device's screen width.

2. In a CSS `background-image` property:

```css
.image-container {
  background-image: url("image.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-srcset: "image-small.jpg 320w, image-medium.jpg 640w, image-large.jpg 1280w";
}
```

In this example, the browser will choose the most appropriate image from the srcset based on the container's width and height.

3. In a JavaScript library or framework:

```javascript
// Using a library like React, you can pass the srcset as a prop to an image component
const imageSrcSet = {
  small: "image-small.jpg",
  medium: "image-medium.jpg",
  large: "image-large.jpg",
};

return (
  <div>
    <Image src={imageSrcSet.small} srcSet={imageSrcSet} alt="Image description" />
  </div>
);
```

In this example, the library will choose the most appropriate image from the srcset based on the component's dimensions and device screen size.

4. In a web font:

```css
@font-face {
  font-family: "MyFont";
  src: url("myfont-regular.woff2") format("woff2"), url("myfont-regular.ttf") format("truetype");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: "MyFont";
  src: url("myfont-bold.woff2") format("woff2"), url("myfont-bold.ttf") format("truetype");
  font-weight: bold;
  font-style: normal;
}

@font-face {
  font-family: "MyFont";
  src: url("myfont-italic.woff2") format("woff2"), url("myfont-italic.ttf") format("truetype");
  font-weight: normal;
  font-style: italic;
}
```

In this example, the browser will choose the most appropriate font file from the srcset based on the device's capabilities and the specified format.

## In Summary

Srcset is an HTML attribute that allows web developers to specify multiple image sources for a single image element. This attribute is used to provide different image sizes and resolutions to accommodate various devices and screen sizes. The browser will automatically choose the most appropriate image source based on the user's device and screen resolution.
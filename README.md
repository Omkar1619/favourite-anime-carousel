
# Favourite-anime-carousel
***

## Description
The purpose of this project is only to record my learnings.

I essentially wanted to learn how to create an image carousel. So I found a video to help me do just that!

***

## Resources

[How to code a carousel with HTML, CSS and JavaScript - from scratch (part 1)](https://www.youtube.com/watch?v=VYsVOamdB0g&t=1s)

[How to code a carousel with HTML, CSS and JavaScript - from scratch (part 2)](https://www.youtube.com/watch?v=gBzsE0oieio)
    
***    
    
## Description

In the above vidoes, Kevin Powell shows how to make an image carousel using html, css and vanilla js.

I mostly followed along with his video but instead of using random images, I made a carousel of images of my favourite anime.

***

## Future Plans

I am yet to optimize the site so that it would work on different devices so learning responsive design is the next step.

I plan on learning about media queries and other stuff that helps making a site responsive and I will keep on updating this site to inculcate everything that I learn.

***

## What I Learned

This is essentially a record of the new stuff that I learned while making this project so that I can refer to it later. It simply enlists things such as cdd properties or js functions that I learned while I created this project.

1. `object-fit: cover`:

The CSS object-fit property is used to specify how an `<img>` or `<video>` should be resized to fit its container.
The object-fit property can take one of the following values:

  * fill - This is default. The image is resized to fill the given dimension. If necessary, the image will be stretched or squished to fit.

  * contain - The image keeps its aspect ratio, but is resized to fit within the given dimension.

  * cover - The image keeps its aspect ratio and fills the given dimension. The image will be clipped to fit.

  * none - The image is not resized.

  * scale-down - the image is scaled down to the smallest version of none or contain.

2. `overflow: hidden`:

The CSS overflow property controls what happens to content that is too big to fit into an area.
The overflow property has the following values:

  * visible - Default. The overflow is not clipped. The content renders outside the element's box
    
  * hidden - The overflow is clipped, and the rest of the content will be invisible
    
  * scroll - The overflow is clipped, and a scrollbar is added to see the rest of the content
    
  * auto - Similar to scroll, but it adds scrollbars only when necessary

3. `element.getBoundingClientRect()`:

The Element.getBoundingClientRect() method returns a DOMRect object providing information about the size of an element and its position relative to the viewport.

Return Value:

The returned value is a DOMRect object which is the smallest rectangle which contains the entire element, including its padding and border-width. The left, top, right, bottom, x, y, width, and height properties describe the position and size of the overall rectangle in pixels. Properties other than width and height are relative to the top-left of the viewport.

4. `element.nextElementSibling()` or `element.previousElementSibling()`:

The Element.nextElementSibling read-only property returns the element immediately following the specified one in its parent's children list, or null if the specified element is the last one in the list.

The Element.previousElementSibling read-only property returns the Element immediately prior to the specified one in its parent's children list, or null if the specified element is the first one in the list.

5. `element.closest(selectors)`:

The closest() method of the Element interface traverses the element and its parents (heading toward the document root) until it finds a node that matches the specified CSS selector.

6. `findIndex((element, index) => { /* condition */ })`:

The findIndex() method returns the index of the first element in an array that satisfies the provided testing function. If no elements satisfy the testing function, -1 is returned.

***

# Order summary component

This is the solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshots/desktop_screenshot.jpg)

Desktop screenshot

![](./screenshots/desktop_screenshot.jpg)

Mobile screenshot

### Links

- Solution URL: [https://github.com/goyashodan/order-summary-component](https://github.com/goyashodan/order-summary-component)
- Live Site URL: [https://goyashodan.github.io/order-summary-component/](https://goyashodan.github.io/order-summary-component/)

## My process

### Built with

- HTML5
- CSS variables
- Flexbox

### What I learned

The three aspects of learning were HTML, CSS, and some advanced CSS aspects. For basic HTML, I was able to create an HTML document from scratch and link it to an external stylesheet. Some advanced CSS techniques used were CSS variables and CSS flexbox.

CSS variables were used for defining the document's standard style colors:

```css
:root {
    font-size: 16px;
    font-family: 'Red Hat Display', sans-serif;
    --pale-blue: hsl(225, 100%, 94%);
    --bright-blue: hsl(245, 75%, 52%);
    --very-pale-blue: hsl(225, 100%, 98%);
    --desaturated-blue: hsl(224, 23%, 55%);
    --dark-blue: hsl(223, 47%, 23%);
    --active-bright-blue: hsl(245, 55%, 68%);
}
```

Flexbox were used to define the structure of certain ``/div`` elements, allowing children elements to be positioned appropriately

```html
<div id="inner-order-container">
  ...
</div>
```

```css
#inner-order-container {
    padding: 50px;
    display: flex;
    flex-direction: column;
}
```
### Continued development

One way to improve the project is to accomodate for vertical ``@media`` queries. For example, when the browser is dragged vertically, the hero image gets chopped off. Likely, this has to do with the ``order-hero`` id.

### Useful resources

- [A Complete Guide to Flexbox by Chris Coyier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand how flexbox works in relation with HTML elements. 

## Author

- Website - [Yashodan Govender](https://www.yashodan.com)
- Twitter - [@goyashodan](https://twitter.com/goyashodan)
- LinkedIn - [@goyashodan](https://www.linkedin.com/in/goyashodan/)

## Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io/) for providing frontend challenges to work on.

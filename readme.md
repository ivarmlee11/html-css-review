# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!-- Code goes here -->
<!DOCTYPE html>

<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <title></title>
  <<body>
    
  </body>
  
</html>
```

2.) What are the differences between these tags?

```html
<!-- Tag 1 -->
<img src="images/me.jpg" alt="My profile image">

<!-- Tag 2 -->
<div></div>
```

```
Explain here.
```One tag is self closing while the other is not.

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- Inline CSS -->
<div style="background-color: red;"></div>
Frowned upon
This style takes precedence over other forms of styling

<!-- Internal style sheet -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>
Useful for single page static sites

<!-- External style sheet (not shown) -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
Explain here
```
A developer should use external style sheets where possible 

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* comment like this */
div {
  border-radius: 50%;
}
/* rounds the corneers of a div element */
.header p {
  font-size: 18px;
}
/* sets font size to 18px */
.footer {
  position: absolute;
  bottom: 0;
}
/* element will always be 0px from the bottom of the page */
.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}
/* applies a background image that covers 100% of the div */
.ninja:hover {
  display: none;
  color: black;
}
```
/* pseudo selector hover changes the display of an element when a mouse is hovering over it */

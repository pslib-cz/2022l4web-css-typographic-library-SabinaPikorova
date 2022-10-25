# Typography CSS library
**Author:** [Sabina Pikorová](https://github.com/SabinaPikorova)
## Description
This is a free typography library that was created for a school project
## Demo site
Link to **[demo](http://pslib-cz.github.io/2022l4web-css-typographic-library-SabinaPikorova)** site for preview.
## Parts of the documentation
1. [Implementation](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Implementation)
2. [Colors](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Colors)
3. [Typography](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Typography)
4. [Headings](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Headings)
5. [Types of text](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Types-of-text)
   - [Normal text](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Normal-text)
   - [Styled text](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Styled-text)
7. [Lists](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Lists)
   - [Unordered list](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Unordered-list)
   - [Ordered list](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Ordered-list)
9. [Table](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Table)
10. [Buttons](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Buttons)
11. [Pictures](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorovaPictures)
    - [Single picture](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Single-picture)
    - [Gallery](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Gallery)
## Implementation
1. Download the files you need in [docs](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova/tree/master/docs) folder
2. Add files inside your project folder
3. Link style.css, responsive.css and hamburger.css files to <head> in every HTML page using syntax:
```<link href="./css/style.ccs rel="stylesheet">```
```<link href="./css/responsive.ccs rel="stylesheet">```
```<link href="./css/hamburger.ccs rel="stylesheet">```
   Also link hamburger.js file to all yours HTML pages and place it after </footer> using syntax:
```<script href="./js/hamburger.js</script>"```
## Colors 
Typography CSS library has predefined colors. You can find them in style.css folder in ```:root``` selector between the lines 1-4. You can change the colours however you want.
## Typography
Typography css has predefined Roboto Condensed font. If this font isn't from some reason implemented on the page, sans-serif will be used. 
## Headings
* ```<h1>``` font size is 32px
* ```<h2>``` font size is 24px
* ```<h3>``` font size is 18.72px
* ```<h4>``` font size is 16px
* ```<h5>``` font size is 13.28px
* ```<h6>``` font size is 10.72px
## Types of text
### Normal text
Size of normal text is ```1rem```.
### Styled text
* ```<small>``` for <sub>small</sub> text
* ```<b>``` or ```<strong>``` for **bold** text 
* ```<u>``` for Underlined text
* ```<mark>``` for (yellow) highlited text
* ```<s>``` for ~~striked~~ text
* ```<i>``` or ```<em>``` for * *italic text* *
* ```<sub>``` for <sub>subscript</sub> text
* ```<sup>``` for <sup>superscript</sup> text
You can even use predefined classes:
* ```<class="colored-text>``` for colored text
## Lists
### Unordered list
```
<ul>
    <li></li>
    <li>
        <ul>
            <li></li>
            <li></li>
        </ul>
    <li>
</ul>
```
### Ordered list
```
<ol>
    <li></li>
    <li>
        <ol>
            <li></li>
            <li></li>
        </ol>
    <li>
</ol>
```
## Table
```
<table>
    <thead>
        <tr>
            <th>First heading</th>
            <th>Second heading</th>
            <th>Third headind</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>First item</th>
            <th>Second item</th>
            <th>Third item</th>
        </tr>
        <tr>
            <th>First item</th>
            <th>Second item</th>
            <th>Third item</th>
        </tr>
        <tr>
            <th>First item</th>
            <th>Second item</th>
            <th>Third item</th>
        </tr>
    </body>
</table>
```
## Buttons
```<button class="btn">Button</button>```
There are 2 predefined button classes:
* ```class="btn-normal"``` for classic button
* ```class="btn-nothing"``` fur unklickable button
## Pictures
For embending and image in HTML is used tag ```<img>```. Use this syntax for single picture:
### Single picture
```
<figure class="gallery__photo">
    <a href="./images/file.jpg">
        <img src="./images/file.jpg" alt="alternative text">
        <figcaption class="gallery__caption">Caption</figcaption>
    </a>
</figure>
```
### Gallery
Use this syntax for photo gallery.
```
<div class="gallery">
    <figure class="gallery__photo>
        <a href="./images/file.jpg">
            <img src="./images/file.jpg" alt="alternative text">
        </a>
    </figure>
    <figure class="gallery__photo>
        <a href="./images/file.jpg">
            <img src="./images/file.jpg" alt="alternative text">
        </a>
    </figure>
</div>
```

                                                               
                                                            

  

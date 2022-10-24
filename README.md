# Typography CSS library
**Author:** *Sabina Pikorová*
## Description
This is a free typography library that was created for a school project
## Demo site
Link to **[demo](http://pslib-cz.github.io/2022l4web-css-typographic-library-SabinaPikorova)** site for preview.
## Parts of the documentation
1. [Implementation](https://github.com/pslib-cz/2022l4web-css-typographic-library-SabinaPikorova#Implementation)
2. Colors
3. Typography
4. Headings
5. Types of text
   - Normal text
   - Styled text
7. Lists
   - Unordered list
   - Ordered list
9. Table
10. Buttons
11. Pictures
    - Single picture
    - Gallery
## Implementation
1. Download page.css in docs/download folder
2. Add file inside your project folder
3. Link page.css file to <head> in every HTML page using syntax:
## Colors 
Typography CSS library has predefined colors. You can find them in style.css folder in ```:root``` selector between the lines 1-4. You can change the colours however you want.
## Typography
Typography css has predefined Roboto Condensed font. If this font isn't from some reason implemented on the page, sans-serif will be used. 
## Headings
* ```<h1>```
* ```<h2>```
* ```<h3>```
* ```<h4>```
* ```<h5>```
* ```<h6>```
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
* ```class="btn-normal"```
* ```class="btn-nothing"```
## Pictures
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

                                                               
                                                            

  

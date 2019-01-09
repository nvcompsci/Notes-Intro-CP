# Creating Web Pages

### Adding Text to the Page

`<h1>Header</h1>` is used for large headings.  
`<h2>Header</h2>` is used for medium headings.  
`<h3></h3>` down to `<h6></h6>` are used for small headings.  
`<p>Paragraph text goes here.</p>` are used for standard paragraphs of text.  

### Lists
- `<ul></ul>` is used to create an unordered list  
- `<ol></ol>` is used to create an ordered list  
- `<li></li>` is for each individual item in the list  
- Notice how `<li>` is *nested* inside of `<ul>`  

This code:  
```html
<ul>
  <li>Item one</li>
  <li>Item two</li>
  <li>Item three</li>
</ul>
```
Produces this...
<ul>
  <li>Item one</li>
  <li>Item two</li>
  <li>Item three</li>
</ul>  

### Images
```html
<img src="https://www.springfieldnewssun.com/cat-680x383.jpeg" width="300" height="200">
```
### Creating sections with `<div>`
Add a `<div>` tag before the elements and a closing `</div>` tag after the elements to enclose them inside of a `<div>`.  
```html
<div>
  <h1>The Weather</h1>
  <p>It will be cold and rainy today.</p>
</div>
```
`<div>` does not show up as anything on the page unless you style it with CSS. They are used to simply organize your page, but with CSS they can be made to look like boxes that contain content.  
## Formatting and Design with *CSS*

### Styling the entire page
```css
body {
  color: blue;
  background-color: lightgreen;
}
```
### Styling certain elements / tags
```css
p {
  font-size: 12pt;
  color: red;
}
```
### Styling specific elements using `id`
`#` represents `id` when selecting elements in CSS.  
```css
#favMusic {
  background-color: white;
  border: 3px solid red;
}
```

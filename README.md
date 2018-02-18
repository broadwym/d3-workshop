# d3-workshop
Introductory workshop to D3, Vanderbilt Digital Scholarship (2018) 

## Introduction 
### Why D3? 
<i>You learn French to write poetry, not nutrition labels</i>. Likewise, you don't learn D3 to create simple visualization. D3 has an incredibly steep learning curve, but is worth learning because of its rich visualization capabilities. 

* Examples: [Nadieh Bremmer](https://www.visualcinnamon.com/), [Alberto Cuadra (Science Magazine)](https://twitter.com/acuadra?lang=en), [John Muyskens (Washington Post, Visual Editor)](https://www.washingtonpost.com/people/john-muyskens/?utm_term=.23148bcef196)

* What to use D3 for?
  * First and foremost, <b>complex visualizations</b>. There is no barchart( ) function. You build your visualization ground up. 
  * For creating your own data visualizaton library. 
  * Custom chart-type or custom interaction. 
  * [API of all D3's capabilities](https://github.com/d3/d3/blob/master/API.md)  

Data Driven Documents (D3.js) is a library (or toolkit), not a language. It's comprised of existing web standards, like CSS3, HTML5, and SVG. See: ["The Hitchiker's Guide to D3"](https://medium.com/@enjalot/the-hitchhikers-guide-to-d3-js-a8552174733a). In plain language, what you want to do is a) take your data, b) bind it to SVG or HTML elements, and c) manipulate the elements based on your data. Learn more about D3 foundationals [here](https://www.dashingd3js.com/basic-building-blocks). 

## HTML5, CSS, JS
**Hyptertext Markup Language**
  * The main markup language for displaying web pages. HTML elements are the building blocks of the HTML web page
  * Use this in lieu of SVG to make viz by manipulating <div> tags
  * Basic HTML follows the DOM
  
**Cascading Style Sheet**
  * Is the style sheet language used for describing the presentation of the document
  * Can be applied to HTML and SVG 
  * `<style>
  p {font-size : 12pt;}
</style>`
  * Where font-size is the rule (or attribute) you attach to HTML's "p" element 
  
**JavaScript**
  * Programming language used to give sophisticated functionality to webpages before, during and after they load. 
  * Use it to write functions to interface with the data and D3.js.
  * You can put JS inline, in the body, or head of your document 

## DOM, SVG
**Document Object Model**
  * The DOM allows programs and scripts to dynamically access and update the structure, content, and style of a document.
  * It defines in what order your objects will render on-screen.
  * This is what allows you to represent and interact with objects in your document. 
  * DOM has a DOM Tree. Think of this as your backbone or structure of your document. It hierarchically builds your document into parent, child, and sibling relationships. 

**Scalable Vector Graphics** 
  * Common tool for making data viz with D3
  * You can also draw on a JS canvas or output to HTML
  * Downloadable and openable in Adobe or Inkscape: good for making your graphic print-friendly 
  * Use it to reference an object in your D3 document
  * For basic D3, you want to use SVG as your canvas upon which you draw shapes 

## Blockbuilder 
**Blockbuilder** is a way to share your visualizations with the D3 community. It links with your Github and automatically generates gists when you save your document. 
* [About Blockbuilder](http://blockbuilder.org/about) 


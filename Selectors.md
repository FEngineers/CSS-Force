# Usual Selector
### .class
Class Selector  *Class选择器*
```css
/* Selects all elements with class="date-posted" */
.date-posted {color: #ccc;}
```

### #id
ID Selector  *ID选择器*
```csss
/* Selects the element with id="intro" */
#intro {font-weight: bold;}
```

### * 
Universal Selector  *通用元素选择器*
```css
/* Selects all elements */
* {
 margin: 0;
 padding: 0;
}
/* Selects all elements under class container */
#container * {
 border: 1px solid black;
}
```
I'd advise you to never use this in production code. It adds too much weight on the browser, and is unnecessary.

### element 
Element Type Selector  *标签选择器*
```css
/* Selects all <p> elements */
p {color: black;}
/* Selects all <h1> elements */
h1 {font-weight: bold;}
```

### element,element
Selector Grouping *组选择器*
```css
/* Selects all <div> elements and all <p> elements */
div, p {
 font-size: 16px;
}
```

### element element
Descendant Selector  *后代元素选择器*
```css
Selects all <p> elements inside <blockquote> elements
blockquote p {padding-left: 2em;}
```

### element>element
Child Combinator *子元素选择器*
```css
/* Selects all class="box" elements where the parent is a id="container" element */
#container > .box {
 float: left;
 padding-bottom: 15px;
}
```

### element+element
Adjacent Sibling Combinator  *相邻元素选择器*
```css
/* Selects all <p> elements that are placed immediately after <ul> elements */
ul + p {
   color: red;
}
```

### element1~element2
General Sibling Combinator  *同级元素通用选择器*
```css
/* Selects every <ul> element that are preceded by a <p> element */
p ~ ul {
   color: red;
}
```

### [attribute]
```css
/* Selects all elements with a target attribute */
[target]
```
### [attribute=value]
```css
/*  Selects all elements with target="_blank" */
[target=_blank]
```
### [attribute~=value]
```css
/* Selects all elements with a title attribute containing the word "flower" */
[title~=flower]
```
### [attribute|=value]
```css
/* Selects all elements with a lang attribute value starting with "en" */
[lang|=en]
```
### [attribute^=value]
```css
/* Selects every <a> element whose href attribute value begins with "https" */
a[href^="https"]
```
### [attribute$=value]
```css
/* Selects every <a> element whose href attribute value ends with ".pdf" */
a[href$=".pdf"]
```
### [attribute*=value]
```css
/* Selects every <a> element whose href attribute value contains the substring "w3schools" */
a[href*="w3schools"]
```

### X[title]
Attribute Selector  *属性选择器*
```css
input[type="text"] {
 background-color: #444;
 width: 200px;
}
```

### 组选择器


### 复合选择器



### X:pseudo-classes
Pseudo-class *伪类选择器*


# THANKS
CSS Mastery: Advanced Web Standards Solution (Second Edition)
[The 30 CSS Selectors you Must Memorize](http://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)
[CSS Selectors](http://www.sitepoint.com/web-foundations/css-selectors/)


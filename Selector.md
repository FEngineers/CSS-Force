### X 
Element Type Selector

*标签选择器*
```css
p {color: black;}
h1 {font-weight: bold;}
```

### .X 
Class Selector

*Class选择器*
```css
.date-posted {color: #ccc;}
```

### #X 
ID Selector

*ID选择器*
```csss
#intro {font-weight: bold;}
```

### * 
Universal Selector

*通用元素选择器*
```css
* {
 margin: 0;
 padding: 0;
}
#container * {
 border: 1px solid black;
}
```
I'd advise you to never use this in production code. It adds too much weight on the browser, and is unnecessary.

### X > Y
Child Combinator

*子元素选择器*
```css
#container > .box {
 float: left;
 padding-bottom: 15px;
}
```

### X Y 
Descendant Selector

*后代元素选择器*
```css
blockquote p {padding-left: 2em;}
```

### X + Y 
Adjacent Sibling Combinator

*相邻元素选择器*
```css
ul + p {
   color: red;
}
```

### X[title]
Attribute Selector

*属性选择器*
```css
input[type="text"] {
 background-color: #444;
 width: 200px;
}
```

### 组选择器


### 复合选择器




# THANKS
CSS Mastery: Advanced Web Standards Solution (Second Edition)
[The 30 CSS Selectors you Must Memorize](http://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)
[CSS Selectors](http://www.sitepoint.com/web-foundations/css-selectors/)


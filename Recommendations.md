# Name Element
We should name a element according to "What's the elememnt used to do?" instead "What's the element looks like".

We should use ".warning" instead ".yellow"

# Both Class and ID are case sensitive
We recommend to use lowercase for Class and ID

We should use "carousel-container" instead "carouselContainer"

# Height Percentage
Height percentage is related to parent's height, not fot itself.

# Dont add Class for every element
We can add a Class for parent element, and use cascade to control all the Children.

# Divitus: Div is not always necessary
We should use:
```html
<ul class="nav">
  <li>...</li>
<ul>
```
instead
```html
<div class="nav">
  <url>
    <li>...</li>
  </ul>
</div>
```

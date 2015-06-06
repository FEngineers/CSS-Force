### Only CSS loading spinner
```css
@keyframes spinner {
    to {transform: rotate(360deg);}
}
 
@-webkit-keyframes spinner {
    to {-webkit-transform: rotate(360deg);}
}
 
.spinner {
    min-width: 30px;
    min-height: 30px;
}
 
.spinner:before {
    content: 'Loading…';
    position: absolute;
    top: 50%;
    left: 50%;
    width: 24px;
    height: 24px;
    margin-top: -13px;
    margin-left: -13px;
}
 
.spinner:not(:required):before {
    content: '';
    border-radius: 50%;
    border: 1px solid #ccc;
    border-top-color: #03ade0;
    animation: spinner .6s linear infinite;
    -webkit-animation: spinner .6s linear infinite;
}
```
[More Style](http://stephanwagner.me/only-css-loading-spinner)


### Blink
```css
.blink_me {
    color: #498f24;
    font-weight: 800;
    font-size: 20px;
    -webkit-animation-name: blinker;
    -webkit-animation-duration: 1s;
    -webkit-animation-timing-function: linear;
    -webkit-animation-iteration-count: infinite;
    
    -moz-animation-name: blinker;
    -moz-animation-duration: 1s;
    -moz-animation-timing-function: linear;
    -moz-animation-iteration-count: infinite;
    
    animation-name: blinker;
    animation-duration: 1s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}

@-moz-keyframes blinker {
    0% { opacity: 1.0; }
    50% { opacity: 0.0; }
    100% { opacity: 1.0; }
}

@-webkit-keyframes blinker {
    0% { opacity: 1.0; }
    50% { opacity: 0.0; }
    100% { opacity: 1.0; }
}

@keyframes blinker {
    0% { opacity: 1.0; }
    50% { opacity: 0.0; }
    100% { opacity: 1.0; }
}
```

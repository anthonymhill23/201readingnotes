# Different types of CSS in CSS3


With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.


## Transform Syntax

div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}


## 2D Rotate

.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}


## 2D Scale

.box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}

Important note however! It is possible to scale only the height or width of an element using the scaleX and scaleY values. The scaleX value will scale the width of an element while the scaleY value will scale the height of an element. To scale both the height and width of an element but at different sizes, the x and y axis values may be set simultaneously. To do so, use the scale transform declaring the x axis value first, followed by a comma, and then the y axis value.





Links used for notes:


 [8 simple CSS transformations ] (https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

[CSS Transformations](https://learn.shayhowe.com/advanced-html-css/css-transforms/)
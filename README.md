# Adding Header

To add the header add the code from below below ur navbar
```html
<header class="header">

</header>
```
And the code below in your css
```css
.header{
 background-image: url('../images/headerback.jpg');
 background-attachment: fixed;
 background-size: cover;
 background-position: center;
}
```

And also create main.js and add the following
```js
$(document).ready(function(){
    $('.header').height($(window).height());
   })
```

Inculde your js and jquery  by adding the lines below just before the closing body tag
```html
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script type="text/javascript" src='main.js'></script>
```
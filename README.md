# Adding Overlay 

To add some text over your background using overlay. Add the line below within your header tag
```html
  <div class="overlay"></div>
```
And css below to add some transperancy
```css
.overlay {
    position: absolute;
    min-height: 100%;
    min-width: 100%;
    left: 0;
    top: 0;
    background: rgba(244, 244, 244, 0.6);
}
```

## Adding Text 

Create a container within the header below the overlay in yout html document
```html
 <div class="container">
        <div class="description">
            <h2> Bootstrap 4 Site</h2>
            <p>Welcome To The Site</p>
        </div>
 </div>
```
And add the following in main.css
```css
.description {
    position: absolute;
    top: 30%;
    margin: auto;
    padding: 2em;
}
```

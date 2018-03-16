# Adding About Section

 To add an about section add the following code below in yout html document
```html
  <div class="about" id="about">
                <div class="container">
                  <h1 class="text-center">About Me</h1>
                        <div class="row"> 
                        <div class="col-lg-4 col-md-4 col-sm-12">
                                <img src="https://scontent-bom1-1.xx.fbcdn.net/v/t1.0-9/10256849_727704323919639_2073406968316271581_n.jpg?_nc_cat=0&oh=786919884cdea959724bd0e80aacfe42&oe=5B43DBA4" class="img-fluid">
                                <span class="text-justify">Web Developer</span>
                                </div>
                                <div class="col-lg-8 col-md-8 col-sm-12 desc">
                                
                                <h3>User Profile</h3>
                                <p>
                                This Is The Description
                                </p>
                                </div>
                        </div>
                </div>
        </div>
```

And add the following css
```css
.about{
 margin: 4em 0;
 padding: 1em;
 position: relative;
}
.about h1{
 color:#F97300;
 margin: 2em;
}
.about img{
 height: 100%;
    width: 100%;
    border-radius: 50%
}
.about span{
 display: block;
 color: #888;
 position: absolute;
 left: 115px;
}
.about .desc{
 padding: 2em;
 border-left:4px solid #10828C;
}
.about .desc h3{
 color: #10828C;
}
.about .desc p{
 line-height:2;
 color:#888;
}
```
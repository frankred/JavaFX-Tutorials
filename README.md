JavaFX-Tutorials
================

This is the tutorials repository of http://blog.mynotiz.de. In my opinion the JavaFX CSS Reference Guide is not well elaborated. With the help of screenshots and concrete examples it would be much easier to understand the explanations. On the following page I want to give you some examples for specific components. 

#Progress-Bar
![Progress-Bar Tutorial](http://rapid-img.de/images/efbacb1c.png)
```css
.progress-bar {
    -fx-background-color: yellow;
    -fx-background-radius: 10, 10, 10, 10;

}

.progress-bar .track{
    -fx-background-color: green;
    -fx-background-insets: 20;
    -fx-background-radius: 6, 6, 6, 6;
}

.progress-bar .bar { 
    -fx-background-color: grey;
    -fx-background-insets: 30, 30, 30, 30; 
    -fx-background-radius: 4, 4, 4, 4;
}
```

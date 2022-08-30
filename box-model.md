# kevin-powell-css
## box model
[box-model](./img/27.png)
>when we declare a width to an element, that width is setting the width of the content.

>to help our lives easier, its very common to change  the `box-sizing` of an element to `border-box`.it will set the width to all content,padding and border(but not the margin)
```css
* {
    box-sizing: border-box;
}
```
>`margin` is spacing between elements.so margin can impact other elements

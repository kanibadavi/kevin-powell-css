# kevin-powell-css
## box model
[box-model-image](./img/27.png)

>`about the width, dont use it!`  

>when we declare a width to an element, that width is setting the width of the content.

>to help our lives easier, its very common to change  the `box-sizing` of an element to `border-box`.it will set the width to all content,padding and border(but not the margin)
```css
*,
*::before,
*::after {
    box-sizing: border-box;
}
```
>`margin` is spacing between elements.so margin can impact other elements

<hr>

>`about te height,dont use it!`

 use these instead:

- `min-height` 
- `padding` 
- `display:flex`

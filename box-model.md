# kevin-powell-css
## box model
[box-model-image](0fqvvuzxoh2o.png)

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

<hr>
<hr>

## inheritance
1. anything related to typography is inherited
like:
- font size 
- font family
- color
2. nothing related to layout is inherited
like:
- margin
- padding 
- height and width
3. the following do not inherit things like you would expect them to
- button
- input
- optgroup
- select
- textarea
>they are inherited by using `inherit` as our value
```css
button,
input,
optgroup,
select,
textarea {
   font-family:inherit;
}
```
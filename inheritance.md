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
<hr>
<hr>
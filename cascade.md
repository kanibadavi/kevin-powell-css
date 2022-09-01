# cascade
## cascade algorithm
1. origin and importance
2. specificity
3. order of appearance
> it doesnt matter what order you put the classes in the html.it goes and sees whats the order in your css.
```html
<div class="blue red">
```
```css
.red {
    background:red
}
.blue {
    background:blue
}
```
>in this case it turns out to blue, no matter what is the order in html.
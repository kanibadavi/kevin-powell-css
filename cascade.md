# cascade
## cascade algorithm
1. `origin and importance`
> the order of origin is:
1. author declaration(things we write)
2. user declaration
3. user agent declaration(browser defaults)
> and the order of importance is:
wherever we have `!important`

>and the last but not the least order of all is:
1. important user declaration
2. important author declaration
3. animations
4. transitions
5. author declaration
6. user declaration
7. user agent declaration
<hr>
<hr>

2. `specificity`
<hr>
<hr>

3. `order of appearance`
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
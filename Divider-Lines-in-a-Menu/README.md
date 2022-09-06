# To add a divider

We add a right border in each ``list item`` but ``not`` in the last one
```css
li:not(:last-child) {
    border-right: 1px solid rgb(70, 70, 70);
}
```
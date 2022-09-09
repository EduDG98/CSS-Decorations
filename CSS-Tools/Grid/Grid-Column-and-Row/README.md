# GRID Columns and row

1. To define columns and rows:
```css
    grid-template-columns: 1fr auto 1fr;
    grid-template-rows: repeat(4, 1fr);
```

2. If we want a specific distribution (as should be always) we define where each element start and finish in the board:

```css
    grid-column: 1/4;       /* From column 1 to column 3*/
    grid-row: 1/3;          /* From column 1 to row 2*/
```
the first number is where we start counting and the last one is where we finish, we have to know that the last number it not include so we have to substract a number.
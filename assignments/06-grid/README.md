# Introduction to Cascading Style Sheets (CSS)

## Grid
Grid was introduced around the same time as flexbox. And as the the name suggests makes it easy to lay out stuff in a grid.

To use grid, the element container you want to behave as a grid should be marked as `display: grid` .
E.g. 

```css
  .grid {
    display: grid;
  }
```

For further information about grid, please look at "A Complete Guide to Grid" at the bottom, for an in depth explanation of all the features of grid.

## Changes to implement
* This assignment can be done without changing any HTML, so please try to do this inside sheet.css.
* Below the assignments are related resources, open them up before starting.

1. Our product manager Chuck Norris has decided we need to offer up some products on our web page. 
He has laid them out in a grid container, but it's looking a bit off. Can you change the layout so we get 3 items per row.
<details>
  <summary>Hint</summary>
  Use template columns
</details>
2. Now things look better. On desktop. Can you think of a way to make things look nice on mobile as well.
<details>
  <summary>Hint</summary>
  You guessed it media queries to the rescue again!
</details>
3. BONUS: Can you give every other element in the grid a red background color

### Related resources
* [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

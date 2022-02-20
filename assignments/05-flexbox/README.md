# Introduction to Cascading Style Sheets (CSS)

## Flexbox and Grid
Is a "recently" introduced addition to CSS. It is an efficient and intuitive way of structuring and laying out elements.
It even makes it easy to center anything both vertically and horizontally, aka as the holy grail of css.

To use flexbox or grid, the element container you want to behave as a flexbox should be marked as `display: flex` or `display: grid` respectively.
E.g. 

```css
  .box {
    display: flex;
  }
  .grid {
    display: grid;
  }
```

Please look at the related resouces.

## Changes to implement
* This assignment can be done without changing any HTML, so please try to do this inside sheet.css.
* Below the assignments are related resources, open them up before starting.

1. We have introduced a sidebar to our page. It does not look quite right. Change it so the elements inside flows downwards, instead of to the right. 
<details>
  <summary>Hint</summary>
  `direction: xxx`...
</details>
2. Now things look better, can you make all the content inside the sidebar align to the bottom, but keep the heading at the top?
<details>
  <summary>Hint<summary>
  `margin-xxx: xxxx`
</details>
3. The sidebar does not look good on mobile, combine your knowledge of media queries and grid to align the sidebar under the article.

### Related resources
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)


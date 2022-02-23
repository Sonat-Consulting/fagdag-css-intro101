# Introduction to Cascading Style Sheets (CSS)

## Flexbox
Flexbox is a "recently" introduced addition to CSS. It is an efficient and intuitive way of structuring and laying out elements.
It even makes it easy to center anything both vertically and horizontally, aka as the holy grail of css.

To use flexbox, the element container you want to behave as a flexbox should be marked as `display: flex` .
E.g. 

```css
  .box {
    display: flex;
  }
```

For further information about flexbox, please look at "A Complete Guide to Flexbox" at the bottom, for an in depth explanation of all the features of flexbox.

## Changes to implement
* This assignment can be done without changing any HTML, so please try to do this inside sheet.css.
* Below the assignments are related resources, open them up before starting.

1. Chuck Norris decided he wanted the `aside` to be a sidebar. It does not look quite right.
Change it so the elements inside flows vertically, instead of horizontally. 
<details>
  <summary>Hint</summary>
  `Change the "flex-direction"`
</details>
2. The text of the sidebar now probably looks a bit cramped. Try to make the text not wrap to a new line.
<details>
  <summary>Hint</summary>
  `Use the white-space attribute. Also min-width probably works fine for this exercise.`
</details>
3. Now things look better, can you make all the content inside the sidebar align to the bottom, but keep the heading at the top
Not sure it looks better this way, but that's not the point ;)
<details>
  <summary>Hint</summary>
  `Use margin auto`
</details>
4. The sidebar does not look good on mobile, combine your knowledge of media queries and flexbox to align the sidebar under the article.

### Related resources
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)


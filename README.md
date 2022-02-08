# fagdag-css-intro101

## Introduction to Cascading Style Sheets (CSS)

#### What is it
* CSS defines how HTML elements should be rendered for the end user.
* CSS can be used for prints, webpages or other compatible media.

#### Where can I use it
* It can be embedded in a single page
* You can use an external stylesheet referenced
* Inline styling is possible

#### Why should I use it
* CSS is a good way to control the layout of several web pages all at once
* Using CSS in a good way promotes less messy HTML

## CSS Selectors
To be able to select what you want to define in CSS, we use selectors.


Lets say you have these paragraphs:
```
<p>Salmon is good</p>
<p class="orange">Orange is orange</p>
<p id="tomato">Tomatoe</p>
```

With selectors you have many ways of targeting them, for instance:

```
p {
  color: white;
}

p:first-of-type {
  border-left: 6px solid red;
  background-color: salmon;
}

.orange {
  border-left: 6px solid red;
  background-color: orange;
}

#tomato {
  border-left: 6px solid red;
  background-color:Tomato;
}
```

### When to target use id, class or tag name?
Looking at this cheatsheet, you can consider how to go about your selectors:

| Selector | Unique | Repetative | Custom | Example |
|---|---|---|---|---|
| ID | x | - | x | #footer {} |
| Class | - | x | x | .header {} |
| Tag | - | x | - | div {} |

* HTML5 does make it possible to create custom tags - this tutorial will use common tags.

### Assignments
* [01 - CSS Selectors](https://github.com/Sonat-Consulting/fagdag-css-intro101/tree/main/assignments/01-selectors) 
* [02 - Colors and units](https://github.com/Sonat-Consulting/fagdag-css-intro101/tree/main/assignments/02-colors-and-units) 
* [03 - Fonts](https://github.com/Sonat-Consulting/fagdag-css-intro101/tree/main/assignments/03-fonts) 

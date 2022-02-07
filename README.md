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
Selectors in CSS can be targeted by selector name, id or class.
Id should be unique in each rendered DOM, class and tag can be repeated.

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

| Selector | Unique | Repetative | Custom |
|---|---|---|---|
| ID | x | - | x |
| Class | - | x | x |
| Tag | - | x | - |

While the table does say tags are not custom, it is possible to create custom tags in HTML5.
But for the sake of this tutorial we will just make examples of common and predefined HTML tags.

### Assignments

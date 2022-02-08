# Introduction to Cascading Style Sheets (CSS)

## Fonts and font families
Browser support for fonts vary, this means what you design on your computer may not look so smashing everywhere.

* Web-Safe-Fonts
  * These are the fonts you can count on every browser (even IE) has support for.
  * A bit boring selection
* Font-family 
  * Use font-family with font-stacking instead of just one font.
    * Gives a controlled experience with fallback options.
  * Browsers will traverse through the list if they dont find the first fonts.
* Third party fonts
  * Not all fonts will support every character set out there
  * Some third party fonts are "self-hosted", whereas others can also be included via @import
    * @import url("https://fonts.googleapis.com/css?family=font-name");


## Changes to implement
* This assignment can be done without changing any HTML, so please try to do this inside sheet.css.
* Below the assignments are related resources, open them up before starting.

1. Please add font-family to the CSS selector html
   * Add 3 of your preferred fonts to the font-family
2. Chuck Norris called again (have to change my number I guess...)
   * He wants to have a professional image by having the footer of the page using these for font-family: 
     * 'Comic Sans MS', 'Chalkboard SE', 'Comic Neue', sans-serif 

### Related resources
* [W3c font-family](https://www.w3schools.com/cssref/pr_font_font-family.asp)
* [Web-safe fonts](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals#web_safe_fonts)

### Assignments
When you are done with this assignment, please move along to assignment [04 - Animations](https://github.com/Sonat-Consulting/fagdag-css-intro101/tree/main/assignments/04-animations).

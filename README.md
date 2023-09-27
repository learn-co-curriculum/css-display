# CSS Display

## Learning Goals

- The default display behavior of different elements.
- How to adjust the way an element displays.

## Introduction

This lesson will discuss the way different elements will display in the browser.
We will focus on the difference between inline and block elements, as well as
how to change the display property.

Make sure to check out the code example in the Resources section to see how
these properties work!

## Element Display: Block Kings & Inline Hippies

All elements in the browser have a default display behavior. We will focus on
the two most common, inline and block. Later lessons demonstrate other display
values such as table and table-cell among others.

### Block Elements

Block level elements are king of the horizontal space, meaning they take up all
of the horizontal space by default. They stretch 100% wide unless we set the
`width` property to something else. They always stack vertically by default.
Their height can bet set, but by default they will scale to the height of their
inner content. Some examples of commonly used block elements are:

```html
<div>...</div>
<h1>...</h1>
<h2>...</h2>
<h3>...</h3>
<h4>...</h4>
<h5>...</h5>
<h6>...</h6>
<p>...</p>
<ul><li>...</li></ul>
<ol><li>...</li></ol>
```

### Inline Elements

Inline level elements are peaceful hippies, they coexist side by side sharing the
horizontal space. They can't have a width or top and bottom margins set on them.
Their size will only be as wide and tall as their inner content. Some examples
of commonly used inline elements are:

```html
<img>
<a>...</a>
<span>...</span>
<input>
```

### Display Property

We can set the `display` property to adjust the way an element displays
(overriding its default display).

`display: inline`

`display: block`

For example we could set a div to display inline or a span to display block thus
changing their default orientation.

## Conclusion

In this lesson, you have learned about the different ways of controlling how
elements are displayed using CSS. To summarize:

- All elements in the browser have a default display value.
- Block elements stack vertically. They are 100% wide by default and accept
  width values so you can set their width. They also accept margin on all sides.
- Inline elements stack horizontally and ignore width and margin values. They
  are only as wide and tall as their content.
- We can set teh display property on elements to either: `inline` or `block` to
  change their default display to another set of rules.

## Resources

- [Display Property - Code Example](http://jsfiddle.net/flatiron_school/352A6/1/)
- [MDN - CSS - Display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)

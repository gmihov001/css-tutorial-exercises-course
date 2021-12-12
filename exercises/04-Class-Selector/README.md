---
tutorial: "https://www.youtube.com/watch?v=RffCSMXgWFc"
---

# `04` Class Selector

There are many ways to select HTML elements to apply styles to them.

So far we have only used the `tag` selectors, which are very limited because they apply their rules to EVERY tag of that type, as you saw in the previous exercise.

Next we will talk about the `.class` selector.

#### 1) Html `class` attribute

It is the most popular css selector - you will use it most of the time. 

The reason for that is because class selectors are very versatile and reusable - you can choose where to apply a class selector by giving speicific html elements the attribute `class`, like this:

```html
<span class="small">
    I am some text with size 9px
</span>    

```

#### 2) Css `.class` selector

Use the value of the `class` attribute of any HTML element to select it. Styling rules will apply to all elements with the same class value:

```css
.small{
    font-size: 9px;
}
```
**Note:** 

Any html tag with the attribute `class="small"` will have a font-size of 9px.

# 📝 Instructions:

Right now there is a class selector in the CSS that is called `.b-blue`. 

1. Observe your css file
2. Apply the existing rule to both `<p>` tags in the HTML document, by applying the appropriate class to them.



---
tutorial: "https://www.youtube.com/watch?v=9906LCSQJ8M"
---

# `04.3` The ID CSS Selector

Even though it is generally not advised (see below), you can also select an element by using an `#id` attribute to apply stiles. 

IDs should be unique - only one html element in your page should can have the same ID.

In the example below, we have selected the id `my_number_one` to apply font size of 9px to an html element with the attribute `id="my_number_one"`.


```css
#my_number_one {
    font-size: 9px;
}
```

# 📝 Instructions:

Following the example, add the id `button1` to the `<span>` tag and compile to check the result in your browser.


Use the `id` property of the HTML element to select it. `Ids` should be unique, only one element must have the same ìd`.

 Generally IDs are not ideal for CSS selectors. You can find out why in the article below:

 https://dev.to/clairecodes/reasons-not-to-use-ids-in-css-4ni4

 Instead, we normally use a combination of classes and specificity to apply our css rules.


---
tutorial: "https://www.youtube.com/watch?v=3JxXkhxyAnI"
---

# `05` Specificity

When creating a CSS document, you can start from the most generic selectors and end with the most specific ones, because CSS gives higher priority to rules that are written further down in the CSS stylesheet. 

To be more precise though, we use something called **specificity**, which means that:

**The more specific the selector - the higher priority it has** 

In the following example, a div with `id='thirditem'` will end up having blue background, because the rule with id selector `#thirditem` is more specific, than the rule with a tag selector `div`, even though the latter is further down in the stylesheet: 

```css
    #thirditem {
        background: blue;
    }

    div {
        background: yellow;
    }
```

## 📝 Instructions:

1. Override the background color of the element with id `thirditem` without changing the existing css code. Instead, add to the css stylesheet a more specific rule at the end of the document to override its background color to `yellow`.


### 💡 Hint:

Use the id as a selector.

There are cases in which you can use the **!important** annotation:
https://css-tricks.com/when-using-important-is-the-right-choice/

However most of the time that is not the best approach. 



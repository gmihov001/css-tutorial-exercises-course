---
tutorial: "https://www.youtube.com/watch?v=3JxXkhxyAnI"
---

# `05.2` Advanced Specificity

You can think of the weight of every selector in term of numbers:

- a tag selector (like `div`) only has weight of 1 point
- a class selector (like `.someclass`) has weight of 10 points
- an id selector (like `#thirditem`) has weight of 100 points

In advanced selectors, the points cumulate. Therefore:

```css
    div {
        min-width: 20vw;
    }

    div 
```


## 📝 Instructions:

1. Override the `background-color` of `#thirditem` without deleting any css code. Simply add to your css a more specific rule at the end of the document to override `background-color` to `green`.


### 💡 Hint:

There are cases in which you can use the **!important** annotation:
https://css-tricks.com/when-using-important-is-the-right-choice/

However most of the time that is not the best approach. 



---
tutorial: "https://www.youtube.com/watch?v=3JxXkhxyAnI"
---

# `05.1` Advanced Specificity

You can think of the weight of every selector in term of numbers:

- a tag selector (like `div`) only has weight of 1 point
- a class selector (like `.someclass`) has weight of 10 points
- an id selector (like `#thirditem`) has weight of 100 points

In advanced selectors, the points cumulate. Therefore in the example below, the selector `#myItem` carries 100 points specificity, while the selector `div #myItem` carries 101 points specificity and will override the lower rule.

```css
    div #myItem {  
        min-width: 20vw;
    }

    #myItem {
        min-width: 30vw;
    }
```


## 📝 Instructions:

1. Override the `color` property of the element with id `fastest` without deleting any css code. You can only add a new rule at the beginning of the CSS document to override the `color` to `red`.


### 💡 Hint:

Remember to use higher specificity that the existing rules. The more selectors you combine the higher the specificity gets, because each selector adds additional points to your rule.  


---
tutorial: "https://www.youtube.com/watch?v=3JxXkhxyAnI"
---

# `05.2` !important

There are cases in which you can use the **!important** annotation:
https://css-tricks.com/when-using-important-is-the-right-choice/

It is very powerful and it will override ALL other conflicting rules including those with higher specificity. Because of that though, it creates precedences in your code and is not the best solution. Many professional teams discourage it.

Try to take better advantage of specificity instead. 


## 📝 Instructions:

1. Build the exercise and observe that the `#thirditem` selector creates green background because it has higher specificity.

2. Override the green background color from the `#thirditem` selector by forcing the first rule to take precedence and keep its blue background.


### 💡 Hint:

Use the `!important` annotation in the background property of the first rule. 

Remember to not make a habit of using this approach. It is most useful for testing purposes in the Inspector feature of your browser. 


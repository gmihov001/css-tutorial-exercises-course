# `12` Relative Length em, rem

By now, we are used to working with pixels as measurement unit, for example, saying that a box has `100px` of width. 

You also saw the `vh` and `vw` units in a previous exercise, which are *relative* to the ***viewport*** (corresponding to the size of your browser windows).

Relative units of measure are more superior than fixed units like pixels, because they help the website be more *responsive*, i.e. to adjust to the size of the screen.

There are other types of units that are ***relative*** - `em` and `rem`. 

We use them when we want the size of an element to be related to another element or measurement unit.

## Example using em:

In this exercise we have two `<h2>` headings. They are both `<h2>`, but one is bigger than the other because headings have relative font-sizes by default. 

Since the first `div` has a bigger based `font-size`, then the heading resizes accordingly.

em: Relative to the current font-size of the parent.

rem: Relative to the original font-size of the page.


## 📝 Instructions:

1. Give a `font-size` of `0.8em` to both `h2`'s

2. Now give a `font-size` of `0.8rem` to both `h3`'s


## The result should look like this:

![Example Image](../../.learn/assets/12-1.png?raw=true)



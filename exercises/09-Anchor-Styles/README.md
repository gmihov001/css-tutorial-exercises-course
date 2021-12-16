# `09` 3D Anchor Styles

People like to feel that they are clicking on something - a great approach to accomplish that is by faking a 3D effect. To do so, designers normally play with the borders, for example:

![Example Image](../../.learn/assets/09-1.png?raw=true)

You can control what css rules apply to each state of an anchor by using the `:hover` (for mouse hover) or `:active` (for mouse pressing) selectors, example:

```css
a:active {
  /* here you can specify whatever css rule that applies
  to the anchor while being 'pressed' */
}
```

## 📝 Instructions:

1. Change the border colors and apply shadow to the anchor, whenever it is being pressed, to the following:

```css
border-color: #000 #aaa #aaa #000;
box-shadow: 0 3px 5px gray;
```

2. Understand the values of the box-shadow property:
https://www.w3schools.com/css/css3_shadows_box.asp 

# Padding Property:
The CSS `padding` properties are used to generate space around an element's content, inside of any defined borders.

Here’s an easy-to-understand definition for padding properties in CSS:

* `Padding-top:` Adds space **inside** the element, above the content.
Think of it as creating space **below the top edge** of the element.
* `Padding-bottom:` Adds space **inside** the element, below the content.
It creates space `above the bottom edge` of the element.
* `Padding-left:` Adds space **inside** the element, to the left of the content.
It creates space **to the right of the left edge** of the element.
* `Padding-right:` Adds space **inside** the element, to the right of the content.
It creates space **to the left of the right edge** of the element.

# 1. Padding Shorthand
The **padding shorthand** in CSS is similar to the margin shorthand and is used to set padding for all four sides of an element (inside spacing between content and the element's border).
### Syntax:
```
padding: [top] [right] [bottom] [left];
```
### 2. Value Patterns:
### 2.1. One Value:
Applies the same padding to **all four sides.**
```
padding: 10px; /* Top, Right, Bottom, Left = 10px */
```

### 2.2. Two Values:
First value = **Top and Bottom,** Second value = **Left and Right.**
```
padding: 10px 20px; /* Top/Bottom = 10px, Left/Right = 20px */
```

### 2.3. Three Values:
First value = **Top,** Second value = **Left and Right,** Third value = **Bottom.**
```
padding: 10px 20px 30px; /* Top = 10px, Left/Right = 20px, Bottom = 30px */
```

### 2.4. Four Values:
Values are applied in a **clockwise direction: Top → Right → Bottom → Left.**
```
padding: 10px 20px 30px 40px;
/* Top = 10px, Right = 20px, Bottom = 30px, Left = 40px */
```

### Example: 
```
.element {
  padding: 10px 20px 30px 40px;
}
```
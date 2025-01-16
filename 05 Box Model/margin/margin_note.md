# Margin Property:
**Margin** are used to create space around elements or outer surface of the elements (section) of the border.

# 1. Margin Sides - Individual Sides
CSS has properties for specifying the **margin** for each side of an element:
### Syntax:
* `margin-top:`
* `margin-right:`  
* `margin-bottom:`
* `margin-left:` 

# 2. Margin Shorthand
The `margin shorthand` in CSS is a quick way to define margins for all four sides of an element (top, right, bottom, and left) in a single line.  
### Syntax:
```
margin: [top] [right] [bottom] [left];
```

### Shortcut:
The `margin` shorthand can be used to set all these in one line:
```
margin: top right bottom left;
```
### Example 1
```
margin: 10px 20px 30px 40px;

```
* 10px → Top
* 20px → Right
* 30px → Bottom
* 40px → Left

# 3.  Value Patterna:
### 3.1. One Value:
Applies the same margin to `all four sides.`
```
margin: 10px; /* Top, Right, Bottom, Left = 10px */

```

### 3.2. Two Values:
First value = `Top and Bottom,` Second value = `Left and Right.`
```
margin: 10px 20px; /* Top/Bottom = 10px, Left/Right = 20px */
```

### 3.3. Three Values:
First value = `Top,` Second value = `Left and Right,` Third value = `Bottom.`
```
margin: 10px 20px 30px; /* Top = 10px, Left/Right = 20px, Bottom = 30px */
```

### 3.4. Four Values:
Values are applied in a `clockwise direction: Top → Right → Bottom → Left.`
```
margin: 10px 20px 30px 40px; 
/* Top = 10px, Right = 20px, Bottom = 30px, Left = 40px */
```

### Example
```
.element {
  margin: 10px 20px 30px 40px;
}
```


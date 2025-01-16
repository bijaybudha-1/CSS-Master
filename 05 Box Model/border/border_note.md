# Border Property
The CSS border properties allow you to specify the style, width, and color of an element's border.

# 1. CSS Border Style
The border-style property specifies what kind of border to display.

The following values are allowed:

* `dotted` - Defines a dotted border
* `dashed` - Defines a dashed border
* `solid` - Defines a solid border
* `double` - Defines a double border
* `groove` - Defines a 3D grooved border. The effect depends on the border-color value
* `ridge` - Defines a 3D ridged border. The effect depends on the border-color value
* `inset` - Defines a 3D inset border. The effect depends on the border-color value
* `outset` - Defines a 3D outset border. The effect depends on the border-color value
* `none` - Defines no border
* `hidden` - Defines a hidden border

# 2. Border Width
The `border-width` property specifies the width of the four borders.
### Syntax:
### Example
```
h1 {
    border-width: 5px;
}
```

# 3. Border Color
The `border-color` property is used to set the color of the four borders.
### Syntax:
### Example 1
```
h1 {
    border-style: solid;
    border-color: black;
}
```
### Example 2
```
h2 {
    border-style: dotted;
    border-color: rgb(0,0,0);
}
```
### Example 3
```
p {
    border-style: dashed;
    border-color: #000;
}
```

# 4. Border Sildes - Individual Sides
In CSS, there are also properties for specifying each of the borders (top, right, bottom, and left):
### Syntax:
### Example 1
```
p {
    border-top-style: dashed;
}
```
### Example 2
```
div {
    border-right-style: solid;
}
```
### Example 3
```
h1 {
    border-bottom-style: dotted;
}
```
### Example 4
```
h3 { 
    
    border-left-style: double;
}
```

# 5. Border Shorthand Property
The `border` property is a shorthand property for the following individual border properties:
* `border-width`
* `border-style`
* `border-color`
### Syntax:
### Example 1
```
p {
    border: 5px solid black;
}
```
### Example 2
```
h1 {
    border: 10px dashed red;
}
```

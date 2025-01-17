# CSS Gradient
A gradient is a smooth transition between two or more colors, often used as backgrounds in CSS.

# Types of Gradients
### 1. Linear Gradients
Colors transition in a straight line. Default direction of linear-gradient is to Top to bottom.

### 2. Direction (Linear):
### Syntax:
* `to right`, `to left`, `to top`, `to bottom`.
* __Angles:__ `45deg`, `90deg`, etc.

```
background: linear-gradient(direction, color1, color2);
```
### Example 1:
```
background: linear-gradient(to right, red, yellow);
```
### Example 2:
```
background: linear-gradient(90deg, red, blue);
```

### 2. Radial Gradient: 
Colors transition outward in a circular or elliptical shape.
### Syntax:
```
background: radial-gradient(shape, color1, color2);
```
### Example 1: 
```
background: radial-gradient(circle, red, yellow);
```
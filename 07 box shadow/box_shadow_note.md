# Box Shadow
`box-shadow` adds shadow effects to elements, giving them depth and a 3D look.

### Shadow
```
box-shadow: offset-x offset-y blur-radius spread-radius color;
```
* __offset-x:__ Horizontal shadow (positive → right, negative → left).
* __offset-y:__ Vertical shadow (positive → down, negative → up).
* __blur-radius__ (optional): Makes the shadow softer.
* __spread-radius__ (optional): Increases or decreases the shadow size.
* __color:__ Defines the shadow color (e.g., black, rgba()).

__Examples:__
__Basic Shadow:__
```
box-shadow: 5px 5px 10px gray;
```
__Inside Shadow(Inside the Element):__
```
box-shadow: inset 5px 5px 10px gray;
```
__No Blur or Spread:__
```
box-shadow: 5px 5px 0 black;
```
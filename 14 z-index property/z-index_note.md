# z-index Property
The `z-index` property controls the **stacking order** of elements on a webpage. Elements with a higher `z-index` appear in front of those with a lower `z-index`.

### Some key points:
__1. Default Value__: `auto` (element stacks based on the order in the DOM).
__2. Only Works on Positioned Elements__: The element must have a `position` value other than `static` (e.g., `relative`, `absolute`, `fixed`).
__3. Higher Value = Higher Priority__: Elements with a higher `z-index` will overlap others.

### Syntax: 
```
element {
  z-index: 1; /* Specify the stacking order */
}
```

### Example:
```
<div style="position: relative; z-index: 1;">Box 1</div>
<div style="position: relative; z-index: 2;">Box 2 (appears on top)</div>
```
* __Box 2__ appears above __Box 1__ because `z-index: 2 > 1`.

### Quick Notes:
* __Positive Values__: Bring elements forward.
* __Negative Values__: Push elements backward.
* Use with `position` to make it effective.
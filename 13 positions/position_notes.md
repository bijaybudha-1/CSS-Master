# CSS Position Property
The `position` property defines how an element is positioned in the document and its relationship with other elements.

# Common Position Values:
### 1. Static (default):
* Elements are positioned in the normal document flow.
```
position: static;
```

### 2. relative (`position: relative`):
__Defination__:
* The element is positioned __relative to its normal position__ in the document flow.
* It __stays in the flow__, so it doesn't affect the positions of sibling elements.
* You can use top, right, bottom, or left to adjust it.

__Use Case:__
* When you want to slightly adjust an element without removing it from the normal document flow.

__Example__:
```
div {
  position: relative;
  top: 20px; /* Moves 20px down */
  left: 10px; /* Moves 10px to the right */
}

```
* Moves the element but leaves its original space intact.

### 3. absolute (`position: absolute;`): 
__Definition__:
* The element is __positioned relative to the nearest positioned ancestor__ (an ancestor with `relative`, `absolute`, or `fixed` position).
* If no ancestor is positioned, it defaults to the `<html>` element.
* It is __removed from the document flow__, so it doesn't affect sibling elements.

__Use Case__:
* For precise placement inside a container or layout.

__Example__:
```
.container {
  position: relative;
}
.child {
  position: absolute;
  top: 10px; /* 10px from the top of the container */
  left: 20px; /* 20px from the left of the container */
}

```

* The `.child` is placed relative to `.container`.

### 4. Fixed (`position: fixed;`):
__Definition__:
* The element is positioned __relative to the viewport__ and does not move when scrolling.
* It is also __removed from the document flow__.

**Use Case**:
* For sticky headers, footers, or pop-ups that stay visible regardless of scrolling.

**Example**:
```
div {
  position: fixed;
  bottom: 0; /* Sticks to the bottom of the viewport */
  right: 0; /* Sticks to the right of the viewport */
}
```

### 5. Sticky (`position: sticky;`):
**Definition**:
* The element behaves like `relative` **until a specified scroll position is reached**, then it behaves like fixed.
* It sticks to its offset position (`top`, `left`, etc.) while within its container.

**Use Case**:
* For navigation bars or headers that stick at the top of the page while scrolling.

**Example**:
```
div {
  position: sticky;
  top: 0; /* Sticks to the top when scrolled to this point */
}
```
* The element sticks to the top and moves with its parent container's scroll.

# Key Differences:
|------------||------------------------------------||---------------||-----------------------|
| Property   ||         Position Reference         || Affects       ||      ScrollBehavior   |
|            ||                                    || Document Flow ||                       |
|------------||------------------------------------||---------------||-----------------------|
| Relatives  || Itself(normal position)            ||Yes            || Moves with the        |
|            ||                                    ||               || document.             |
|------------||------------------------------------||---------------||-----------------------|
|Absolute    || Nearest positioned ancestor        || No            || Moves with the        |
|            || (or `<html>`)                      ||               || ancestor.             |
|------------||------------------------------------||---------------||-----------------------|
|Fixed       || Viewport                           ||No             || Does not move (fixed).|
|------------||------------------------------------||---------------||-----------------------|
|Sticky      || Scroll position within the parent  ||Partially      || Moves until it        | 
|            ||                                    ||               || "sticks."             |
|------------||------------------------------------|| --------------||-----------------------|
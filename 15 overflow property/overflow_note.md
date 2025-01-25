# Overflow Property
The `overflow` property controls what happens to content that exceeds the size of its container.

# Common Values:
### 1. visible(default)
Content is not clipped and overflows the container.
```
overflow: visible;
```

### 2. hidden
Content is clipped, and the overflow is not visible.
```
overflow: hidden;
```

### 3. scroll
Adds scrollbars to the container, regardless of whether the content overflows.
```
overflow: scroll;
```

### 4. auto 
Adds scrollbars `only if` the content overflows.
```
overflow: auto;
```

# Example: 
```
div {
  width: 200px;
  height: 100px;
  overflow: hidden;
}
```

# Quick Notes:
* Use `hidden` for clean layouts.
* Use `auto` or `scroll` when content might overflow.
* Combine with `overflow-x` (horizontal) or `overflow-y` (vertical) for more control.
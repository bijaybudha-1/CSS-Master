# List Properties
CSS list properties style HTML lists (`<ul>`, `<ol>`, `<li>`), controlling appearance, markers, and positioning.

### Common List Properties:
__1. list-style-type__: Defines the marker style (e.g., bullets, numbers).
```
list-style-type: disc; /* Default bullet */
list-style-type: square; /* Square bullet */
list-style-type: decimal; /* Numbered list */
```

__2. list-style-position__: Specifies whether the marker is inside or outside the list item.
```
list-style-position: outside; /* Default, marker outside */
list-style-position: inside; /* Marker inside */
```
__3. list-style-image__: Replaces the marker with an image.
```
list-style-image: url('marker.png'); /* Custom marker image */
```

__4. list-style (Shorthand)__: Combines all list properties.
```
list-style: square inside url('marker.png');
```

__Example__:
```
ul {
  list-style: circle inside;
}
```
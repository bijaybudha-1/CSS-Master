# Anchor in CSS
The `<a>` tag creates hyperlinks, and CSS is used to style them for better design and usability.

### Anchor State (Pseudo-classes):
__1. a:link__: Styles an unvisited link.
```
a:link { color: blue; }
```

__2. a:visited__: Styles a link that has been visited.
```
a:visited { color: purple; }
```

__3. a:hover__: Styles a link when the mouse is over it. 
```
a:hover { color: red; }
```

__4. a:active__: Styles a link when it is clicked.
```
a:active { color: orange; }
```

__Example:__
```
a {
  text-decoration: none; /* Removes underline */
  color: black;          /* Default link color */
}

a:hover {
  color: green;          /* Changes color on hover */
}
```

# Quick Notes:
* __Order of States__: Always use __LoVe HA__ (Link → Visited → Hover → Active).
* Use `text-decoration: none;` to remove underlines.
* Combine states for interactive and attractive links.
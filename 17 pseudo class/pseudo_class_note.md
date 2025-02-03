# Pseudo-Classes in CSS
A pseudo-class in CSS is used to define a special state of an element. It allows you to style elements based on user interaction or their position in the document without modifying the HTML.

### Commonly Used Pseudo-Classes
__1. :hover__:
- Applies styles when the user hovers over an element.

**Syntax**:
```
button:hover {
    background-color: blue;
    color: white;
}
```

__2. :focus__:
– Styles an element when it is focused (like an input field).

__Syntax__:
```
input:focus {
    border-color: green;
}
```

__3. :first-child__:
– Targets the first child of a parent.

__Syntax__:
```
p:first-child {
    font-weight: bold;
}
```

__4. :last-child__:
– Targets the last child of a parent.

__Syntax__:
```
p:last-child {
    color: red;
}
```

__5. :nth-child(n)__:
– Selects elements based on their position in a parent (e.g., even, odd, specific number).

__Syntax__:
```
li:nth-child(odd) {
    background-color: lightgray;
}
```

__6. :not(selector)__: 
– Excludes elements that match the given selector.

__Syntax__:
```
div:not(.exclude) {
    background-color: yellow;
}
```
__7. :checked__:
– Styles checkboxes or radio buttons when selected.

__Syntax__:
```
input:checked {
    outline: 2px solid blue;
}
```

__8. :first-of-type__:
- Selects the first element of a specific type within a parent.
- Ignores other element types.

__✅ Example: Styles only the first <p> inside a <div>.__
```
p:first-of-type {
    color: blue;
    font-weight: bold;
}
```

__9. :last-of-type__:
- Selects the last element of a specific type within a parent.
__✅ Example: Styles only the last <p> inside a <div>.__
```
p:last-of-type {
    color: red;
    font-style: italic;
}
```
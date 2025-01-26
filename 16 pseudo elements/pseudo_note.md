# Pseudo Elements
Pseudo-elements allow you to style specific parts of an element without modifying the HTML structure.

# Common Pseudo-elements:
### 1. `::before`
* Inserts content **before** an element's content.
```
element::before {
  content: "Prefix - ";
}
```

### 2. `::after`
* Inserts content **after** an element's content.
```
element::after {
  content: " - Suffix";
}
```

### 3. `::first-letter`
* Styles the __first letter__ of an element.
```
element::first-letter {
  font-size: 2em;
  color: red;
}
```

### 4. `::first-line`
* Styles the __first line__ of an element.
```
element::first-line {
  font-weight: bold;
}
```

### 5. `::placeholder`
* Styles the placeholder text in input fields.

```
input::placeholder {
  color: gray;
  font-style: italic;
}
```

### Example:
```
h1::before {
  content: "👉 ";
  color: blue;
}
h1::after {
  content: " 👈";
  color: blue;
}
```

# Quicks Notes:
* Pseudo-elements are denoted by `::` (modern syntax, but `:` works for older browsers).
* They are commonly used for adding decorative content or highlighting specific text parts.
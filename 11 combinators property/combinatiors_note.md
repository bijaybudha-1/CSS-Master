# Combinators
Combinators in CSS define relationships between elements, helping you select and style elements based on their context in the HTML structure.

### Types of combinators:
__1. Descendant Combinator (` `)__:
* Selects all descendants of an element (any level).
```
div p {
  color: red;
}
```
* (Selects all `<p>` inside `<div>`)

__2. Child Combinator (`>`)__:
* Selects direct children of an element.
```
div > p {
  color: blue;
}
```
* (Selects `<p>` directly inside `<div>`)

__3. Adjacent Sibling Combinator (`+`)__:
* Selects the next sibling immediately after an element.
```
h1 + p {
  color: green;
}
```
* (Selects the first `<p>` after `<h1>`)

__4. General Sibling Combinator (`~`)__:
* Selects all siblings after an element.
```
h1 ~ p {
  color: purple;
}
```
* (Selects all `<p>` after `<h1>`)

# Quick Notes:
* Combinators help target elements efficiently.
* Combine with classes or IDs for precise styling.
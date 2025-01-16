# Box Model
The `CSS Box Model` describes how elements are structured and spaced on a webpage. It consists of the following layers:

### 1. Content: 
* The inner part of the box where text, images, or other content resides.
* Example: `width` and `height` define the size of this area.

### Padding: 
* Space between the content and the border.
* Adds breathing room __inside__ the element.

### Border: 
* The edge that wraps around the padding and content.
* You can style it (e.g., color, width, dashed, etc.).

### Margin: 
* Space **outside** the border, separating the element from other elements.
* Creates distance between elements.

```
+---------------------+ <- Margin
|    Border           |
|  +-------------+    |
|  |  Padding    |    |
|  | +---------+ |    |
|  | | Content | |    |
|  | +---------+ |    |
|  +-------------+    |
+---------------------+ <- Margin
```
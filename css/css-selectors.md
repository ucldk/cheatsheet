## Tag selectors

You can always choose an element based on its tag. This works for any tag.

```css
div {
   color: blue;
}
```

## Class selectors

Elements can be selected by class reference. Remember, the class reference can be reused throughout the document.

```html
<div class="my-class"></div>
```

```css
.my-class {
   color: blue;
}
```

## ID selectors

Elements can be selected by ID reference. Remember, the ID reference can only be used once throughout the document.

```html
<div id="my-id"></div>
```

```css
#id {
   color: blue;
}
```

## Attribute selectors

Elements with specific attributes can be selected too.

```html
<input type="text">
```

```css
[type] {
   color: blue;
}

[type="text"] {
   color: red;
}
```

## Pseudo selectors

### :first-child

Selects first element in range

```css
li:first-child {
   color: blue;
}
```

### :last-child

Selects last element in range

```css
li:last-child {
   color: blue;
}
```

### :hover
Highlights when element is hovered

```css
a:hover {
   color: blue;
}
```

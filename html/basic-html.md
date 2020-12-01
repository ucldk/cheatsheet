This cheatsheet is a list of commonly used HTML tags.

## Basic HTML document

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    
  </body>
</html>
```

## Text Formatting

| Tag | Description |
| - | - |
| `<h?>Heading</h?>` | Heading tag, h1 for largest to h6 for smallest |
| `<p>Paragraph</p>` | New paragraph or text block |
| `<b>Bold text</b>` | Bold text |
| `<u>Underline text</u>` | Underline text |
| `<i>Italic text</i>` | Italic text |
| `<br>` | Line break / new line |
| `<ul><li>List item</li></ul>` | Unordered list |
| `<ol><li>List item</li></ol>` | Ordered list |

## Semantic tags

| Tag | Description |
| - | - |
| `<article></article>` | A self-contained part of a website. |
| `<aside></aside>` | Element with indirect relation to documents main content |
| `<footer></footer>` | Represents a footer for its parent sectioning content. E.g. body, article, aside, nav, section |
| `<header></header>` | Represents a header for its parent sectioning content. E.g. body, article, aside, nav, section |
| `<hgroup></hgroup` | A group of multilevel headers. |
| `<main></main>` | The main content of the specific site on the website |
| `<nav></nav>` | Represents a navigation on the website. |
| `<section></section` | A standalone section, which does not have more specific elements to represent it |

## Generic tags

| Tag | Description |
| - | - |
| `<div></div>` | Division block element, is used when other semantic blocks does not make sense |
| `<span></span>` | Span inline element, is used to format something specific for text etc. |

## Media tags

| Tag | Description |
| - | - |
| `<img src="path/to/image.png" alt="Alt text">` | Embeds an image element into the document/page |
| `<video><source src="path/to/video.mp4" type="video/mp4"></video>` | Embeds a video element into the document/page |
| `<audio src="path/to/audio.mp3"></audio>` | Embeds a audio element into the document/page |

## Links

| Tag | Description |
| - | - |
| `<a href="https://example.com">Website</a>` | A basic link |

## Forms

| Tag | Description |
| - | - |
| `<form method="post" action="path/to/location.php"></form>` | The container to hold the form |
| `<input type="text" name="inputName">` | The input field, can hold multiple types like: text, password, email, date etc. |
| `<select name="inputName"><option>Value 1</option><option>Value 2</option></select>` | The select field to choose from a drop down list |
| `<textarea name="inputName">The value of text area</textarea>` | A larger multiline text input |


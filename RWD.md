# HTML Labels

## with closing tag

`<h1>`

`<p>` is used to create a paragraph of text on websites

`<!-- -->`: comment

`<main> </main>`: identify different content areas, make your HTML easier to read and help with SEO to accessability

`<ul> </ul>`
  - `<li> </li>`
`<ol> <ol>`

`<em> </em>`
`<strong> </strong>`: used to indicate that some text is of strong importance or urgent.

## without closing tag

`<img>`

- attribute:
  - `src`
  - `alt`
  - `target`
    - _blank 

`<figure>`

`<hr>`: element to display a divider between sections of different content.


# box-sizing
- `box-sizing` is used to set this behavior. By default, the `content-box` model is used. With this model , when an element has a specific width, that width is calculated based only on the element's content. Padding the border values get added to the total width, so the element grows to accommodate these values.

# flex-direction
Flexbox has a main and cross axis. The main axis is defined by the flex-direction property, which has four possible values:

row (default): horizontal axis with flex items from left to right
row-reverse: horizontal axis with flex items from right to left
column: vertical axis with flex items from top to bottom
column-reverse: vertical axis with flex items from bottom to top
Note: The axes and directions will be different depending on the text direction. The values shown are for a left-to-right text direction.

# flex-wrap
The flex-wrap property determines how your flex items behave when the flex container is too small. Setting it to wrap will allow the items to wrap to the next row or column. nowrap (default) will prevent your items from wrapping and shrink them if needed.

# object-fit
Notice how some of your images have become distorted. This is because the images have different aspect ratios. Rather than setting each aspect ratio individually, you can use the object-fit property to determine how images should behave.

Give your .gallery img selector the object-fit property and set it to cover. This will tell the image to fill the img container while maintaining aspect ratio, resulting in cropping to fit.

# `::after`
The `::after` pseudo-element creates an element that is the last child of the selected element. You can use it to add an empty element after the last image. If you give it the same `width` as the images it will push the last image to the left when the gallery is in a two-column layout. Right now, it is in the center because you set `justify-content: center` on the flex container.

Example
```css
.container::after {
  content: "";
  width: 860px;
}
```


# rem units
rem units stands for `root em`, and is relative to the font size of the `html` element

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

# CSS

`<div>` : the `<div>` element is used mainly for design layout purposes unlile the other content elements you have used so far

## Selector
id use `#`
class use `.`

## Color
- rgb
  - `rgb(0, 0, 0)`
- hex
  - #4B5320
  - `0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F`
  - `#00FF00 = rgb(0 ,255, 0)`
- HSL
  - `hsl(240, 100%, 50%)`

## linaer-gradient
- `linear-gradient(90deg, color1, color2, ..)`
- `linear-gradient(90deg, red 90%, black)`
- If no gradientDirection argument is provided to the linear-gradient function, it arranges colors from top to bottom, or along a 180 degree line, by default.

```css
.red(
    background: linear-gradient(90deg, )
)
```

## rgba
the a is ==opacity==

if two block elements are next to each other, they stack like actual blocks

## border-left
`border-left` = `border-left-width` + `border-left-style` + `border-left-color`

## box-shadow
`box-shadow: offsetX offsetY blurRadius color`
Here's how the offsetX and offsetY values work:

- both offsetX and offsetY accept number values in px and other CSS units
- a positive offsetX value moves the shadow right and a negative value moves it left
- a positive offsetY value moves the shadow down and a negative value moves it up
- if you want a value of zero (0) for any or both offsetX and offsetY, you don't need to add a unit. Every browser understands that zero means no change.

### want to expand shadow out further
`spreadRadius`
`box-shadow: offsetX offsetY blurRadius spreadRadius color;`



# vh 
the `vh` unit stands for viewport height, and is relative to `1%` of the `hegiht` of the viewport

# rem
The `rem` unit stands for root `em`, and is relative to the font size of the `html` element
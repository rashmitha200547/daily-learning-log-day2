**Day 2 CSS**

## What is CSS?
CSS (Cascading Style Sheets) is used to style and design HTML content — colors, fonts, spacing, layout, and positioning. HTML gives structure, CSS gives appearance.

## Ways to Add CSS
1. Inline CSS — written directly inside an HTML tag: `style="color: blue;"`
2. Internal CSS — written inside a `<style>` tag in the `<head>`
3. External CSS — written in a separate `.css` file and linked using `<link rel="stylesheet" href="style.css">` most commmonly used.

External CSS is the most preferred — keeps HTML and styling separate and reusable.

## Basic CSS Syntax
selector { property: value; }

Example: `h1 { color: red; font-size: 24px; }`

## Selectors
- Element selector: `p { }` — selects all `<p>` tags
- Class selector: `.box { }` — selects elements with class="box"
- ID selector: `#header { }` — selects element with id="header"
- Universal selector: `* { }` — selects all elements

## Common CSS Properties
- `color` — text color
- `background-color` — background color
- `font-size` — size of text
- `font-family` — font type
- `text-align` — align text (left, center, right)
- `margin` — space outside an element
- `padding` — space inside an element, around content
- `border` — adds a border around an element
- `width` / `height` — size of the element

## The Box Model
Every HTML element is a box made up of:
1. Content — the actual text/image inside
2. Padding — space between content and border
3. Border — the line around the padding
4. Margin — space outside the border, separating it from other elements

## Flexbox (for layout)
Flexbox makes it easy to align and arrange items in a row or column.
- `display: flex` — turns on flexbox for that container
- `justify-content` — aligns items horizontally
- `align-items` — aligns items vertically

## Colors in CSS
Colors can be written as:
- Name: red
- Hex code: #ff0000
- RGB: rgb(255, 0, 0)

## Units in CSS
- px — fixed pixel size
- % — relative to parent element
- em / rem — relative to font size

## Key Takeaways
- CSS controls how HTML looks — colors, spacing, layout
- External CSS is best practice for real projects
- The box model (content, padding, border, margin) is the foundation of layout
- Flexbox is one of the easiest ways to align elements on a page

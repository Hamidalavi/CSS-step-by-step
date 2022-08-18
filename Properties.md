# Properties

## Image and Color

- `background: color/hex code/rgb(a)/url("path")`: Change the background of content.
- `background-color: color/hex code/rgb(a)`: Change the background color of content.
- `background-image: url("path")`: Change the background image of content.
- `background-size: unit unit/unit cover contain`: Specifies the size of the background images.
- `background-repeat: value`: Specifies how background images are tiled after they have been sized and positioned.
- `background-position: unit unit`: Allows us to set the initial position.
- `background-origin: value`: Allows us to set a background positioning area.
- `background-clip: value`: Defines where the image should be clipped if necessary.
- `background-attachment`: Defines how the scrolling will behave inside of that image.
- `box-shadow: x-axis-pos y-axis-pos blurriness spread/width color`: Uses shadow behind an element.

## Fonts and Text

- `font-family: font`: Changes the font.
- `font-weight: light/bold`: We can make the font bold and thin.
- `font-style: style`: Allows italic or oblique faces to be selected.
- `font-size: size/unit`: Changes the font size.
- `font-variant: variant`: Specifies variant representations of the font (lower-case or upper-case).
- `letter-spacing: value`: Specifies the minimum, maximum, and optimal spacing between letters.
- `white-space: value`: Changes the way of text in lines and spaces.
- `line-height: value`: Let's us define the top and the bottom of our content box (space between top and bottom - inline box).
- `text-align: alignment`: Align the text to the left/center/right position.
- `vertical-align: alignment`: Align the text to the top/middle/bottom position.
- `text-decoration: decoration style`: Decorations applied to font used for an element's text.
- `text-shadow: x-axis-pos y-axis-pos blurriness color`: Enables shadow effects to be applied to the text of the element.
- `text-transform`: Applies the uppercase/lowercase/capitalize values.
- `list-style: style`: To set the list style (number, bullet and more). It's used for `ul` unordered lists. It's not work when the list items (i.e. `li` in `inline` or `inline-block` level).
- `color: color/hex code/rgb(a)/ hsl(a)`: Change the color of text.
- `color: currentColor`: Gets the element color and sets this color to related part (`border-color`, `background-color` and etc).
- `shape-outside: shape(unit at unit unit)`: Changes the shape of the elements when the image near them, for example `shape-outside: circle(80px at 50% 50%);`.
- `shape-margin: unit`: Applies margin for shaped text.

## Box Model

- `width: unit unit`: Specifies the width of the content area, padding area or border area (depending on `box-sizing`) of certain boxes.
- `height: unit unit`: Specifies the height of the content area, padding area or border area (depending on `box-sizing`) of certain boxes.
- `padding: unit unit unit unit`: The thickness of the padding area.
- `margin: unit unit unit unit`: Set values the thickness of the margin area.
- `border-width: unit`: The thickness of the border around all four edges of an element.
- `border-color: color`: The color of the border around all four edges of an element.
- `border-style: style`: The style of the border around all four edges of an element.
- `border: unit style color`: Combination of properties and values of border.
- `border-radius: unit`: Rounds the border edges.
- `border-radius: unit unit unit unit`: Rounds the specific border edge.
- `border-collapse: separate/collapse`: Applies the border state (separated or collapsed).
- `border-image: url()`: We can set our own images as border.
- `border-image-slice: number`: Specifies the offset that is used to divide the image into nine regions (four corners, four edges and a middle).

- `display: type`: Set value to make certian positions or levels (like inline, block, flex and so on).
- `box-sizing: type`: Specifies the behavior of the `width` and `height` properties.

## Positions

- `position: fixed`: Sets how an element is positioned in a document. In this case, we set it to the `fixed`.
- `position: absolute`: Sets how an element is positioned in a document. In this case, we set it to the `absolute` which means that this element belongs to the ancestor (default is `html` element).
- `position: relative`: It defines how this element should move from the current position. In other hands it leads to being a parent.
- `top right bottom left`: These properties determine the final location of positioned elements (`position` property).
- `z-index: value`: We can set the z-axis or depth of an element with this property.
- `overflow-x: value`: Specifies the handling of overflow in the horizontal direction.
- `overflow-y: value`: Specifies the handling of overflow in the vertical direction.

## Filters

- `blur()`: Blures of an element - e.g. `blur(5px)`.
- `brightness()`: Brightness of an element - e.g. `brightness(200%)`.
- `contrast()`: Setting contrast of an element - e.g. `contrast(200%)`.
- `grayscale()`: Changing the gray-ish of an element - e.g. `grayscale(60%)`.
- `huerotate()`: Changing the hue of an element - e.g. `hue-rotate(90deg)`.
- `invert()`: Reverses the color of an element - e.g. `invert(80%)`.
- `opacity()`: Changing the opacity of an element - e.g. `opacity(45%)`.
- `saturate()`: Changing the saturate (like soaked with liquid or brush) of an element - e.g. `saturate(500%)`.
- `sepia()`: Adds a brown-ish or coffee color to an element - e.g. `sepia(20%)`.

## Functions

- `url("")`: Uses path for background color and image.
- `rgb(red, green, blue)`: Specifies the color of part of an element.
- `rgba(red, green, blue, alpha channel)`: Specifies the color of part of an element with opacity level.
- `linear-gradient(pos-dir, color1, color2, colorn)`: Adds a linear gradient color to an element.
- `radial-gradient(pos-dir, color1, color2, colorn)`: Adds a radial gradient color to an element.
- `calc()`: With that, we can use the mathmatics with that function.

## FlexBox Container

- `display: flex`: Turns the element into the flex contianer.
- `flex-direction: direction`: Specifies the direction of flex container (row, row-reverse, column and column-reverse).
- `flex-wrap: value`: Controls whether the flex container is single-line or multi-line, and the direction of the cross-axis, which determines the direction new lines are stacked in.
- `flex-flow: flex-direction flex-wrap`: The combination of `direction` and `flex-wrap` properties.
- `align-items: alignment`: Aligns items along the **cross axis**.
- `justify-content: alignment`: Aligns items along the **main axis**.

## FlexBox Flex Items

- `order: number`: Change the order of items (bigger number => latest element).
- `align-self: value`: Change the individual element position.
- `flex-grow: number`: Sets the flex grow factor. Negative numbers are invalid (default is `0`).
- `flex-shrink: number`: Sets the flex shrink factor. Negative numbers are invalid (default is `1`).
- `flex-basis: unit`: Defines the size of an element depending on the main axis (depends on the flex size).
- `flex: flex-grow flex-shrink flex-basis`: Combination of three flex item properties.

## CSS Grid

- `display: grid`: Turns the container into a grid.
- `grid-template-columns: [name] unit`: Defines multiple columns in the grid.
- `grid-template-rows: [name] unit`: Defines multiple rows in the grid.
- `grid-template-areas: value`: Create a nice and dynamic area like a table.
- `grid-column-start: number/name`: Pointing an element's start point in column side.
- `grid-column-end: number/name`: Pointing an element's end point in column side.
- `grid-row-start: number/name`: Pointing an element's start point in rows side.
- `grid-row-end: number`: Pointing an element's end point in row side.
- `grid-column: start / end`: Shorthand property for `grid-column-start` and `grid-column-end` properties.
- `grid-row: start / end`: Shorthand property for `grid-row-start` and `grid-row-end` properties.
- `grid-area: row-start / column-start / row-end / column-end`: Shorthand property for `grid-column` and `grid-row` properties.
- `repeat(number, pattern)`: Repeating some units in one method.
- `minmax(unit, unit)`: Specifies an element with limited width and height (used for `grid-template-columns` and `grid-template-rows` properties).
- `fit-content(unit)`: Specifies an element with initial size (no more than the content requires).
- `column-gap: unit`: Specifies gap between elements in column side.
- `row-gap: unit`: Specifies gap between elements in row side.
- `gap: row-unit column-unit`: Shorthand for `row-gap` and `column-gap` properties.
- `justify-content: start/center/end`: Changes the grid position along the X axis.
- `align-content: start/center/end`: Changes the grid position along the Y axis.
- `justify-self: start/center/end`: Moves cell along the X axis.
- `align-self: start/center/end`: Moves cell along the Y axis.
- `grid-auto-rows: unit`: Controls how rows' size being increased (not based on the content size).
- `grid-auto-columns: unit`: Controls how columns' size being increased (not based on the content size).
- `grid-auto-flow: value`: Controls how auto-placed items get flowed into the grid.
- `auto-fill`: (keyword) Fills the current row with as many items as possible and then it will wrap and enter a new row.
- `auto-fit`: (keyword) Fits the current row with as many items as possible and then it will wrap and enter a new row.

## Transformation

- `transform: rotateX(degree)`: Rotate an element along the X axis.
- `transform: rotateY(degree)`: Rotate an element along the Y axis.
- `transform: rotateZ(degree)`: Rotate an element along the Z axis.
- `transform: rotate(degree)`: Rotate an element along the Z axis by default.
- `transform: translateX(unit)`: Allows us to move an element in its X axis, not the page X axis.
- `transform: translateY(unit)`: Allows us to move an element in its Y axis, not the page Y axis.
- `transform: translateZ(unit)`: Allows us to move an element in its Z axis, not the page Z axis.
- `transform: translate(unit, unit)`: Allows us to move an element in its X and Y axises, not the page X and Y axises.
- `transform-origin: position`: Set an origin of the rotating or transforming elements.
- `transform: skewX(degree)`: Skews an content along the X axis.
- `transform: skewY(degree)`: Skews an content along the Y axis.
- `transform: skew(degree, degree)`: Skews an content along the X and Y axises.
- `transform: scaleX(times)`: Scales an element along the X axis.
- `transform: scaleY(times)`: Scales an element along the Y axis.
- `transform: scaleZ(times)`: Scales an element along the Z axis.
- `transform: scale3d(times)`: OOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO.
- `transform: scale(times)`: Scales an element along the both X and Y axises. If we use two parameters, they are calculated separately in X and Y axises.
- `perspective: unit`: Applies the same transform as the `perspective(number)` transform function, except that it applies only to the positioned or transformed children of the element, not to the transform on the element itself.
- `perspective-origin: unit/value`: Establishes the origin for the perspective property. It effectively sets the X and Y position at which the viewer appears to be looking at the children of the element.

## Transition

- `transition-property: property`: Selects any property to apply an animation.
- `transition-duration: time`: Duration of animation.
- `transition-delay: time`: Applies delay to our animation.
- `transition-timing-function: value`: Linear, ease, ease-in, ease-out, ease-in-out and cubic-bezier timing function for our animation.
- `transition: property duration delay timing-function`: Shorthand for `transition-property`, `transition-duration`, `transition-delay` and `transition-timing-function` properties.

## Animation

- `@keyframes hamid { from { } to { } }`: Animation declaration.
- `animation-name: name`:Name of animation.
- `animation-duration: time`: Duration of animation.
- `animation-timing-function: value`: Linear, ease, ease-in, ease-out, ease-in-out and cubic-bezier timing function for our animation.
- `animation-delay: time`: Applies delay to our animation.
- `animation-iteration-count: number/infinite`: Number of the animation iteration.
- `animation-direction: alternate/reverse/...`: Choose the animation direction (start and end point).
- `animation-fill-mode: backwards/both/forwards`: Save the animation state in first point (first keyframe) and last point (last keyframe) or both of them.
- `animation-play-state: running/paused`: Defines whether the animation is running or paused.
- `animation: name duration timing-function delay iteration-count fill-mode direction play-state`: The animation shorthand.

## Pseudo Classes

- `selector:root`: Selects the document's root element.
- `selector:hover`: Add hover effect.
- `selector:active`: To seeing an active link.
- `selector:focus`: Selects the input element which has focus.
- `selector:focus-within`: Selects the input element which has focus.
- `selector:checked`: Selects every checked input element.
- `selector:enabled`: Selects every enabled input element.
- `selector:disabled`: Selects every disbled input element.
- `selector:empty`: Selects every element that has no children (just include text node).
- `selector:is(.selcetor1, selcetor2, selectorn)`: Selects multiple selector that contain in same selector.
- `selector:not(tag/selector)`: Allows us to reverse a certain rule or exclude a certain selector.
- `selector:first-letter`: Changes the behavior of first letter of a paragraph or text.
- `selector:first-child`: Selects the first child of parent element.
- `selector:last-child`: Selects the last child of parent element.
- `selector:nth-child(number)`: Selects a specific child for a parent element.
- `selector:nth-child(n+number)`: Selects a specific child and the rest elements.
- `selector:nth-child(numnern)`: Selects specific childs and the rest elements based on the number (e.g. `:nth-child(3n)` selects third sixth ninth and etc elements).
- `selector:nth-child(-n+number)`: Selects first child and other children based on the number for a parent element (e.g. `div p:nth-child(-n + 5)`: Selects children `1` to `5`).
- `selector:nth-child(even)`: Selects the even children.
- `selector:nth-child(odd)`: Selects the odd children.
- `selecotor:in-range`: Uses for input that has `min` and `max` attribute value.
- `selecotor:out-of-range`: Uses for input that has `min` and `max` attribute value.
- `selector:valid`: Uses for input that has valid value.
- `selector:invalid`: Uses for input that has invalid value like email input.
- `selector:read-write`: Allows us to edit our content of an element (make sure that the `contenteditable` attribute is set).
- `selector:visited`: Selects all visited links.
- `selector:link`: Selects all unvisited links.
- `selector:required`: Selects input element with the `required` attribute.
- `selector:optional`: Selects input element with no `required` attribute.

## Pseudo Elements

- `selector::before`: Add content before a selector content.
- `selector::after`: Add content after a selector content.
- `selector::selection`: Changes the behavior of text selection.

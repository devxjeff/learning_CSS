# CSS Learning Roadmap

A practical roadmap for learning CSS, from the basics to responsive page
layouts and a mini project.

Use the checklist to track your progress. For each stage, read the
concepts, practise with small examples, and apply what you learn to your
own webpage.

## 1. CSS Selectors

Learn how to target HTML elements so you can apply styles to them.

-    Element selectors, such as `p` and `h1`
-    Class selectors, such as `.card`
-    ID selectors, such as `#header`
-    Grouping selectors, such as `h1, h2, p`
-    Descendant and child selectors
-    Attribute selectors
-    Pseudo-classes, such as `:hover` and `:focus`
-    Pseudo-elements, such as `::before` and `::after`
-    Specificity and the cascade

**Practice:** Style headings, paragraphs, buttons, and a card using
different selectors.

## 2. Colors

Learn how to set colors for text, backgrounds, borders, and other
elements.

-    Named colors
-    HEX color values
-    RGB and RGBA
-    HSL and HSLA
-    `color` and `background-color`
-    Transparency and contrast

**Practice:** Create a simple color palette and use it consistently
across a webpage.

## 3. Units and Sizes

Understand how CSS measures dimensions, spacing, and text.

-  Pixels (`px`)
-    Percentages (`%`)
-    `em` and `rem`
-    Viewport units (`vw`, `vh`, `vmin`, `vmax`)
-    `auto`, `min-content`, and `max-content`
-    `min-width`, `max-width`, `min-height`, and `max-height`
-    When to use fixed versus flexible sizing

**Practice:** Make a content container that can grow on large screens
but does not become too wide.

## 4. The Box Model

Learn how the browser calculates the space an element occupies.

-    Content
-    Padding
-    Border
-    Margin
-    `box-sizing`
-    `width` and `height`
-    Margin collapsing
-    Spacing and alignment

**Practice:** Build a card with padding, a border, and space around it.
Try `box-sizing: border-box`.

## 5. Typography

Learn how to make text readable and visually consistent.

-   [ ] `font-family`
-   [ ] `font-size`
-   [ ] `font-weight`
-   [ ] `font-style`
-   [ ] `line-height`
-   [ ] `text-align`
-   [ ] `text-decoration`
-   [ ] `text-transform`
-   [ ] Letter and word spacing
-   [ ] Web-safe fonts and web fonts

**Practice:** Style a page title, section headings, paragraphs, and
small supporting text.

## 6. Styling Links

Learn how to make links clear and interactive.

-   [ ] The `:link` and `:visited` states
-   [ ] The `:hover` state
-   [ ] The `:focus` state
-   [ ] The `:active` state
-   [ ] Removing or changing underlines
-   [ ] Improving keyboard accessibility
-   [ ] Providing visible focus styles

**Practice:** Create navigation links with hover and focus effects that
remain easy to read.

## 7. List Styles

Learn how to customize ordered and unordered lists.

-   [ ] `list-style-type`
-   [ ] `list-style-position`
-   [ ] `list-style-image`
-   [ ] Styling `ul` and `ol`
-   [ ] Styling list items
-   [ ] Using lists for navigation menus

**Practice:** Create a styled feature list and a simple navigation menu.

## 8. Mini Project: Apply the Fundamentals

Combine selectors, colors, sizing, the box model, typography, links, and
lists.

-   [ ] Plan a simple page structure in HTML
-   [ ] Add a header and navigation
-   [ ] Create a main content section
-   [ ] Style headings and paragraphs
-   [ ] Add links and a list
-   [ ] Use consistent colors and spacing
-   [ ] Check the page in a browser
-   [ ] Fix any overflow or spacing issues

**Suggested project:** A personal introduction page, learning portfolio,
or small business landing page.

## 9. Display

Learn how CSS controls the way elements participate in page layout.

-   [ ] `block`
-   [ ] `inline`
-   [ ] `inline-block`
-   [ ] `none`
-   [ ] `visibility`
-   [ ] `display: flex`
-   [ ] `display: grid`
-   [ ] How display affects width, height, and flow

**Practice:** Compare paragraphs, spans, buttons, and images using
different display values.

## 10. Floats

Understand floats and how text can wrap around an element.

-   [ ] `float: left` and `float: right`
-   [ ] Text wrapping
-   [ ] The `clear` property
-   [ ] Clearing floats
-   [ ] Common float-related layout problems
-   [ ] When modern layout methods are more suitable

**Practice:** Make text wrap around a small image, then compare the
result with a Flexbox layout.

## 11. Columns

Learn ways to arrange content into columns.

-   [ ] The CSS multi-column layout
-   [ ] `column-count`
-   [ ] `column-width`
-   [ ] `column-gap`
-   [ ] `column-rule`
-   [ ] Balancing and reading flow
-   [ ] The difference between text columns and grid columns

**Practice:** Format a long article into readable columns, then adjust
the layout for a narrow screen.

## 12. Positioning

Learn how elements can be placed relative to their normal position or a
containing element.

-   [ ] `position: static`
-   [ ] `position: relative`
-   [ ] `position: absolute`
-   [ ] `position: fixed`
-   [ ] `position: sticky`
-   [ ] `top`, `right`, `bottom`, and `left`
-   [ ] Containing blocks
-   [ ] `z-index` and stacking order

**Practice:** Create a badge positioned on a card and a sticky
navigation bar.

## 13. Flexbox

Learn a one-dimensional layout system for arranging items in rows or
columns.

-   [ ] Flex containers and flex items
-   [ ] `display: flex`
-   [ ] `flex-direction`
-   [ ] `justify-content`
-   [ ] `align-items`
-   [ ] `align-content`
-   [ ] `gap`
-   [ ] `flex-wrap`
-   [ ] `flex-grow`, `flex-shrink`, and `flex-basis`
-   [ ] `align-self`

**Practice:** Build a navigation bar, a row of cards, and a centered
login form.

## 14. CSS Grid Layout

Learn a two-dimensional layout system for rows and columns.

-   [ ] `display: grid`
-   [ ] Grid rows and columns
-   [ ] `grid-template-columns` and `grid-template-rows`
-   [ ] Fractional units (`fr`)
-   [ ] `gap`
-   [ ] `repeat()`
-   [ ] `minmax()`
-   [ ] `grid-column` and `grid-row`
-   [ ] Grid areas
-   [ ] Responsive grids

**Practice:** Create a gallery or dashboard with a grid of cards.

## 15. Images

Learn how to size and position images cleanly in a webpage.

-   [ ] Setting image width and height
-   [ ] `max-width: 100%`
-   [ ] `height: auto`
-   [ ] `object-fit`
-   [ ] `object-position`
-   [ ] Rounded corners and borders
-   [ ] Background images
-   [ ] `background-size` and `background-position`
-   [ ] Avoiding stretched or distorted images
-   [ ] Basic accessibility: useful `alt` text in HTML

**Practice:** Create a responsive image gallery with consistent image
sizes.

## 16. Media Queries and Responsive Design

Learn how to adapt a webpage to phones, tablets, laptops, and larger
screens.

-   [ ] What responsive design means
-   [ ] The viewport and mobile-first design
-   [ ] `@media` rules
-   [ ] Breakpoints
-   [ ] Responsive widths and spacing
-   [ ] Flexible images
-   [ ] Responsive Flexbox and Grid layouts
-   [ ] Testing at different screen sizes
-   [ ] Reducing horizontal overflow
-   [ ] Respecting user preferences where appropriate

**Practice:** Make your mini project work on both a phone-sized screen
and a desktop screen.

## Final Project: Responsive Personal Portfolio

Use the skills from this roadmap to build a small portfolio website.

-   [ ] Create semantic HTML
-   [ ] Add a header and navigation links
-   [ ] Include an introduction section
-   [ ] Add a skills list
-   [ ] Display project cards and images
-   [ ] Use Flexbox or Grid for layout
-   [ ] Add hover and focus states
-   [ ] Make the layout responsive with media queries
-   [ ] Test keyboard navigation
-   [ ] Check text contrast and image alternative text
-   [ ] Organize CSS into readable sections
-   [ ] Upload the project to GitHub

## Suggested Study Routine

1.  Learn one topic at a time.
2.  Type the examples yourself instead of only copying them.
3.  Change values and observe what happens in the browser.
4.  Write a small example for each topic.
5.  Add completed topics to your mini project.
6.  Review earlier topics when you encounter a problem.
7.  Commit your progress to GitHub with clear commit messages.

## Progress Tracker

-   [ ] CSS Selectors
-   [ ] Colors
-   [ ] Units and Sizes
-   [ ] Box Model
-   [ ] Typography
-   [ ] Styling Links
-   [ ] List Styles
-   [ ] Mini Project: Fundamentals
-   [ ] Display
-   [ ] Floats
-   [ ] Columns
-   [ ] Positioning
-   [ ] Flexbox
-   [ ] CSS Grid Layout
-   [ ] Images
-   [ ] Media Queries and Responsive Design

**Reminder:** The goal is not just to finish the topics. It is to
understand each concept well enough to use it independently in your own
webpages.


# CSS Specificity Issue in Nested Selectors

This repository demonstrates a rather uncommon CSS specificity bug related to nested selectors and unexpected behavior. The bug lies in the unexpected application (or lack thereof) of styles due to how CSS specificity works with nested selectors.

## Bug Description

The provided `bug.css` file contains a CSS rule that intends to style a specific element within a nested structure. However, due to specificity issues, the styles aren't applied as expected.

## Bug Solution

The `bugSolution.css` file shows how to resolve the specificity issue by adjusting the selector to have higher specificity or using the `!important` flag (though the latter should be used sparingly).

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` (not included in this repo, you need to create one) in a web browser. Observe the unexpected styling.
3. Replace `bug.css` with `bugSolution.css` and refresh the browser to see the fix.
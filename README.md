# CSS calc() Unexpected Behavior

This repository demonstrates an uncommon bug related to the CSS `calc()` function. The issue arises when using `calc()` to calculate a width based on a percentage and a fixed value, especially when the parent element's width is not explicitly defined.

## Bug Description
The `calc()` function in CSS can produce unexpected results when the parent element doesn't have a specified width. This can lead to unexpected layout behaviors, especially in responsive designs. 

## How to Reproduce
1. Clone this repository.
2. Open `index.html` in your browser.
3. Observe that the inner element's width is not what is expected.

## Solution
Ensure the parent element has an explicitly defined width (either in pixels, percentages, or other units). This provides a solid base for the `calc()` function to work correctly.
# Uncommon HTML Bug: Incorrect Element Selection

This repository demonstrates a subtle bug that can occur in HTML when using JavaScript to modify the content of an element. The bug is related to incorrect element selection using `getElementById`.

## Bug Description

The provided `bug.html` file contains a simple HTML structure with a div element. The JavaScript code attempts to select this div element and modify its innerHTML. However, the selector is incorrect, leading to the bug.

## Bug Solution

The corrected code in `bugSolution.html` demonstrates the proper way to select the element using `getElementById`.  The '#' symbol, which is used for CSS selectors, is omitted.

## How to reproduce the bug

1. Open `bug.html` in a web browser.
2. Observe that the innerHTML is not modified, and there may be a javascript error in the console.

## How to fix the bug

1. Replace `bug.html` with `bugSolution.html`.
2. The innerHTML of the div should now be successfully updated.

This example highlights the importance of understanding the differences between CSS selectors and JavaScript's DOM manipulation methods.
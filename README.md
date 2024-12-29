# Inconsistent Button Hover Effect Due to box-shadow

This repository demonstrates a subtle bug in CSS related to the `box-shadow` property and its behavior on hover. The bug causes an unexpected visual jump in a button element when the user hovers over it.

## Bug Description

A button is styled using CSS to include a box-shadow. The :hover state modifies the box-shadow property which leads to an unintended change in the x and y offset values of the shadow. This leads to a slight jump in the button's position on hover.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to view the buggy CSS code.
3. Open `index.html` in a browser.
4. Observe the button's behavior on hover.

## Solution

The `bugSolution.css` file provides a corrected version of the CSS that addresses the issue by keeping the offset values consistent between the default and hover states, thus eliminating the visual jump.

## Technologies Used

* CSS
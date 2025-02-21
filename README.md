# Uncommon HTML Bug: Number as innerHTML

This repository demonstrates a subtle bug in HTML where assigning a number directly to `innerHTML` leads to unexpected results. The correct approach is to convert the number to a string before assignment.

## Bug Description
The issue lies in directly assigning a numeric value to the `innerHTML` property of an HTML element. Instead of rendering the number as text, the browser attempts to interpret it as a node value, resulting in unusual behavior.

## Bug Reproduction
1. Open the `bug.html` file in a web browser.
2. Observe that the content of the div is not replaced with "100" as expected but instead displays unexpected output.

## Bug Solution
The `bugSolution.html` file demonstrates the correct way to achieve the desired result by explicitly converting the number to a string before setting the `innerHTML` property.
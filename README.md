# CSS Specificity and Inheritance Bug

This repository demonstrates a common issue in CSS related to specificity and inheritance. The `bug.css` file contains code with a specificity problem, resulting in unexpected color inheritance. The `bugSolution.css` file provides a solution to resolve the issue.

## Bug Description

The main issue is that the more specific rule for `div p` does not override the `div` rule because of a specificity problem. The rule set on the `div` is more specific than `div p` resulting in an unpredicted color display.

## Solution

The solution increases the specificity of the `div p` selector to override the parent `div` rule.
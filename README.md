# CSS Specificity Gotcha: Unexpected Inheritance and Specificity Behavior

This repository demonstrates a common, yet subtle issue in CSS related to specificity and inheritance.  The problem lies in understanding how CSS rules are applied when inheritance and selectors with varying specificity are involved.

## The Problem

The `bug.css` file contains CSS rules designed to style paragraphs (`<p>`) within `div` elements.  Intuitively, you might expect the paragraph's style to be determined by the most specific rule. However, due to the intricacies of inheritance and specificity in CSS, the intended styling isn't always applied.

## The Solution

The `bugSolution.css` file shows a possible solution demonstrating how to increase the specificity of the selector that targets paragraphs within `div` elements using more specific selectors.  This is important to understand for avoiding CSS specificity issues and correctly applying the intended style.
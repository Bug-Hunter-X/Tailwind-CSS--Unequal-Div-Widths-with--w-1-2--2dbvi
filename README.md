# Tailwind CSS: Unequal Div Widths with `w-1/2`

This repository demonstrates an unexpected behavior when using Tailwind CSS utility classes for div widths.  The issue involves two divs intended to each occupy 50% of their parent container, but they fail to do so consistently.

The `bug.js` file shows the problem. The solution, provided in `bugSolution.js`, highlights the fix needed to ensure proper width distribution across the child divs.

## Steps to reproduce

1. Clone this repository.
2. Run a local webserver or use a live preview tool for HTML files (such as live-server for VScode).
3. Open `bug.html` in your browser.  Observe the unequal width of the two divs.
4. Open `bugSolution.html` and observe the correct width distribution.

## Solution

The solution involves ensuring the parent container has `flex` enabled, which allows proper distribution of space based on fractional width utilities provided by Tailwind CSS. 

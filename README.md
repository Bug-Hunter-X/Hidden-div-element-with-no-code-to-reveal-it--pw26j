# Hidden Div Bug

This repository demonstrates an uncommon HTML bug related to hidden elements.  The `bug.html` file shows a div that's initially hidden via JavaScript;  however, there's no mechanism to show it later, leading to unexpected behavior. The `solution.html` file provides a fix.

## Bug Description:
The problem lies in the JavaScript code.  It hides a div, but lacks the countermanding code to restore visibility later, which might be unintentional.

## Solution:
The solution involves adding JavaScript to show the div after a delay or based on an event, depending on the intention.
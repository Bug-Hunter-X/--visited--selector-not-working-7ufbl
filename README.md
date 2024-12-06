# :visited selector not working

This repository demonstrates a common issue with the CSS `:visited` pseudo-class selector. The `:visited` selector is intended to style links that have been previously visited by the user. However, due to browser security restrictions, the styling effect of `:visited` is often limited or unpredictable.

## Problem

The provided `bug.css` file contains a CSS rule that attempts to change the color of visited links to purple. However, this rule might not work correctly in all browsers.

## Solution

The `bugSolution.css` file demonstrates an alternative approach. While the appearance of visited links cannot be fully customized, some subtle changes can be achieved by using the `:hover` and `:focus` states. This provides visual feedback without relying heavily on the unreliable `:visited` selector.

## Usage

1. Clone this repository.
2. Open `index.html` (or a similar file including links) in your browser.
3. Notice how the styling on visited links works (or doesn't work) for each CSS version.
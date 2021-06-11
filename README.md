## `display: grid` not rendering properly when displayed as an iPad popover

This demonstrates an issue with using `display: grid` CSS styles within iPadOS popover.

The sample project has a grid layout which displays a two row layout, the initial row being a full width and the second row being a 2 column layout.

1. Opening the popover shows that the grid layout is not rendered as expected
1. Clicking the magical hidden link which opens the popover as a tab shows how the layout should be rendered

![Gif of the bug in action](./sample.gif)

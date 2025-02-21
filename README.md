# CSS Inline-Block Width Inconsistency

This repository demonstrates an uncommon CSS bug related to the width of inline-block elements when the parent container's width is not explicitly defined.  The bug manifests in inconsistent rendering across different browsers.

## Bug Description

The provided CSS snippet uses `display: inline-block;` on a div element.  While expecting the div to occupy 50% of its parent's width, this behavior is not guaranteed if the parent's width is not explicitly set.  Some browsers might ignore the 50% width and render the div at its full content width.

## Solution

The solution involves explicitly setting the width of the parent container. This ensures consistent behavior across different browsers.
# CSS :hover Pseudo-class Issue with Nested Elements

This repository demonstrates a common issue encountered when using the `:hover` pseudo-class in CSS with nested elements.  The expected behavior is that when the parent element is hovered over, the styling applied to the child element via the `:hover` selector should be activated. However, under certain circumstances, this may not occur.

The `bug.css` file contains the erroneous CSS code, and `solution.css` provides the corrected version.

## Problem

The issue arises when specificity conflicts between selectors, especially when the child element is styled directly without consideration of the parent's `:hover` state.  This is clearly outlined in the provided CSS and HTML files.
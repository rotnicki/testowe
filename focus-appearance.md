# Success Criterion 2.4.11 Focus Appearance

(Level AA) [New]

When the keyboard focus indicator is visible, one or both of the following are true:

1. The entire focus indicator meets all the following:
    * encloses the user interface component or sub-component that is focused, and
    * has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states, and
    * has a contrast ratio of at least 3:1 against adjacent non-focus-indicator colors.
2. An area of the focus indicator meets all the following:
    * is at least as large as the area of a 1 CSS pixel thick perimeter of the unfocused component or sub-component, or is at least as large as a 4 CSS pixel thick line along the shortest side of the minimum bounding box of the unfocused component or sub-component, and
    * has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states, and
    * has a contrast ratio of at least 3:1 against adjacent non-focus-indicator colors, or is no thinner than 2 CSS pixels.

Exceptions:

* The focus indicator is determined by the user agent and cannot be adjusted by the author, or
* The focus indicator and the indicator's background color are not modified by the author.

> NOTE
> 
> What is perceived as the user interface component or sub-component (to determine enclosure or size) depends on its visual presentation. The visual presentation includes the component's visible content, border, and component-specific background. It does not include shadow and glow effects outside the component's content, background, or border.
 
> NOTE
> 
> Examples of sub-components that may receive a focus indicator are menu items in an opened drop-down menu, or focusable cells in a grid.

> NOTE
> 
> Contrast calculations can be based on colors defined within the technology (such as HTML, CSS and SVG). Pixels modified by user agent resolution enhancements and anti-aliasing can be ignored.

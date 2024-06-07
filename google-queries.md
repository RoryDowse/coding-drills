# Google Queries Reference Sheet

## Week 1 Mini Project

### Display and Positioning Selectors

#### Making a Fixed Navigation Bar and Following Sections

- reset margin and padding on universal selector
- set width of header to 100%
    - ensures element takes up full space
- set header z-index
    - set high number for high priority
    - ensures fixed header stays on top
- set nav position to 'relative'
    - this offsets the element from the normal flow
- display the nav list items inline
    - this turns the list items from vertical elements to horizonal
- remove bullet points by 'list-style-type: none'
- reset color of nav links
    - from hyperlink reference blue to desired color
    - set 'text-decoration: none' to remove visted link default color
- set main element position to relative
    - this offsets it from the fixed header
    - determine the height of the header
        - use the browser box model source
    - add 'top: [insert header height]px' to offset
- center other elements by:
    - text - text-align: center;
    - img - display: block;<br>
            margin: 0 auto;
    - consider - width: 50%;<br>
                margin: 0 auto;
- offset other elements - like container or footer - with:
    - position: relative;<br>
    top: [insert header height]px;
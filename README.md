# Learning Materials

This work is centred on developing a flexible and reusable Style Guide for Learning Materials, Resources and other Teaching and Learning content at Charles Sturt University.

## Workshop

[Report put together from the Design Thinking](https://app.box.com/s/9ujleq2tqqakcjtq08gpdfc73njx0bnh) workshop. Starting point for discussions.

## Influences on Style

### CSU Sites

- [Student.csu](http://student.csu.edu.au)
- [Innovate.csu](http://innovate.csu.edu.au)
- [Staff.csu](http://staff.csu.edu.au)

### Material Design

Forms the basis of new CSU websites

- [Material Design](https://material.io)
- Inspired frameworks with examples:
  - [Materialize CSS](http://materializecss.com)
  - [Material Design Lite](https://getmdl.io/index.html)

### Responsive type

Responsive type settings used are based on this article:[Viewport Unit Based Typography](https://zellwk.com/blog/viewport-based-typography/). This uses a single calculation based on the screens width to set the baseline value of 18px to create the font size value:

```css
font-size: calc(112.5% + 0.5vw)
```

Font's used in Blackboard are mostly are based on percentages and ems so this size flows through the site quite well.

### Flex Grid

A simple grid system using flexbox has been deployed in the theme. Based on these articles:

- https://philipwalton.github.io/solved-by-flexbox/demos/grids/
- https://www.taniarascia.com/easiest-flex-grid-ever/

By using Flexbox's innate nature to resize elements based on the page the grid is simply based on Rows and Columns. Place Columns in a Row and they will automatically resize equally. This works fine for most applications but there are special classes - column-half, column-2 and column-3 - which will help come up with thirds and other column configurations. Flexbox also provides ways to align content within elements to top, bottom and center.

## Useful Tools

### Colour Tools

- [Adobe Color](https://color.adobe.com)
- [Sass Color Generator](http://scg.ar-ch.org/)

### HTML

- [HTML Cleaner](https://html-cleaner.com/) - general purpose cleaner for HTML
- [CSS Out](https://uimagine.edu.au/cssout) - cleans out inline styles
- [Atom](https://atom.io) - text editor designed for working in code


## Tips for Testing

1. Open Chrome and install [Styler](https://chrome.google.com/webstore/detail/styler/bogdgcfoocbajfkjjolkmcdcnnellpkb)
2. Go to the web page you wish to test on - Interact2 for example
3. Click on Styler to open up the CSS & JS windows
3. Past in CSS and click off the window to see changes
4. Styler will store your CSS for that website so to revert to the original you need to delete the CSS

# Learning Materials

This work is centred on developing a flexible and reusable Style Guide for Learning Materials, Resources and other Teaching and Learning content at Charles Sturt University.

## Workshop

[Report put together from the Design Thinking](https://app.box.com/s/9ujleq2tqqakcjtq08gpdfc73njx0bnh) workshop. Starting point for discussions.

## Preview Links

New elements demonstration - [Material Demonstration](https://uimagine.edu.au/interact2-theme/material-demo)
New style guide tool - [Style Guide]https://uimagine.edu.au/interact2-theme/guide)

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

With the introduction of Responsive Design Elements a lot of consideration has gone into the design of the typography. The focus of these changes has been to improve the *readability* of the text in Blackboard - and to do it across screen sizes. The article *[Your Body Text Is Too Small
Why website body text should be bigger, and ways to optimize it.](https://medium.com/@xtianmiller/your-body-text-is-too-small-5e02d36dc902)* provides a good overview of the approach taken and the reasons why.

Responsive type settings used are based on this article:[Precise control over responsive typography](https://madebymike.com.au/writing/precise-control-responsive-typography/). This uses a single calculation based on the screens width to set the baseline value of 16px and a maximum of 24px which is designed to adapt to any screen size - the small the screen the closer to the user and the smaller the text, the larger the screen the further away the user is and so the larger the font.

The basic equation sets this up here with a media query setting the max size at 24px at 1000px screen width.

```css
font-size: calc( 16px + (24 - 16) * ( (100vw - 400px) / ( 1000 - 400) ));
```

Once this baseline has been introduced to the content area - all font sizes are relative using percentages which allows them to adapt easily to all variations.

### Flex Grid

A simple grid system using flexbox has been deployed in the theme. Based on these articles:

- https://philipwalton.github.io/solved-by-flexbox/demos/grids/
- https://www.taniarascia.com/easiest-flex-grid-ever/

By using Flexbox's innate nature to resize elements based on the page the grid is simply based on Rows and Columns. Place Columns in a Row and they will automatically resize equally. This works fine for most applications but there are special classes - column-half, column-2 and column-3 - which will help come up with thirds and other column configurations. Flexbox also provides ways to align content within elements to top, bottom and center.

### Tooltips

Tool tips uses the CSS framework from [Wenk](https://tiaanduplessis.github.io/wenk/) but replaces the ```data-wenk``` attribute with ```tooltip```. To use simply se an attribute in the tag to ```tooltip="the text you want to display"```.

### Print CSS

Add a tweaked version of the [Gutenberg Print CSS](https://github.com/BafS/Gutenberg) and removed nav and header items from display. Tweaked background printing to turn it on.

## Useful Tools Used

### Colour Tools

- [Adobe Color](https://color.adobe.com)
- [Sass Color Generator](http://scg.ar-ch.org/)

### HTML

- [HTML Cleaner](https://html-cleaner.com/) - general purpose cleaner for HTML
- [CSS Out](https://uimagine.edu.au/cssout) - cleans out inline styles
- [Atom](https://atom.io) - text editor designed for working in code

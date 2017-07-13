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

## Tips for Testing

1. Open Chrome and install [Styler](https://chrome.google.com/webstore/detail/styler/bogdgcfoocbajfkjjolkmcdcnnellpkb)
2. Go to the web page you wish to test on - Interact2 for example
3. Click on Styler to open up the CSS & JS windows
3. Past in CSS and click off the window to see changes
4. Styler will store your CSS for that website so to revert to the original you need to delete the CSS

### Font Testing

**Import Fonts into Styler CSS**

```CSS
@import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro|Arimo|Archivo+Narrow|Roboto|Lora|Merriweather|Source+Serif+Pro');

```
View different fonts by changing the body/span selector

```css
body, span[style] {font-family: 'Source Sans Pro' !important;}

body, span[style] {font-family: 'Arimo' !important;}

body, span[style] {font-family: 'Archivo Narrow' !important;}

body, span[style] {font-family: 'Roboto' !important;}

body, span[style] {font-family: 'Lora' !important;}

body, span[style] {font-family: 'Merriweather' !important;}

body, span[style] {font-family: 'Source Serif Pro' !important;}

```

### Interact2 Devel Hacks

```css
body {
 max-width:100%;
}

.customBanner {
max-height: 50vh;
}
```

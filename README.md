# Learning Materials

This work is centred on developing a flexible and reusable Style Guide for Learning Materials, Resources and other Teaching and Learning content at Charles Sturt University.

## Tips for Testing

1. Open Chrome and install [Styler](https://chrome.google.com/webstore/detail/styler/bogdgcfoocbajfkjjolkmcdcnnellpkb)
2. Go to the web page you wish to test on - Interact2 for example
3. Past in CSS and see changes
4. Revert to original by deleting CSS

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

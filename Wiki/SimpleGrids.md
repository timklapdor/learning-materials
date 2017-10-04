## Simple Grids

The new style uses a simple grid layout consisting of two classes - ``` .flex-row``` and ``` .flex-column``` that are applied to ```<div>``` tags. The rows act as a container and set basic styles for the containers. Containers will by default auto resize to fit equally within a row container. So equal columns are simple to create and manage. The simplicity of this grid system also plays nicely in that for mobile screens items will simply stack as blocks on top of each other.

```html
<div class="flex-row">
  <div class="flex-column"><p>Some text in here</p></div>
  <div class="flex-column"><p>Some other text in here</p></div>
</div>
```

You can also create multi-columns

```html
<div class="flex-row">
  <div class="flex-column"><p>Some text in here</p></div>
  <div class="flex-column"><p>Some other text in here</p></div>
  <div class="flex-column"><p>Some more text in here</p></div>
  <div class="flex-column"><p>Even more text in here</p></div>
</div>
```

### Basic Grid Code

Use the following code to create a number of basic layouts:

#### Halves

```html
<div class="flex-row">
  <div class="flex-column"><p>Some text in here</p></div>
  <div class="flex-column"><p>Some other text in here</p></div>
</div>
```
#### Thirds

```html
<div class="flex-row">
  <div class="flex-column"><p>Some text in here</p></div>
  <div class="flex-column"><p>Some other text in here</p></div>
  <div class="flex-column"><p>Some more text in here</p></div>
</div>
```

#### Two Thirds

```html
<div class="flex-row">
  <div class="flex-column"><p>Some text in here</p></div>
  <div class="flex-column-2"><p>Some other text in here</p></div>
</div>
```

#### Three Quarters

```html
<div class="flex-row">
  <div class="flex-column"><p>Some text in here</p></div>
  <div class="flex-column-3"><p>Some other text in here</p></div>
</div>
```

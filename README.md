# LeadsNearby Website Style Guide

### Contents
* [Elements](#elements)
    * [Typography](#typography)
        * [Headings](#headings)
        * [Body](#body)
    * Buttons
    * Nearby Now Widget
* Layouts

## Elements

### Typography [Source Code](src/scss/parts/_typography.scss)

*Note: In most cases, typography styles should already be defined in Avada Theme Options, making the inclusion of these styles unnecessary*

#### Headings

```css
h1, h2, h3, h4 {
    color: #333;
    text-align: left;
    text-transform: none;
    font-family: "Open Sans", Arial, Helvetica, sans-serif;
    font-weight: 400;
    line-height: 1.2;
    margin-top: 0;
    margin-bottom: 1em;
}

h1 {
    font-size: 2.45em;
}

h2 {
    font-size: 1.953em;
}

h3 {
    font-size: 1.563em;
}

h4 {
    font-size: 1.25em;
}
```

#### Body

```css
body {
    color: #333;
    text-align: left;
    text-transform: none;
    font-family: "Open Sans", Arial, Helvetica, sans-serif;
    font-size: 16px;
    font-weight: 400;
    line-height: 1.5;
}

p {
    margin-top: 0;
    margin-bottom: 1em;
}
```


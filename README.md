# LeadsNearby Website Style Guide

## Contents

* [Colors](#colors)
* [Elements](#elements)
    * [Typography](#typography)
        * [Headings](#headings)
        * [Body](#body)
    * [Buttons](#buttons)
    * [Icons](#icons)
    * [Custom Fusion Elements](#custom-fusion-elements)
    * [Fusion Element Modifications](#fusion-element-modifications)
    * [Nearby Now Widget](#nearby-now-widget)
* [Layouts](#layouts)

## Colors

<img src="src/images/colors/gray-dark.svg" style="vertical-align: middle" /> Dark Gray

<img src="src/images/colors/gray-medium.svg" style="vertical-align: middle" /> Medium Gray

<img src="src/images/colors/gray.svg" style="vertical-align: middle" /> Gray

<img src="src/images/colors/red.svg" style="vertical-align: middle" /> Red

```scss
// SCSS Color Variables
$gray-dark: #1a1a1a;
$gray-medium: #333;
$gray: #4c5264;
$gray-light: #efefef;
$red-dark: #a01d20;
$red: #f43127;
$pink: #f62459;
$orange: #ff6a2b;
$yellow: #ffd058;
$green: #00972f;
$green-lime: #94cc61;
$blue-navy: #1e2b43;
$blue-medium: #004983;
$blue-cobalt: #006ada;
$blue-light: #aec6d8;
$grape: #a338c4;
$violet: #9a88c5;
```

```css
/* CSS Color Variables */
:root {
    --color-gray-dark: #1a1a1a;
    --color-gray-medium: #333;
    --color-gray: #4c5264;
    --color-gray-light: #efefef;
    --color-red-dark: #a01d20;
    --color-red: #f43127;
    --color-pink: #f62459;
    --color-orange: #ff6a2b;
    --color-yellow: #ffd058;
    --color-green: #00972f;
    --color-green-lime: #94cc61;
    --color-blue-navy: #1e2b43;
    --color-blue-medium: #004983;
    --color-blue-cobalt: #006ada;
    --color-blue-light: #aec6d8;
    --color-grape: #a338c4;
    --color-violet: #9a88c5;
}
```


## Elements

### Typography - [Source Code](src/scss/parts/_typography.scss)

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

### Buttons

### Icons

### Custom Fusion Elements

### Fusion Element Modifications

### Nearby Now Widget

The Nearby Now widget element is bundled in the lnb-nn-integration Wordpress plugin. See [plugin repository](https://github.com/LeadsNearby/lnb-nn-integration#nearby-now-stynamic-widget) for more detailed information. Example widget code is pasted below for reference and to show the structure of the HTML and styling is designed to be easy to modify.

```html
<div class="lnbReviewsWidget lnbReviewsWidget--block" style="--accent-color:#000;--stars-color:#fee300;">
    <h3 class="lnbReviewsWidget__title">Company Name</h3>
    <svg class="lnbReviewsWidget__stars" id="lnb-review-widget-stars" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 35">
        <path d="M20.5.4L26 11.6l12.4 1.8-9 8.7 2.2 12.3-11.1-5.8-11 5.8 2.1-12.3-9-8.7L15 11.6zM60.1.4l5.6 11.2L78 13.4l-8.9 8.7 2.1 12.3-11.1-5.8-11 5.8 2.1-12.3-8.9-8.7 12.3-1.8zM99.8.4l5.5 11.2 12.3 1.8-8.9 8.7 2.1 12.3-11-5.8-11.1 5.8 2.1-12.3-8.9-8.7 12.3-1.8zM139.4.4l5.5 11.2 12.4 1.8-9 8.7 2.1 12.3-11-5.8-11.1 5.8 2.1-12.3-8.9-8.7 12.4-1.8zM179 .4l5.5 11.2 12.4 1.8-9 8.7 2.2 12.3-11.1-5.8-11 5.8 2.1-12.3-9-8.7 12.4-1.8z"></path>
    </svg>
    <span class="lnbReviewsWidget__data">Rated 5.0 out of 15,000 reviews</span>
</div>
```

## Layouts
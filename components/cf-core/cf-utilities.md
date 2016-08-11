---
layout: default
title:  "cf-utilities"
parent: "cf-core"
---


## Helper classes

### Clearfix

<div class="u-clearfix">
    <div style="float: right; width: 50%; height: 60px; background: lightblue;"></div>
</div>
<i>
    This text would normally flow up into the empty space to the left of the blue box,
    if the black box's parent did not have the `u-clearfix` class.
</i>

### Visually hidden

<a href="#">
    <span class="cf-icon cf-icon-twitter-square"></span>
    <span class="u-visually-hidden">Share on Twitter</span>
</a>

The text "Share on Twitter" in the above example is only accessible to screenreaders.

### Inline block

<div class="u-mb30">
    Sets <code>display: inline-block;</code> and adds a <code>.lt-ie8</code>
    fallback to hack inline block for IE 7 and below.
    <div class="u-inline-block" style="background: lightblue; padding: 0 0.5em;">
        Inline block
    </div>
</div>

### Float right

<div class="u-clearfix u-mb30">
    <div class="u-right" style="background: lightblue; padding: 1em;">I'm floating!</div>
</div>

### Break word

<div class="u-break-word u-mb30" style="width: 100px; padding: 0.5em; border: 1px solid silver;">
    <a href="#">
        something@something.com
    </a>
</div>

### Margin utilities

<div class="content-l u-mb30">
    <div class="content-l_col content-l_col-1-2">
        <div class="u-mb0" style="background-color: lightblue;">0 bottom margin</div>
        <div class="u-mb5" style="background-color: lightblue;">5 bottom margin</div>
        <div class="u-mb10" style="background-color: lightblue;">10 bottom margin</div>
        <div class="u-mb15" style="background-color: lightblue;">15 bottom margin</div>
        <div class="u-mb20" style="background-color: lightblue;">20 bottom margin</div>
        <div class="u-mb30" style="background-color: lightblue;">30 bottom margin</div>
        <div class="u-mb45" style="background-color: lightblue;">45 bottom margin</div>
        <div class="u-mb60" style="background-color: lightblue;">60 bottom margin</div>
    </div>
    <div class="content-l_col content-l_col-1-2">
        <div class="u-mt0" style="background-color: lightblue;">0 top margin</div>
        <div class="u-mt5" style="background-color: lightblue;">5 top margin</div>
        <div class="u-mt10" style="background-color: lightblue;">10 top margin</div>
        <div class="u-mt15" style="background-color: lightblue;">15 top margin</div>
        <div class="u-mt20" style="background-color: lightblue;">20 top margin</div>
        <div class="u-mt30" style="background-color: lightblue;">30 top margin</div>
        <div class="u-mt45" style="background-color: lightblue;">45 top margin</div>
        <div class="u-mt60" style="background-color: lightblue;">60 top margin</div>
    </div>
</div>

### Width utilities

<div class="u-w100pct" style="background: lightblue; margin-bottom: 1px;">
    100 %
</div>
<div class="u-w90pct" style="background: lightblue; margin-bottom: 1px;">
    90 %
</div>
<div class="u-w80pct" style="background: lightblue; margin-bottom: 1px;">
    80 %
</div>
<div class="u-w70pct" style="background: lightblue; margin-bottom: 1px;">
    70 %
</div>
<div class="u-w60pct" style="background: lightblue; margin-bottom: 1px;">
    60 %
</div>
<div class="u-w50pct" style="background: lightblue; margin-bottom: 1px;">
    50 %
</div>
<div class="u-w40pct" style="background: lightblue; margin-bottom: 1px;">
    40 %
</div>
<div class="u-w30pct" style="background: lightblue; margin-bottom: 1px;">
    30 %
</div>
<div class="u-w20pct" style="background: lightblue; margin-bottom: 1px;">
    20 %
</div>
<div class="u-w10pct" style="background: lightblue; margin-bottom: 1px;">
    10 %
</div>
<div class="u-w75pct" style="background: lightblue; margin-bottom: 1px;">
    75 %
</div>
<div class="u-w25pct" style="background: lightblue; margin-bottom: 1px;">
    25 %
</div>
<div class="u-w66pct" style="background: lightblue; margin-bottom: 1px;">
    66 %
</div>
<div class="u-w33pct u-mb30" style="background: lightblue; margin-bottom: 1px;">
    33 %
</div>

### Width-specific display

#### Show on mobile

View this page at a width narrower than [`@bp-xs-max`](cf-vars.html#breakpoint-variables)
to see the show-on-mobile example.

<div class="u-mb30" style="border: 1px solid black; height: 22px; padding: 5px;">
    <p class="u-show-on-mobile">Visible on mobile</p>
</div>

#### Hide on mobile

<div class="u-mb30" style="border: 1px solid black; height: 22px; padding: 5px;">
    <p class="u-hide-on-mobile">Hidden on mobile</p>
</div>


## Mixins

### Align with button

<button class="a-btn">Button</button>
<span class="u-align-with-btn">Aligned with button</span>

### Flexible proportional containers

#### 16:9 flexible video player

<div class="u-flexible-container u-mb30">
    <video class="u-flexible-container_inner"
           style="background: lightgray;"
           controls>
    </video>
</div>

### 4:3 flexible video player

<div class="u-flexible-container u-flexible-container__4-3 u-mb30">
    <video class="u-flexible-container_inner"
           style="background: lightgray;"
           controls>
    </video>
</div>

### Flexible container with only a background (no inner video or object element)

<div class="u-flexible-container u-mb30"
     style="background-image: url(http://placekitten.com/870/490);
            background-position: center center;
            background-repeat: no-repeat;"></div>

### Link modifiers

Modify link properties using the following mixins.

#### Link colors

`u-link__colors()`

<ul class="link-color-example-0">
    <li><a href="#">Link</a></li>
    <li><a class="visited" href="#">Visited</a></li>
    <li><a class="hover" href="#">Hover</a></li>
    <li><a class="focus" href="#">Focus</a></li>
    <li><a class="active" href="#">Active</a></li>
</ul>

`u-link__colors(@pacific)`

<ul class="link-color-example-1">
    <li><a href="#">Link</a></li>
    <li><a class="visited" href="#">Visited</a></li>
    <li><a class="hover" href="#">Hover</a></li>
    <li><a class="focus" href="#">Focus</a></li>
    <li><a class="active" href="#">Active</a></li>
</ul>

`.u-link__colors(@pacific, @red)`

<ul class="link-color-example-2">
    <li><a href="#">Link</a></li>
    <li><a class="visited" href="#">Visited</a></li>
    <li><a class="hover" href="#">Hover</a></li>
    <li><a class="focus" href="#">Focus</a></li>
    <li><a class="active" href="#">Active</a></li>
</ul>

`.u-link__colors(@pacific, @dark-green, @dark-pacific, @dark-red, @dark-gold)`

<ul class="link-color-example-5">
    <li><a href="#">Link</a></li>
    <li><a class="visited" href="#">Visited</a></li>
    <li><a class="hover" href="#">Hover</a></li>
    <li><a class="focus" href="#">Focus</a></li>
    <li><a class="active" href="#">Active</a></li>
</ul>

```
.u-link__colors(@pacific,  @dark-green, @dark-pacific, @dark-red, @dark-gold,
                @dark-red, @dark-gold,  @green,        @gold,     @red)
```

<ul class="link-color-example-10">
    <li><a href="#">Link</a></li>
    <li><a class="visited" href="#">Visited</a></li>
    <li><a class="hover" href="#">Hover</a></li>
    <li><a class="focus" href="#">Focus</a></li>
    <li><a class="active" href="#">Active</a></li>
</ul>

#### Link borders

<div class="u-mb15">
    <a class="u-link__border" href="#">
        Link borders forced on a link that doesn't normally get borders
    </a>
</div>

<p>
    <a class="u-link__no-border" href="#">
        Link borders removed from a link that does normally have borders
    </a>
</p>

<p>
    <a class="u-link__hover-border" href="#">
        Link with default borders removed from normal, visited, and active states,
        but still with borders on the hover and focus states
    </a>
</p>

### Small text utility

<p class="u-small-text">The fine print.</p>
<p>Here's a paragraph with some <small>inline small text</small> within.</p>

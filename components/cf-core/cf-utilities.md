---
layout: default
title:  "cf-utilities"
parent: "cf-core"
---

## Utilities

### Helper classes

#### Clearfix

<div class="u-clearfix">
    <div style="float:left; width:100%; height:60px; background:black;"></div>
</div>
<em>This text would normally flow up into the black box if the box above</em>

#### Visually hidden

<a href="#">
    <span class="cf-icon cf-icon-twitter-square"></span>
    <span class="u-visually-hidden">Share on Twitter</span>
</a>

The text "Share on Twitter" is only screenreader accessible above

#### Inline block

Adds a `.lt-ie8` fallback to hack inline block for IE 7 and below.

<div class="u-inline-block" style="background-color: lightblue; width: 50%"></div>

#### Float right

<div class="u-right"><h1>Float Right</h1></div>
<div class="block">&nbsp;</div>

#### Break word

Force word breaks within an element. Useful for small containers where text may over-run the width of the container.

<div style="width: 100px;">
    This link should break:
    <br>
    <a class="u-break-word" href="#">
        something@something.com
    </a>
    <br>
    <br>
    This link should not:
    <br>
    <a href="#">
        something@something.com
    </a>
</div>

_This only works in IE8 when the element with the .u-break-word class has layout. See <http://stackoverflow.com/questions/3997223/word-wrapbreak-word-not-working-in-ie8> for more information._

#### Margin utilities

Force a margin top or bottom on an element in pixels.

`.u-m[p][#]`

<h1 class="u-mb0" style="background-color:grey;">Heading with zero bottom margin</h1>

_`[p]` is the position, use `t` for top or `b` for bottom. `[#]` is the pixel value, available options are 0, 5, 10, 15, 20, 30, 45, 60_

#### Width utilities

Set the width of an element in percentages.

**NOTE: Inline style properties for demonstration only.**

<div class="u-w100pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w100pct</code>
</div>
<div class="u-w90pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w90pct</code>
</div>
<div class="u-w80pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w80pct</code>
</div>
<div class="u-w70pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w70pct</code>
</div>
<div class="u-w60pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w60pct</code>
</div>
<div class="u-w50pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w50pct</code>
</div>
<div class="u-w40pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w40pct</code>
</div>
<div class="u-w30pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w30pct</code>
</div>
<div class="u-w20pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w20pct</code>
</div>
<div class="u-w10pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w10pct</code>
</div>
<div class="u-w75pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w75pct</code>
</div>
<div class="u-w25pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w25pct</code>
</div>
<div class="u-w66pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w66pct</code>
</div>
<div class="u-w33pct" style="background: #f4edf3; margin-bottom: 1px;">
    <code>.u-w33pct</code>
</div>

#### Width-specific display

Show or hide content based on the current display size.

__NOTE: Inline style properties for demonstration only__

##### Show on mobile

Displays content on screen widths under 601px.

<div style="border: 1px solid black; height: 22px; padding: 5px;">
    <p class="u-show-on-mobile">Visible on mobile</p>
</div>

##### Hide on mobile

Hides content on screens widths under 601px.

<div style="border: 1px solid black; height: 22px; padding: 5px;">
    <p class="u-hide-on-mobile">Hidden on mobile</p>
</div>

### Mixins

#### Align with button

Align an element vertically with the text within a button that may be to either side.

```
.u-align-with-btn(@font-size: @base-font-size-px);
```

_Pass font-size as the argument for calculating spacing, default value is `@base-font-size-px`._

#### Flexible proportional containers

Utilize intrinsic ratios to create a flexible container that retains an aspect ratio. When image tags scale they retain their aspect ratio, but if you need a flexible video you will need to use this mixin.

_Read more about intrinsic rations: <http://alistapart.com/article/creating-intrinsic-ratios-for-video>_

```
.u-flexible-container-mixin(@width: 16, @height: 9);
```

In addition to the mixin, there are two default classes available for building 16:9 and 4:3 containers.

__NOTE: Inline style properties for demonstration only__

To create a 16:9 flexible video player, wrap the video element in an element with `u-flexible-container` and add the `u-flexible-container_inner` to the video element.

<div class="u-flexible-container">
    <video class="u-flexible-container_inner"
           style="background:#75787B;"
           controls>
    </video>
</div>

To create a flexible container with only a background (no inner video or object element), ommit the inner container.

<div class="u-flexible-container"
     style="background-image: url(http://placekitten.com/700/394);
            background-position: center center;
            background-repeat: no-repeat;"></div>

To create a 4:3 flexible video player, add the `__4_3` modifier to the container

<div class="u-flexible-container u-flexible-container__4-3">
    <video class="u-flexible-container_inner"
           style="background:#75787B;"
           controls>
    </video>
</div>

_When using the mixin, pass the width as the first argument, and the height as the second argument, default values are `16, 9`._

_Original mixin credit: <https://gist.github.com/craigmdennis/6655047>_

#### Link Modifiers

Modify link properties using the following mixins.

##### Link Colors

Calling the mixin without arguments will set the following states - default(pacific), :hover(pacific-50), :focus:(pacific), :visited teal, :active navy.

`u-link__colors()`

Passing a single argument into the mixin will set the color for the default, :visited, :hover, :focus, :active states.

`u-link__colors(@c)`

Passing two arguments into the mixin will set the color for the default, :visited, and :active states as the first argument, and :hover and :focus as the second argument.

`u-link__colors(@c, @h)`

Passing five arguments will set the color for the default, :visited, :hover, :focus, and :active states respectively.

`u-link__colors(@c, @v, @h, @f, @a)`

Passing ten arguments will set the text (default, :visited, :hover, :focus, and :active states in the first five arguments) and border colors (default, :visited, :hover, :focus, and :active states in the following five arguments) separately.

`u-link__colors(@c, @v, @h, @f, @a, @bc, @bv, @bh, @bf, @ba)`

__A base mixin of `u-link__colors-base()` exists, but please refrain from using this mixin directly in order to promote consistent naming throughout this project. If you need to set colors for all states of a link, use `.u-link__colors(@c, @v, @h, @f, @a)`.__

##### Link borders

Force the default bottom border on the default and :hover states.

`.u-link__border()`

Turn off the default bottom border on the default and :hover states.

`.u-link__no-border()`

Turn off the default bottom border on the default state but force a bottom border on the :hover state.

`.u-link__hover-border()`

##### Link children

Calling this mixin without arguments will set the default color for the hover state of a child within a link, without affecting the link itself.

`.u-link__hover-child()`

Passing a single argument into the mixin will set a custom color for the hover state of a child within a link, without affecting the link itself.

`.u-link__hover-child(@c)`

#### Small Text Utility

##### Class

Sets the element to 14px (in ems).

`.u-small-text`

_To be used on default 16px text only. To use on text set to another size, use the mixin below._

##### Mixin

Sets the element to 14px (in ems) based on the text size passed as `@context`.

`.u-small-text(@context)`

---
layout: default
title:  "cf-base"
parent: "cf-core"
---

## Base Typography

### Webfont mixins

<ul>
    <li class="webfont-regular-example">.u-webfont-regular()</li>
    <li class="webfont-italic-example">.u-webfont-italic()</li>
    <li class="webfont-medium-example">.u-webfont-medium()</li>
    <li class="webfont-demi-example">.u-webfont-demi()</li>
</ul>

### Type hierarchy

#### Default body type

<p>Lorem ipsum dolor sit amet, <em>consectetur adipisicing elit</em>, sed do eiusmod <strong>tempor incididunt</strong> ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

#### Heading level 1

<h1>Example heading element</h1>
<p class="h1">A non-heading element</p>

_Responsive heading. At small screen sizes, displays as Heading 2._

#### Heading level 2

<h2>Example heading element</h2>
<p class="h2">A non-heading element</p>

_Responsive heading. At small screen sizes, displays as Heading 3._

#### Heading level 3

<h3>Example heading element</h3>
<p class="h3">A non-heading element</p>

_Responsive heading. At small screen sizes, displays as Heading 4._

#### Heading level 4

<h4>Example heading element</h4>
<p class="h4">A non-heading element</p>

_Not a responsive heading._

#### Heading level 5

<h5>Example heading element</h5>
<p class="h5">A non-heading element</p>

_Not a responsive heading._

#### Heading level 6

<h6>Example heading element</h6>
<p class="h6">A non-heading element</p>

_Not a responsive heading._

#### Lead paragraph

<p class="lead-paragraph">Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

_Responsive text. Displays as a Heading 3 on large screens; displays at Heading 4 size (but still Regular weight) on small screens._

#### Display heading (aka "superheading")

<h1 class="superheading">Example display heading</h1>

### Body copy element vertical margins

<p>Paragraph margin example</p>
<p>Paragraph margin example</p>
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ul>
<p>Paragraph margin example</p>

- _Applies 15px bottom margin to all `p`, `ul`, `ol`, `dl`, `figure`, `table`, and `blockquote` elements._
- _Applies -5px top margin to lists following paragraphs to reduce margin between them to 10px._
- _Applies 8px bottom margin to list items that are not within a nav element._
- _Assumes that the font size of each of these items remains the default._

### Default links

<div class="u-mb30">
    <a href="#">Default</a>,
    <a href="#" class="visited">Visited</a>,
    <a href="#" class="hover">Hovered</a>,
    <a href="#" class="focus">Focused</a>,
    <a href="#" class="active">Active</a>
</div>

### Underlined links

Links are automatically underlined when they are a child of a `p`, `li`, or `dd`.

<p>
    <a href="#">A child of a paragraph</a>
</p>
<ul>
    <li>
        <a href="#">A child of a list item</a>
    </li>
</ul>
<dl>
    <dt>
        Definition list term
    </dt>
    <dd>
        <a href="#">A child of a definition list description</a>
    </dd>
</dl>
<nav class="u-mb30">
    <ul>
        <li><a href="#">Exception:</a></li>
        <li><a href="#">Links within a <code>nav</code> element</a></li>
        <li><a href="#">do not get underlined</a></li>
    </ul>
</nav>

### Lists

#### Unordered list

<p> Paragraph example for visual reference</p>
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ul>

#### Ordered list

<p>Paragraph example for visual reference</p>
<ol>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ol>

### Tables

<table>
    <thead>
        <tr>
            <th>Column 1 header</th>
            <th>Column 2 header</th>
            <th>Column 3 header</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1, column 1</td>
            <td>Row 1, column 2</td>
            <td>Row 1, column 3</td>
        </tr>
        <tr>
            <td>Row 2, column 1</td>
            <td>Row 2, column 2</td>
            <td>Row 2, column 3</td>
        </tr>
        <tr>
            <td>Row 3, column 1</td>
            <td>Row 3, column 2</td>
            <td>Row 3, column 3</td>
        </tr>
    </tbody>
</table>

### Block quote

<blockquote cite="link-to-source">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa
    similique fugit hic eligendi praesentium officiis illum optio iusto
    commodi eum tempore nisi ad in perferendis enim quo dolores.
    Reprehenderit similique earum quibusdam possimus vitae esse
    nesciunt mollitia sed beatae aliquid dolores iure a impedit quam
    minus eum modi illum ducimus eligendi eveniet labore non sequi
    voluptate et totam praesentium animi itaque asperiores dolorum
    sunt laudantium repellat nam commodi. Perspiciatis natus aliquam
    veniam officiis ducimus voluptatum ut necessitatibus non!
</blockquote>

## Base images

### Full-width images

Gives all images a default max-width of 100% of their container.

<img src="http://placekitten.com/1200/40" alt="">

### Figure

<figure>
    <img src="http://placekitten.com/340/320">
</figure>

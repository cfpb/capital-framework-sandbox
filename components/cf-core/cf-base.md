---
layout: default
title:  "cf-base"
parent: "cf-core"
---

## Base Typography

### Webfonts

Sets the font-stack, weight, and style of an element.

```
.webfont-regular();
.webfont-italic();
.webfont-medium();
.webfont-demi();
```

To use your own fonts in the webfont mixins, set your own font with the `@webfont-regular/italic/medium/demi` variables in your `theme-overrides.less` file.

_These mixins also add the appropriate .lt-ie9 overrides. .lt-ie9 overrides are necessary to override font-style and font-weight each time the webfont is used. These overrides are built into the webfont mixins so you get them automatically. Note that this requires you to use conditional classes on the <html> element: <https://github.com/h5bp/html5-boilerplate/blob/v4.3.0/doc/html.md#conditional-html-classes.>_

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

#### Default state

<a href="#">Default link style</a>

#### Visited state

<a href="#" class="visited">Visited link style</a>

#### Hovered state

<a href="#" class="hover">Visited link style</a>

#### Focused state

<a href="#" class="focus">Visited link style</a>

#### Active state

<a href="#" class="active">Visited link style</a>

_Note that the .visited, .hover, .focus, .active classes are for demonstration purposes only and should not be used in production._

### Underlined links

Links are automatically underlined when they are a child of a `p`, `li`, or `dd`. To enable them elsewhere, simply add a bottom-border-width to the link.

#### States

<p>
    <a href="#">Default</a>,
    <a href="#" class="visited">Visited</a>,
    <a href="#" class="hover">Hovered</a>,
    <a href="#" class="focus">Focused</a>,
    <a href="#" class="active">Active</a>
</p>

_Note that the .visited, .hover, .focus, .active classes are for demonstration purposes only and should not be used in production._

#### Underline conditions

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

#### Exceptions for underlined links

Links within a nav element are not underlined.

<nav>
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
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ul>

### Tables

#### Standard lable

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

_Note that the use of a block quote is to quote an external work. See `.pull-quote` if you need to highlight an excerpt from the current work._
_Note that it is best practice to document the URL of a quoted work using the cite attribute._


## Base forms

_Visit https://github.com/cfpb/cf-forms for advanced form field patterns._

### Form labels

#### Default label

<label>Form label</label>

#### Label for a radio or checkbox

<input type="radio" id="radio-input">
<label for="radio-input">Radio label</label>
<input type="checkbox" id="checkbox-input">
<label for="checkbox-input">Checkbox label</label>

### Form Elements

_Note that the `.focus` class is for documentation purposes only and should not be used in production._

#### `type="text"`

<input type="text" value="Lorem ipsum">
<input class="focus" type="text" value="Lorem ipsum">
<br><br>
<input placeholder="Lorem ipsum" type="text" value="">

#### `type="search"`

<input type="search" value="Lorem ipsum">
<input class="focus" type="search" value="Lorem ipsum">
<br><br>
<input placeholder="Lorem ipsum" type="search" value="">

#### `type="email"`

<input type="email" value="Lorem ipsum">
<input class="focus" type="email" value="Lorem ipsum">
<br><br>
<input placeholder="Lorem ipsum" type="email" value="">


#### `type="url"`

<input type="url" value="Lorem ipsum">
<input class="focus" type="url" value="Lorem ipsum">
<br><br>
<input placeholder="Lorem ipsum" type="url" value="">

#### `type="tel"`

<input type="tel" value="Lorem ipsum">
<input class="focus" type="tel" value="Lorem ipsum">
<br><br>
<input placeholder="Lorem ipsum" type="tel" value="">

#### `type="number"`

<input type="number" value="1000">
<input class="focus" type="number" value="1000">
<br><br>
<input placeholder="Lorem ipsum" type="number" value="">

#### `textarea`

<textarea>Lorem ipsum</textarea>
<textarea class="focus">Lorem ipsum</textarea>

#### Multiselect

<select multiple>
    <option value="option1">Lorem</option>
    <option value="option2">Ipsum</option>
    <option value="option3">Dolor</option>
    <option value="option4">Sit</option>
</select>
<select class="focus" multiple>
    <option value="option1">Lorem</option>
    <option value="option2">Ipsum</option>
    <option value="option3">Dolor</option>
    <option value="option4">Sit</option>
</select>

## Base images

### Full-width images

Gives all images a default max-width of 100% of their container.

<img src="http://placekitten.com/800/40" alt="">

### Figure

<figure>
    <img src="http://placekitten.com/340/320">
</figure>

### Bordered figure

<figure class="figure__bordered">
    <img src="http://placekitten.com/340/320">
</figure>

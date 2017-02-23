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

<p>For those who have seen the Earth from space, and for the hundreds and perhaps thousands more who will, the experience most certainly changes your perspective. The things that we share in our world are far more valuable than those which divide us.</p>
<ul>
    <li>Astronomy compels the soul to look upward, and leads us from this world to another.</li>
    <li>
        Space, the final frontier. These are the voyages of the Starship Enterprise. Its five-year mission: to explore strange new worlds, to seek out new life and new civilizations, to boldly go where no man has gone before. Starring:
        <ul>
            <li>William Shatner as Captain James T. Kirk</li>
            <li>Leonard Nimoy as Commander Spock</li>
            <li>DeForest Kelley as Dr. Leonard McCoy, who is a doctor, not anything else, dammit, Jim!</li>
        </ul>
    </li>
    <li>What was most significant about the lunar voyage was not that man set foot on the Moon but that they set eye on the earth.</li>
    <li>There can be no thought of finishing for ‘aiming for the stars.’ Both figuratively and literally, it is a task to occupy the generations. And no matter how much progress one makes, there is always the thrill of just beginning.</li>
    <li>Where ignorance lurks, so too do the frontiers of discovery and imagination.</li>
</ul>
<p>And now let us settle in for a long winter's ordered list example:</p>
<ol>
    <li>Item the first</li>
    <li>Item the second</li>
    <li>
        Item the third. This one has an unordered list nested inside of it!
        <ul>
            <li>Sub-bullet 1</li>
            <li>Sub-bullet 2</li>
            <li>Sub-bullet 3</li>
        </ul>
    </li>
    <li>Item the fourth</li>
    <li>Item the fifth</li>
    <li>Item the can you tell we're trying to get to double digits?</li>
    <li>Item the seventh</li>
    <li>Item the eighth</li>
    <li>Item the ninth</li>
    <li>Item the tenth</li>
</ol>

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

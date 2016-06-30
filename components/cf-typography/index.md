---
layout: default
title:  "cf-typography"
parent: "Components"
---

## Text


### Pull quote

#### Default pull quote
<div class="block block__flush-top">
    <aside class="pull-quote">
        <div class="pull-quote_body">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Cum corrupti tempora nam nihil qui mollitia consectetur
            corporis nemo culpa dolorum!
        </div>
        <footer>
            <cite class="pull-quote_citation">
                - Author Name
            </cite>
        </footer>
    </aside>
</div>

#### Large pull quote
<div class="block block__flush-top">
    <aside class="pull-quote pull-quote__large">
        <div class="pull-quote_body">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Cum corrupti tempora nam nihil qui mollitia consectetur
            corporis nemo culpa dolorum!
        </div>
        <footer>
            <cite class="pull-quote_citation">
                - Author Name
            </cite>
        </footer>
    </aside>
</div>


### Micro copy

#### Standard micro copy

<p class="micro-copy">
    Lorem ipsum dolor sit amet
</p>


#### Large micro copy

<p class="micro-copy">
    Lorem ipsum dolor sit amet
</p>


### Short description

#### .short-desc

<p class="short-desc">I am short description.</p>

#### .short-desc__large (modifier)

<p class="short-desc short-desc__large">I am large short description.</p>


### Date

#### Default date

<span class="date">
    Nov 4, 2013
</span>


### Category slug

#### Default category slug

<a href="#" class="category-slug">
    <span class="category-slug_icon cf-icon cf-icon-dialogue"></span>
    <span class="u-visually-hidden">Category:</span>
    Consumer finance
</a>


### Header slug

#### Default header slug
<div class="block block__flush-top">
    <h2 class="header-slug">
        <span class="header-slug_inner">
            Blog summary
        </span>
    </h2>
</div>


### Padded header

#### Default padded header
<div class="block block__flush-top">
    <h2 class="padded-header">
        Header
    </h2>
</div>

### Fancy slug

#### Default fancy slug

<div class="block block__flush-top">
<h2 class="fancy-slug">
    <span class="fancy-slug_text">
        <span class="fancy-slug_ribbon-left"></span>
        Watchroom
        <span class="fancy-slug_ribbon-right"></span>
    </span>
</h2>
</div>


### Meta header

#### Default meta header
<div class="block block__flush-top">
    <div class="meta-header">
        <span class="meta-header_right date">
            Nov 4, 2013
        </span>
        <a href="#" class="meta-header_left category-slug">
            <span class="cf-icon cf-icon-credit-card"></span>
            Consumer finance
        </a>
    </div>
</div>


#### Alternate meta header arrangements
<div class="block block__flush-top">
    <div class="meta-header">
        <a href="#" class="meta-header_right category-slug">
            <span class="cf-icon cf-icon-credit-card"></span>
        </a>
        <span class="meta-header_left date">
            Nov 4, 2013
        </span>
    </div>
</div>

<div class="block block__flush-top">
    <div class="meta-header">
        <a href="#" class="meta-header_left category-slug">
            <span class="cf-icon cf-icon-credit-card"></span>
            Consumer finance
        </a>
    </div>
</div>


## Links


### Links with icons

- Styles to enable adding an icon to a link and preventing the link's underline from extending under the icon.
- For the underlined icon prevention to work, you must wrap the link text with a `span.icon-link_text`. There can be no whitespace between the text and the opening and closing span tags.

<p>
    For more information, email
    <a class="icon-link icon-link__mail" href="#">
        <span class="icon-link_text">john.smith@cfpb.gov</span>
    </a>.
    Alternatively, you can
    <a class="icon-link icon-link__download" href="#">
        <span class="icon-link_text">download the info sheet</span>
    </a>.
    Oh, you might also want to visit this
    <a class="icon-link icon-link__external-link" href="#">
        <span class="icon-link_text">other organization's website</span>
    </a> for further details.
</p>
<a class="icon-link icon-link__right" href="#">
    Visit another section of our site
</a>

#### Links with icons on the left (modifier)

<a class="icon-link icon-link__mail icon-link__before" href="#">
    <span class="icon-link_text">john.smith@cfpb.gov</span>
</a><br>
<a class="icon-link icon-link__phone icon-link__before" href="#">
    (123) 456-7890
</a>


#### Non-wrapping icon links

<p>
    For more information, email
    <a class="icon-link icon-link__mail icon-link__no-wrap" href="#">
        <span class="icon-link_text">john.smith@cfpb.gov</span>
    </a>.
</p>


### Styled link

<a class="styled-link" href="#">
    Default styled link
</a>


### Jump link

<a class="jump-link" href="#">
    <span class="jump-link_text">Default jump link</span>
</a>


#### .jump-link__large (modifier)

<a class="jump-link jump-link__large" href="#">
    <span class="jump-link_text">Large jump link</span>
</a>


#### .jump-link__<icon> (modifier)

<a class="jump-link jump-link__right" href="#">
    <span class="jump-link_text">Jump link using the right icon from cf-icons</span>
</a>


#### .jump-link__before (modifier)

<a class="jump-link jump-link__left jump-link__before" href="#">
    <span class="jump-link_text">Jump link with icon on left</span>
</a>


#### .jump-link__bg (modifier)

<a class="jump-link jump-link__bg" href="#">
    <span class="jump-link_text">Jump link with grey background and
        solid borders on small screens</span>
</a>


### Block link


#### .block-link

<a class="block-link" href="#">
    Default block link
</a>


## Lists

### Unstyled list modifier

#### Default example

<ul class="list list__unstyled">
    <li class="list_item">
        <a class="list_link">List item 1</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 2</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 3</a>
    </li>
</ul>


### Spaced list modifier

#### Default example

<ul class="list list__spaced">
    <li class="list_item">
        <a class="list_link">List item 1</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 2</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 3</a>
    </li>
</ul>


### Spaced list item modifier

#### Default example

<ul class="list">
    <li class="list_item">
        <a class="list_link">List item 1</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 2</a>
    </li>
    <li class="list_item list_item__spaced">
        <a class="list_link">List item 3</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 4</a>
    </li>
</ul>


### Horizontal list modifier

#### Default example

<ul class="list list__horizontal">
    <li class="list_item">
        <a class="list_link">List item 1</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 2</a>
    </li>
    <li class="list_item">
        <a class="list_link">List item 3</a>
    </li>
</ul>


### Icon list modifier

- Set up a list with icons on the left, in place of bullets.
- Will need some more work to allow lines to wrap.

#### Default example

<ul class="list list__icons">
    <li class="list_item">
        <span class="cf-icon cf-icon-email list_icon"></span>
        List item 1
    </li>
    <li class="list_item">
        <span class="cf-icon cf-icon-phone list_icon"></span>
        List item 1
    </li>
    <li class="list_item">
        <span class="cf-icon cf-icon-fax list_icon"></span>
        List item 1
    </li>
</ul>



### Link list modifier

#### Default example

<ul class="list list__links">
    <li class="list_item">
        <a class="list_link" href="#">List item 1</a>
    </li>
    <li class="list_item">
        <a class="list_link" href="#">List item 2</a>
    </li>
    <li class="list_item">
        <a class="list_link" href="#">List item 3</a>
    </li>
</ul>


#### Link list with icons

<ul class="list list__links list__icons">
    <li class="list_item">
        <a class="list_link icon-link icon-link__before icon-link__email"
           href="#">
            <span class="icon-link_text">List item 1</span>
        </a>
    </li>
    <li class="list_item">
        <a class="list_link icon-link icon-link__before icon-link__phone"
           href="#">
            <span class="icon-link_text">List item 2</span>
        </a>
    </li>
    <li class="list_item">
        <a class="list_link icon-link icon-link__before icon-link__fax"
           href="#">
            <span class="icon-link_text">List item 3</span>
        </a>
    </li>
</ul>

#### Branded list

<ul class="list__branded">
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ul>

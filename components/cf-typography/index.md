---
layout: default
title:  "cf-typography"
parent: "Components"
---


## Running Text

### Micro copy

<p class="a-micro-copy">
    Lorem ipsum dolor sit amet
</p>

### Date

<span class="a-date">
    Nov 4, 2013
</span>

### Pull quote

#### Default pull quote
<aside class="m-pull-quote">
    <p class="m-pull-quote_body">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Cum corrupti tempora nam nihil qui mollitia consectetur
        corporis nemo culpa dolorum!
    </p>
    <footer>
        <cite class="m-pull-quote_citation">
            - Author Name
        </cite>
    </footer>
</aside>

#### Large pull quote
<aside class="m-pull-quote m-pull-quote__large">
    <div class="m-pull-quote_body">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Cum corrupti tempora nam nihil qui mollitia consectetur
        corporis nemo culpa dolorum!
    </div>
    <footer>
        <cite class="m-pull-quote_citation">
            - Author Name
        </cite>
    </footer>
</aside>


## Headings

### Heading with icon

<a href="#" class="a-heading a-heading__icon">
    <span class="cf-icon cf-icon-dialogue"></span>
    Consumer finance
</a>


## Headers

### Slug header

<header class="m-slug-header">
    <h2 class="a-heading">
        Blog summary
    </h2>
</header>

### Meta header

#### Default meta header
<header class="m-meta-header">
    <div class="m-meta-header_right">
        <span class="a-date">
            Nov 4, 2013
        </span>
    </div>
    <div class="m-meta-header_left">
        <span class="u-visually-hidden">Categories: </span>
        <a href="#" class="a-heading a-heading__icon">
            <span class="cf-icon cf-icon-credit-card"></span>
            Consumer finance
        </a>
        |
        <a href="#" class="a-heading a-heading__icon">
            <span class="cf-icon cf-icon-credit-card"></span>
            Consumer finance
        </a>
    </div>
</header>

#### Example in a cfgov-refresh Post Preview

<div class="o-post-preview">
    <header class="m-meta-header">
        <div class="m-meta-header_right">
            <span class="a-date">
                Nov 4, 2013
            </span>
        </div>
        <div class="m-meta-header_left">
            <span class="u-visually-hidden">Categories: </span>
            <a href="#" class="a-heading a-heading__icon">
                <span class="cf-icon cf-icon-credit-card"></span>
                Consumer finance
            </a>
            |
            <a href="#" class="a-heading a-heading__icon">
                <span class="cf-icon cf-icon-credit-card"></span>
                Consumer finance
            </a>
        </div>
    </header>
    <h3>
        <a href="http://www.consumerfinance.gov/about-us/blog/administrador-del-acuerdo-de-provident-planea-ponerse-en-contacto-con-prestatarios-elegibles-proximamente/">
            Administrador del Acuerdo de Provident planea ponerse en contacto con prestatarios elegibles próximamente
        </a>
    </h3>
    <p>Prepaid cards can look and act like other types of cards, but they haven’t always had the same protections. Our new rule will help make prepaid cards and other prepaid accounts safer to use.</p>
    <div class="post_meta">
        <span class="o-post-preview_byline">
            By <a href="http://www.consumerfinance.gov/about-us/blog/?filter1_authors=david-silberman">David Silberman</a>
        </span>

        <div class="tags tags__hide-heading ">
            <span class="u-visually-hidden">Topics:</span>
            <ul class="tags_list">
                <li class="tags_tag">
                    <a href="http://www.consumerfinance.gov/about-us/blog/?filter1_topics=prepaid-cards" class="tags_link">
                        <span class="tags_bullet" aria-hidden="true">•</span>
                        Prepaid cards
                    </a>
                </li>
                <li class="tags_tag">
                    <a href="http://www.consumerfinance.gov/about-us/blog/?filter1_topics=rulemaking" class="tags_link">
                        <span class="tags_bullet" aria-hidden="true">•</span>
                        Rulemaking
                    </a>
                </li>
            </ul>
        </div>

    </div>
</div>


## Links

### Links with icons

For more information, email
<a class="a-link a-link__icon a-link__mail" href="#">
    <span class="a-link_text">john.smith@cfpb.gov</span>
</a>.
Alternatively, you can
<a class="a-link a-link__icon a-link__download" href="#">
    <span class="a-link_text">download the info sheet</span>
</a>.
Oh, you might also want to visit this
<a class="a-link a-link__icon a-link__external-link" href="#">
    <span class="a-link_text">other organization's website</span>
</a> for further details.

#### Links with icons on the left (modifier)

<a class="a-link a-link__icon a-link__mail a-link__before" href="#">
    <span class="a-link_text">john.smith@cfpb.gov</span>
</a><br>
<a class="a-link a-link__icon a-link__phone a-link__before" href="#">
    <span class="a-link_text">(123) 456-7890</span>
</a>

#### Non-wrapping icon links

For more information, email
<a class="a-link a-link__icon a-link__mail a-link__no-wrap" href="#">
    <span class="a-link_text">john.smith@cfpb.gov</span>
</a>.

### Jump link

<a class="a-link
          a-link__jump
          a-link__right" href="#">
    <span class="a-link_text">Default jump link</span>
</a>


#### Jump link with large link modifier

<a class="a-link
          a-link__jump
          a-link__large
          a-link__right" href="#">
    <span class="a-link_text">Large jump link</span>
</a>


#### Jump link with before link modifier

<a class="a-link
          a-link__jump
          a-link__before
          a-link__left" href="#">
    <span class="a-link_text">Jump link with icon on left</span>
</a>


#### Jump link with bg modifier (only visible on small screens)

<a class="a-link
          a-link__jump
          a-link__bg
          a-link__right" href="#">
    <span class="a-link_text">Jump link with grey background and
        solid borders on small screens</span>
</a>


### Block link

<a class="a-link__block" href="#">
    Default block link
</a>


## Lists

### Unstyled list modifier

<ul class="m-list m-list__unstyled">
    <li class="m-list_item">List item 1</li>
    <li class="m-list_item">List item 2</li>
    <li class="m-list_item">List item 3</li>
</ul>


### Spaced list modifier

#### Default example
<ul class="m-list m-list__spaced">
    <li class="m-list_item">List item 1</li>
    <li class="m-list_item">List item 2</li>
    <li class="m-list_item">List item 3</li>
</ul>

#### Nested list example

<ul class="m-list m-list__spaced">
    <li class="m-list_item">List item 1</li>
    <li class="m-list_item">
        List item 2
        <ul class="m-list m-list__spaced">
            <li class="m-list_item">List item 2a</li>
            <li class="m-list_item">List item 2b</li>
            <li class="m-list_item">List item 2c</li>
        </ul>
    </li>
    <li class="m-list_item">List item 3</li>
</ul>

### Horizontal list modifier

<ul class="m-list m-list__horizontal">
    <li class="m-list_item">List item 1</li>
    <li class="m-list_item">List item 2</li>
    <li class="m-list_item">List item 3</li>
</ul>

### Link list modifier

<ul class="m-list m-list__links">
    <li class="m-list_item">
        <a class="m-list_link" href="#">List item 1</a>
    </li>
    <li class="m-list_item">
        <a class="m-list_link" href="#">List item 2</a>
    </li>
    <li class="m-list_item">
        <a class="m-list_link" href="#">List item 3</a>
    </li>
</ul>

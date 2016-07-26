---
layout: default
title:  "cf-layout"
parent: "Components"
---

## Content layouts

### Standard content columns
<div class="block">
    <div class="content-l">
        <div class="content-l_col content-l_col-1">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Full-width column (spans 12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-2">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Half-width column (spans 6/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-2">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Half-width column (spans 6/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-3">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Third-width column (spans 4/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-3">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Third-width column (spans 4/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-3">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Third-width column (spans 4/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-2-3">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Two thirds-width column (spans 8/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-3">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Third-width column (spans 4/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-4">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;">
                Quarter width column (spans 3/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-3-4">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;">
                Three-quarter width column (spans 9/12 columns)
            </div>
        </div>
    </div>
</div>

### Large gutters modifier
<div class="block">
    <div class="content-l content-l__main  content-l__large-gutters">
        <div class="content-l_col content-l_col-1">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Full-width column (spans 12 columns)
            </div>
        </div>
    </div>
    <div class="content-l content-l__main  content-l__large-gutters">
        <div class="content-l_col content-l_col-1-2">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Half-width column (spans 6/12 columns)
            </div>
        </div>
        <div class="content-l_col content-l_col-1-2">
            <div style="background: #F1F2F2;
                        text-align: center;
                        padding: 8px;
                        margin-bottom: 4px;">
                Half-width column (spans 6/12 columns)
            </div>
        </div>
    </div>
</div>

## Content layout column dividers
<div class="block">
    <div class="content-l content-l__large-gutters">
        <div class="content-l_col content-l_col-1-2">
            <img src="http://placekitten.com/600/320" alt="Placeholder image">
            <br>
            Half-width column (spans 6/12 columns)
        </div>
        <div class="content-l_col content-l_col-1-2 content-l_col__before-divider">
            <img src="http://placekitten.com/600/320" alt="Placeholder image">
            <br>
            Half-width column (spans 6/12 columns)
        </div>
    </div>
    <br>
    <div class="content-l content-l__large-gutters">
        <div class="content-l_col content-l_col-1-3">
            Third-width column (spans 4/12 columns)
        </div>
        <div class="content-l_col content-l_col-1-3 content-l_col__before-divider">
            Third-width column (spans 4/12 columns)
        </div>
        <div class="content-l_col content-l_col-1-3 content-l_col__before-divider">
            Third-width column (spans 4/12 columns)
        </div>
    </div>
</div>


## Content bar
<div class="block">
    <div class="content_bar"></div>
</div>

## Content line

A 1 pixel edge to edge bar that can divide content.
<div class="block">
    <div class="content_line"></div>
</div>

## Main content and sidebar

<div class="block">
    <main class="content" role="main">
        <section class="content_hero" style="background: #E3E4E5">
            Content hero
        </section>
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <section class="content_main">
                Main content area
            </section>
            <aside class="content_sidebar" style="background: #F1F2F2">
                Sidebar
            </aside>
        </div>
    </main>
</div>

## Left-hand navigation layout

<div class="block">
    <main class="content content__1-3" role="main">
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <aside class="content_sidebar">
                Section navigation
            </aside>
            <section class="content_main">
                <h2>Main content area</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Cum corrupti tempora nam nihil qui mollitia consectetur
                    corporis nemo culpa dolorum! Laborum at eos deleniti
                    consequatur itaque officiis debitis quisquam! Provident!
                </p>
            </section>
        </div>
    </main>
    <footer class="footer" role="contentinfo">
        <div class="wrapper">
            Footer
        </div>
    </footer>
</div>

## Right-hand sidebar layout
<div class="block">
    <main class="content content__2-1" role="main">
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <section class="content_main">
                <h2>Main content area</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Cum corrupti tempora nam nihil qui mollitia consectetur
                    corporis nemo culpa dolorum! Laborum at eos deleniti
                    consequatur itaque officiis debitis quisquam! Provident!
                </p>
            </section>
            <aside class="content_sidebar" style="background: #F1F2F2">
                Sidebar
            </aside>
        </div>
    </main>
    <footer class="footer" role="contentinfo">
        <div class="wrapper">
            Footer
        </div>
    </footer>
</div>

## Narrow content column option

<div class="block">
    <main class="content content__2-1" role="main">
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <section class="content_main content_main__narrow">
                <h2>Main content area</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Cum corrupti tempora nam nihil qui mollitia consectetur
                    corporis nemo culpa dolorum! Laborum at eos deleniti
                    consequatur itaque officiis debitis quisquam! Provident!
                </p>
            </section>
            <aside class="content_sidebar" style="background: #F1F2F2">
                Sidebar
            </aside>
        </div>
    </main>
    <footer class="footer" role="contentinfo">
        <div class="wrapper">
            Footer
        </div>
    </footer>
</div>

## Flush bottom modifier
<div class="block">
    <main class="content content__1-3" role="main">
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <aside class="content_sidebar content__flush-bottom">
                Side with no bottom padding...
            </aside>
            <section class="content_main content__flush-bottom">
                Main content with no bottom padding...
                <div class="block
                            block__flush-bottom
                            block__flush-sides
                            block__bg">
                    .content__flush-bottom is very useful when you have a
                    content block inside of .content_main with a background
                    and flush sides.
                </div>
            </section>
        </div>
    </main>
    <footer class="footer" role="contentinfo">
        <div class="wrapper">
            Footer
        </div>
    </footer>
</div>

## Flush top modifier (only on small screens)
<div class="block">
    <main class="content content__1-3" role="main">
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <aside class="content_sidebar content__flush-top-on-small">
                Side with no top padding on small screens...
            </aside>
            <section class="content_main">
                Main content
            </section>
        </div>
    </main>
    <footer class="footer" role="contentinfo">
        <div class="wrapper">
            Footer
        </div>
    </footer>
</div>

## Flush all modifier (only on small screens)

<div class="block">
    <main class="content content__1-3" role="main">
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <aside class="content_sidebar content__flush-all-on-small">
                Side with no padding or border-based gutters on small screens...
            </aside>
            <section class="content_main">
                Main content
            </section>
        </div>
    </main>
    <footer class="footer" role="contentinfo">
        <div class="wrapper">
            Footer
        </div>
    </footer>
</div>

## Block

Main content...

<div class="block" style="background-color: #C3BABA">
    Content block 1
</div>
<div class="block" style="background-color: #E9E3E6">
    Content block 2
</div>
<div class="block" style="background-color: #B2B2B2">
    Content block 3
</div>


### Border-top modifier

Adds top border to `.block`.

Main content...

<div class="block block__border-top" style="background-color: #E9E3E6">
    Content block with top border.
</div>


### Border-right modifier

Adds right border to `.block`.

Main content...
<div class="block block__border-right" style="background-color: #E9E3E6">
    Content block with right border.
</div>


### Border-bottom modifier

Main content...
<div class="block block__border-bottom" style="background-color: #E9E3E6">
    Content block with bottom border.
</div>


### Border-left modifier

Main content...
<div class="block block__border-left" style="background-color: #E9E3E6">
    Content block with left border.
</div>

### Border modifier

Main content...
<div class="block block__border" style="background-color: #E9E3E6">
    Content block with borders on all sides.
</div>


### Flush-top modifier
<div class="block">
    <div style="background-color: grey">
        Plain content.
    </div>
    <div class="block block__flush-top" style="background-color: #E9E3E6">
        Content block with no top margin.
    </div>
    <div style="background-color: grey">
        Plain content.
    </div>
</div>



### Flush-bottom modifier

<div class="block">
    <div style="background-color: grey">
        Plain content.
    </div>
    <div class="block block__flush-bottom" style="background-color: #E9E3E6">
        Content block with no bottom margin.
    </div>
    <div style="background-color: grey">
        Plain content.
    </div>
</div>

### Flush-sides modifier

<div class="block">
    <main class="content content__1-3" role="main">
        <div class="content_wrapper">
            <aside class="content_sidebar">
                Section navigation
            </aside>
            <section class="content_main">
                Main content...
                <aside class="block block__flush-sides" style="background-color: #E9E3E6">
                    Content block with no side margins. Content block with no side margins. Content block with no side margins. Content block with no side margins.
                </aside>
            </section>
        </div>
    </main>
</div>

### Flush modifier

<div class="block">
    <main class="content content__1-3" role="main">
        <div class="content_wrapper">
            <aside class="content_sidebar">
                Section navigation
            </aside>
            <section class="content_main">
                Main content...
                <aside class="block block__flush" style="background-color: #E9E3E6">
                    Content block with no side margins. Content block with no side margins. Content block with no side margins. Content block with no side margins.
                </aside>
            </section>
            </section>
        </div>
    </main>
</div>

### Background modifier

<div class="block">
    Main content...
    <div class="block block__bg">
        Content block with a background
    </div>
</div>

### Background and flush-sides modifier combo example

<div class="block">
    <main class="content content__1-3" role="main">
        <div class="content_wrapper">
            <aside class="content_sidebar">
                Section navigation
            </aside>
            <section class="content_main content__flush-bottom">
                Main content...
                <div class="block block__flush-sides block__bg">
                    Content block with a background and flush sides
                </div>
            </section>
        </div>
    </main>
</div>

### Padded-top modifier

<div class="block">
    Main content...
    <div class="block block__padded-top block__border-top" style="background-color: #E9E3E6">
        Content block with reduced top margin & added top padding
        and border.
    </div>
</div>


### Padded-bottom modifier

Breaks bottom margin into margin & padding. Useful in combination with
`block__border-bottom` to add padding between block contents & border.

Main content...
<div class="block block__padded-bottom block__border-bottom" style="background-color: #E9E3E6">
    Content block with reduced bottom margin & added bottom padding
    and border.
</div>


### Sub blocks

<div class="block block__sub">
    <div style="background: #F1F2F2; padding: 8px;">
        Sub content block
    </div>
</div>
<div class="block block__sub">
    <div style="background: #F1F2F2; padding: 8px;">
        Sub content block
    </div>
</div>
<div class="block block__sub">
    <div style="background: #F1F2F2; padding: 8px;">
        Sub content block
    </div>
</div>


### Mixing content blocks with content layouts

<div class="content-l">
    <div class="block content-l_col content-l_col-1-2">
        <div style="background: #F1F2F2; padding: 8px;">
            Content block that is also a content column.
            Notice how my top margins only exist on smaller screens when
            I need to stack vertically.
        </div>
    </div>
    <div class="block content-l_col content-l_col-1-2">
        <div style="background: #F1F2F2; padding: 8px;">
            Content block that is also a content column.
            Notice how my top margins only exist on smaller screens when
            I need to stack vertically.
        </div>
    </div>
</div>


## Bleedbar sidebar styling

<div class="block">
    <main class="content content__2-1 content__bleedbar" role="main">
        <section class="content_hero" style="background: #E3E4E5">
            Content hero
        </section>
        <div class="content_bar"></div>
        <div class="content_wrapper">
            <section class="content_main">
                Main content area
            </section>
            <aside class="content_sidebar">
                Bleeding sidebar
            </aside>
        </div>
    </main>
</div>


## cf-grid helpers

### Featured content module

Featured content module, like a hero, consists of headline/text/optional call to action along with a visual. It is intended to be used in a main content column next to a sidebar.

Text is full width & displayed above the visual in the default/mobile view.
At larger screen sizes, the text occupies a fixed portion of the screen (equal to the width of 5 of 12 columns at 701px & 3 of 12 columns at 901px for desktop).
The visual occupies the remaining space.
The visual should be 640x360 (16x9 ratio) and resize to fit the height of the FCM with a static width and is anchored left when it becomes too wide for the available space.

<section class="block block__border block__flush o-featured-content-module">
    <div class="o-featured-content-module_text">
        <div class="category-slug">
            <span class="o-featured-content-module_icon cf-icon cf-icon-speech-bubble">
</span> Featured </div>
        <h2>Feature title</h2>
        <p>Lorem ipsum dolor sit amet, ei ius adhuc inani iudico, labitur instructior ex pri. Cu pri inani constituto, cum aeque noster commodo cu.</p>
        <a class="jump-link jump-link__underline"> <span class="jump-link_text">Read more about the feature</span> </a>
    </div>
    <div class="o-featured-content-module_visual"> <img class="o-featured-content-module_img" src="http://placekitten.com/g/540/270"> </div>
</section>


### Featured content module - Right-anchored image

<section class="block block__border block__flush o-featured-content-module o-featured-content-module__right">
    <div class="o-featured-content-module_text">
        <div class="category-slug">
            <span class="o-featured-content-module_icon cf-icon cf-icon-speech-bubble">
</span> Featured (Map)</div>
        <h2>Feature title</h2>
        <p>Lorem ipsum dolor sit amet, ei ius adhuc inani iudico, labitur instructior ex pri. Cu pri inani constituto, cum aeque noster commodo cu.</p>
        <a class="jump-link jump-link__underline"> <span class="jump-link_text">Read more about the feature</span> </a>
    </div>
    <div class="o-featured-content-module_visual"> <img class="o-featured-content-module_img" src="http://placekitten.com/g/540/270"> </div>
</section>


### Featured content module - Center-anchored image

<section class="block block__border block__flush o-featured-content-module o-featured-content-module__center">
    <div class="o-featured-content-module_text">
        <div class="category-slug">
            <span class="o-featured-content-module_icon cf-icon cf-icon-speech-bubble">
</span> Featured (Video) </div>
        <h2>Feature title</h2>
        <p>Lorem ipsum dolor sit amet, ei ius adhuc inani iudico, labitur instructior ex pri. Cu pri inani constituto, cum aeque noster commodo cu.</p>
        <a class="jump-link jump-link__underline"> <span class="jump-link_text">Read more about the feature</span> </a>
    </div>
    <div class="o-featured-content-module_visual"> <img class="o-featured-content-module_img" src="http://placekitten.com/g/540/270"> </div>
</section>


## Heroes

[See the full-width hero demo page](heroes.html)

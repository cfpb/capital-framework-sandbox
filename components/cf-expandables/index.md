---
layout: default
title:  "cf-expandables"
parent: "Components"
---

## Original Documentation Markup

### Default state

<div class="o-expandable o-expandable__padded">
    <button class="o-expandable_header o-expandable_target" title="Expand content">
        <span class="o-expandable_header-left o-expandable_label">
            Expandable Header
        </span>
        <span class="o-expandable_header-right o-expandable_link">
            <span class="o-expandable_cue o-expandable_cue-open">
                Show
                <span class="cf-icon cf-icon-plus-round"></span>
            </span>
            <span class="o-expandable_cue o-expandable_cue-close">
                Hide
                <span class="cf-icon cf-icon-minus-round"></span>
            </span>
        </span>
    </button>
    <div class="o-expandable_content">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>

### Default state (open on load)

<div class="o-expandable o-expandable__padded">
    <button class="o-expandable_header o-expandable_target" title="Expand content">
        <span class="o-expandable_header-left o-expandable_label">
            Expandable Header
        </span>
        <span class="o-expandable_header-right o-expandable_link">
            <span class="o-expandable_cue o-expandable_cue-open">
                Show
                <span class="cf-icon cf-icon-plus-round"></span>
            </span>
            <span class="o-expandable_cue o-expandable_cue-close">
                Hide
                <span class="cf-icon cf-icon-minus-round"></span>
            </span>
        </span>
    </button>
    <div class="o-expandable_content o-expandable_content__onload-open">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>



### Barebones Expandable

<div class="o-expandable">
    <button class="o-expandable_target" title="Expand content">
        <span class="o-expandable_cue o-expandable_cue-open">
            Show
        </span>
        <span class="o-expandable_cue o-expandable_cue-close">
            Hide
        </span>
    </button>
    <div class="o-expandable_content">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>


## Expandable groups

<div class="o-expandable-group">
    <div class="o-expandable o-expandable__padded">
        <button class="o-expandable_header o-expandable_target" title="Expand content">
            <span class="o-expandable_header-left o-expandable_label">
                Expandable Header 1
            </span>
            <span class="o-expandable_header-right o-expandable_link">
                <span class="o-expandable_cue o-expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="o-expandable_cue o-expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="o-expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="o-expandable o-expandable__padded">
        <button class="o-expandable_header o-expandable_target" title="Expand content">
            <span class="o-expandable_header-left o-expandable_label">
                Expandable Header 2
            </span>
            <span class="o-expandable_header-right o-expandable_link">
                <span class="o-expandable_cue o-expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="o-expandable_cue o-expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="o-expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="o-expandable o-expandable__padded">
        <button class="o-expandable_header o-expandable_target" title="Expand content">
            <span class="o-expandable_header-left o-expandable_label">
                Expandable Header 3
            </span>
            <span class="o-expandable_header-right o-expandable_link">
                <span class="o-expandable_cue o-expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="o-expandable_cue o-expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="o-expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
</div>


### Accordion-style group

<div class="o-expandable-group o-expandable-group__accordion" >
    <div class="o-expandable o-expandable__padded">
        <button class="o-expandable_header o-expandable_target" title="Expand content">
            <span class="o-expandable_header-left o-expandable_label">
                Expandable Header 1
            </span>
            <span class="o-expandable_header-right o-expandable_link">
                <span class="o-expandable_cue o-expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="o-expandable_cue o-expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="o-expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="o-expandable o-expandable__padded">
        <button class="o-expandable_header o-expandable_target" title="Expand content">
            <span class="o-expandable_header-left o-expandable_label">
                Expandable Header 2
            </span>
            <span class="o-expandable_header-right o-expandable_link">
                <span class="o-expandable_cue o-expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="o-expandable_cue o-expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="o-expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="o-expandable o-expandable__padded">
        <button class="o-expandable_header o-expandable_target" title="Expand content">
            <span class="o-expandable_header-left o-expandable_label">
                Expandable Header 3
            </span>
            <span class="o-expandable_header-right o-expandable_link">
                <span class="o-expandable_cue o-expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="o-expandable_cue o-expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="o-expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
</div>

---
layout: default
title:  "cf-expandables"
parent: "Components"
---

## Original Documentation Markup

### Default state

<div class="expandable expandable__padded">
    <button class="expandable_header expandable_target" title="Expand content">
        <span class="expandable_header-left expandable_label">
            Expandable Header
        </span>
        <span class="expandable_header-right expandable_link">
            <span class="expandable_cue-open">
                Show
                <span class="cf-icon cf-icon-plus-round"></span>
            </span>
            <span class="expandable_cue-close">
                Hide
                <span class="cf-icon cf-icon-minus-round"></span>
            </span>
        </span>
    </button>
    <div class="expandable_content">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing
            elit. Neque ipsa voluptatibus soluta nobis unde quisquam
            temporibus magnam debitis quidem. Ducimus ratione
            corporis nesciunt earum vel est quaerat blanditiis
            dolore ipsa?
        </p>
    </div>
</div>


### Barebones expandable

<div class="expandable">
    <button class="expandable_target" title="Expand content">
        <span class="expandable_cue-open">
            Show
        </span>
        <span class="expandable_cue-close">
            Hide
        </span>
    </button>
    <div class="expandable_content">
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

<div class="expandable-group">
    <div class="expandable-group_header">Expandable group header</div>
    <div class="expandable expandable__padded">
        <button class="expandable_header expandable_target" title="Expand content">
            <span class="expandable_header-left expandable_label">
                Expandable Header 1
            </span>
            <span class="expandable_header-right expandable_link">
                <span class="expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="expandable expandable__padded">
        <button class="expandable_header expandable_target" title="Expand content">
            <span class="expandable_header-left expandable_label">
                Expandable Header 2
            </span>
            <span class="expandable_header-right expandable_link">
                <span class="expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="expandable expandable__padded">
        <button class="expandable_header expandable_target" title="Expand content">
            <span class="expandable_header-left expandable_label">
                Expandable Header 3
            </span>
            <span class="expandable_header-right expandable_link">
                <span class="expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="expandable_content">
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

<div class="expandable-group" data-accordion="true">
    <div class="expandable-group_header">Expandable group header</div>
    <div class="expandable expandable__padded">
        <button class="expandable_header expandable_target" title="Expand content">
            <span class="expandable_header-left expandable_label">
                Expandable Header 1
            </span>
            <span class="expandable_header-right expandable_link">
                <span class="expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="expandable expandable__padded">
        <button class="expandable_header expandable_target" title="Expand content">
            <span class="expandable_header-left expandable_label">
                Expandable Header 2
            </span>
            <span class="expandable_header-right expandable_link">
                <span class="expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="expandable_content">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing
                elit. Neque ipsa voluptatibus soluta nobis unde quisquam
                temporibus magnam debitis quidem. Ducimus ratione
                corporis nesciunt earum vel est quaerat blanditiis
                dolore ipsa?
            </p>
        </div>
    </div>
    <div class="expandable expandable__padded">
        <button class="expandable_header expandable_target" title="Expand content">
            <span class="expandable_header-left expandable_label">
                Expandable Header 3
            </span>
            <span class="expandable_header-right expandable_link">
                <span class="expandable_cue-open">
                    Show
                    <span class="cf-icon cf-icon-plus-round"></span>
                </span>
                <span class="expandable_cue-close">
                    Hide
                    <span class="cf-icon cf-icon-minus-round"></span>
                </span>
            </span>
        </button>
        <div class="expandable_content">
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

---
layout: default
title:  "cf-grid"
parent: "Components"
---

## Example grid layouts

### 12 columns w/ 1200px max width

<div class="cols-12">
    <section>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
        <div class="col col-1"><p>one</p></div>
    </section>

    <section>
        <div class="col col-2"><p>two</p></div>
        <div class="col col-2"><p>two</p></div>
        <div class="col col-2"><p>two</p></div>
        <div class="col col-2"><p>two</p></div>
        <div class="col col-2"><p>two</p></div>
        <div class="col col-2"><p>two</p></div>
    </section>

    <section>
        <div class="col col-2"><p>two</p></div>
        <div class="col col-3"><p>three</p></div>
        <div class="col col-2"><p>two</p></div>
        <div class="col col-3"><p>three</p></div>
        <div class="col col-2"><p>two</p></div>
    </section>

    <section>
        <div class="col col-3"><p>three</p></div>
        <div class="col col-3"><p>three</p></div>
        <div class="col col-3"><p>three</p></div>
        <div class="col col-3"><p>three</p></div>
    </section>

    <section>
        <div class="col col-4"><p>four</p></div>
        <div class="col col-4"><p>four</p></div>
        <div class="col col-4"><p>four</p></div>
    </section>

    <section>
        <div class="col col-6"><p>six</p></div>
        <div class="col col-6"><p>six</p></div>
    </section>

    <section>
        <div class="col col-12"><p>twelve</p></div>
    </section>
</div>


### Prefixing/Suffixing

<div class="cols-12">
    <section>
        <div class="col col-1 suffix-11"><p>prefix 0, suffix 11</p></div>
        <div class="col col-1 prefix-1 suffix-10"><p>prefix 1, suffix 10</p></div>
        <div class="col col-1 prefix-2 suffix-9"><p>prefix 2, suffix 9</p></div>
        <div class="col col-1 prefix-3 suffix-8"><p>prefix 3, suffix 8</p></div>
        <div class="col col-1 prefix-4 suffix-7"><p>prefix 4, suffix 7</p></div>
        <div class="col col-1 prefix-5 suffix-6"><p>prefix 5, suffix 6</p></div>
        <div class="col col-1 prefix-6 suffix-5"><p>prefix 6, suffix 5</p></div>
        <div class="col col-1 prefix-7 suffix-4"><p>prefix 7, suffix 4</p></div>
        <div class="col col-1 prefix-8 suffix-3"><p>prefix 8, suffix 3</p></div>
        <div class="col col-1 prefix-9 suffix-2"><p>prefix 9, suffix 2</p></div>
        <div class="col col-1 prefix-10 suffix-1"><p>prefix 10, suffix 1</p></div>
        <div class="col col-1 prefix-11"><p>prefix 11, suffix 0</p></div>
    </section>
</div>


### Nesting

<div class="cols-12">
    <section>
        <div class="col col-6">
            <p>six</p>
            <section>
                <div class="col col-4"><p>four</p></div>
                <div class="col col-4"><p>four</p></div>
                <div class="col col-4"><p>four</p></div>
            </section>
        </div>

        <div class="col col-6">
            <p>six</p>
            <section>
                <div class="col col-4"><p>four</p></div>
                <div class="col col-4"><p>four</p></div>
                <div class="col col-4"><p>four</p></div>
            </section>
        </div>
    </section>

    <section>
        <div class="col col-3">
            <p>three</p>
            <section>
                <div class="col col-6"><p>six</p></div>
                <div class="col col-6"><p>six</p></div>
            </section>
        </div>

        <div class="col col-6">
            <p>six</p>
            <section>
                <div class="col col-4"><p>four</p></div>
                <div class="col col-4"><p>four</p></div>
                <div class="col col-4"><p>four</p></div>
            </section>
        </div>

        <div class="col col-3">
            <p>three</p>
            <section>
                <div class="col col-3"><p>three</p></div>
                <div class="col col-3"><p>three</p></div>
                <div class="col col-3"><p>three</p></div>
                <div class="col col-3"><p>three</p></div>
            </section>
        </div>
    </section>
</div>

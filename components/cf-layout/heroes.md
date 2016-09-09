---
layout: child-component
title:  "Heroes"
parent: "cf-layout"
---

## Standard hero with illustration

<section class="m-hero">
    <div class="m-hero_wrapper wrapper">
        <div class="m-hero_text">
            <h1 class="m-hero_heading">Hero title</h1>
            <p class="m-hero_subhead">
                Hero text goes here. This paragraph has a recommended maximum length of 185 characters.
                This paragraph has a recommended maximum length of 185 characters.
            </p>
            <a class="m-hero_cta" href="#">
                Call to action
            </a>
        </div>
        <div class="m-hero_image-wrapper">
            <div class="m-hero_image" style="background-image: url('http://www.consumerfinance.gov/static/fin-ed-resources/static/img/parents_hero_760x390.png')"></div>
        </div>
    </div>
</section>


## Hero with illustration that bleeds vertically
{: class="u-mt30"}

<section class="m-hero m-hero">
    <div class="m-hero_wrapper wrapper">
        <div class="m-hero_text">
            <h1 class="m-hero_heading">Hero title</h1>
            <p class="m-hero_subhead">
                Hero text goes here. This paragraph has a recommended maximum length of 185 characters.
                This paragraph has a recommended maximum length of 185 characters.
            </p>
            <a class="m-hero_cta btn" href="#">
                Call to action
            </a>
        </div>
        <div class="m-hero_image-wrapper m-hero_image-wrapper__bleed-vertical">
            <img class="m-hero_image" src="{{ site.github.url }}/dist/static/img/bleeding-hero-illustration_mobile.png" alt="">
            <div class="m-hero_image__bleeding" style="background-image: url('{{ site.github.url }}/dist/static/img/bleeding-hero-illustration.png')"></div>
        </div>
    </div>
</section>

### Alternate – doesn't bleed all the way down
{: class="u-mt30"}

<section class="m-hero m-hero">
    <div class="m-hero_wrapper wrapper">
        <div class="m-hero_text">
            <h1 class="m-hero_heading">Hero title</h1>
            <p class="m-hero_subhead">
                Hero text goes here. This paragraph has a recommended maximum length of 185 characters.
                This paragraph has a recommended maximum length of 185 characters.
            </p>
            <a class="m-hero_cta btn" href="#">
                Call to action
            </a>
        </div>
        <div class="m-hero_image-wrapper m-hero_image-wrapper__bleed-vertical">
            <img class="m-hero_image" src="{{ site.github.url }}/dist/static/img/bleeding-hero-illustration_mobile.png" alt="">
            <div class="m-hero_image__bleeding" style="background-image: url('{{ site.github.url }}/dist/static/img/bleeding-hero-illustration_alt.png')"></div>
        </div>
    </div>
</section>


## Hero with photograph
{: class="u-mt30"}

The text overlays the photograph at larger screen sizes.
It's best to avoid a non-button call to action in these,
as it's unlikely that the Pacific Blue will have accessible contrast with a
non-white (or light gray) background.

<section class="m-hero m-hero__overlay"
         style="background-image: url('http://files.consumerfinance.gov/f/images/PC_hero.original.jpg')">
    <div class="m-hero_wrapper wrapper">
        <div class="m-hero_text">
            <h1 class="m-hero_heading">Hero title</h1>
            <p class="m-hero_subhead">
                Hero text goes here. This paragraph has a recommended maximum length of 185 characters.
                This example paragraph is 151 characters long.
            </p>
        </div>
        <div class="m-hero_image-wrapper">
            <div class="m-hero_image" style="background-image: url('http://files.consumerfinance.gov/f/images/pc_mobile_1.original.jpg')"></div>
        </div>
    </div>
</section>

---
layout: default
title:  "cf-pagination"
parent: "Components"
---

## Original Documentation Markup
<div class="u-mb30">
  <nav class="pagination">
      <a class="btn btn__super pagination_prev" href="#pagination_content">
          <span class="btn_icon__left cf-icon cf-icon-left"></span>
          Previous
      </a>
      <a class="btn btn__super pagination_next" href="#pagination_content">
          Next
          <span class="btn_icon__right cf-icon cf-icon-right"></span>
      </a>
      <form class="pagination_form" action="index.html#pagination_content">
          <label class="pagination_label"
                 for="pagination_current-page">
              Page
              <span class="u-visually-hidden">
                  number out of 149 total pages
              </span>
          </label>
          <input
              class="pagination_current-page"
              id="pagination_current-page"
              name="pagination_current-page"
              type="number" min="1" max="149"
              value="149">
          <span class="pagination_label">
              <span aria-hidden="true">
                  of 149
              </span>
          </span>
          <button class="btn btn__link pagination_submit"
                  id="pagination_submit"
                  type="submit">
              Go
          </button>
      </form>
  </nav>
</div>

## Atomic Documentation Markup

<div class="u-mb30">
  <nav class="m-pagination" role="navigation" aria-label="Pagination">
      <a class="a-btn
                a-btn_icon-position-left
                a-btn_icon__left
                m-pagination_btn-prev"
         href="?page=1#o-filterable-list-controls">
          Newer
      </a>
      <a class="a-btn
                a-btn_icon-position-right
                a-btn_icon__right
                m-pagination_btn-next"
         href="?page=3#o-filterable-list-controls">
          Older
      </a>
      <form class="m-pagination_form"
              action="#o-filterable-list-controls">
          <label class="m-pagination_label"
                   for="m-pagination_current-page">
              Page
              <span class="u-visually-hidden">
                  number 2 out
              </span>
              <input class="m-pagination_current-page"
                       id="m-pagination_current-page"
                       name="page"
                       type="number"
                       min="1"
                       max="149"
                       pattern="[0-9]*"
                       inputmode="numeric"
                       value="2">
              of 149
          </label>
          <button class="a-btn
                         a-btn__link
                         m-pagination_btn-submit"
                    id="m-pagination_btn-submit"
                    type="submit">Go</button>
      </form>
  </nav>
</div>

## Live CFGov Markup (<a href="http://www.consumerfinance.gov/about-us/blog/">about-us/blog</a>)

### First Page
<div class="u-mb30">
  <nav class="m-pagination" role="navigation" aria-label="Pagination">
        <a class="btn
                  btn__super
                  btn__disabled
                  m-pagination_btn-prev">

            <span class="btn_icon__left cf-icon cf-icon-left"></span>
            Newer
        </a>
        <a class="btn
                  btn__super
                  m-pagination_btn-next" href="?page=2#o-filterable-list-controls">Older
            <span class="btn_icon__right cf-icon cf-icon-right"></span>
        </a>
        <form action="#o-filterable-list-controls">
            <label for="m-pagination_current-page">
                Page
                <span class="u-visually-hidden">
                    number out of 73 total pages
                </span>
            </label>
                <input type="hidden" name="page" value="1">
            <input id="m-pagination_current-page" name="page" type="number" min="1" max="73" pattern="[0-9]*" inputmode="numeric" value="1">
            <span class="m-pagination_label">
                of 73
            </span>
            <button class="btn btn__link" id="m-pagination_submit-btn" type="submit">
                Go
            </button>
        </form>
    </nav>
</div>

### Mid-page

<div class="u-mb30">
  <nav class="m-pagination" role="navigation" aria-label="Pagination">
        <a class="btn
                  btn__super
                  m-pagination_btn-prev" href="?page=1#o-filterable-list-controls">
            <span class="btn_icon__left cf-icon cf-icon-left"></span>
            Newer
        </a>
        <a class="btn
                  btn__super
                  m-pagination_btn-next" href="?page=3#o-filterable-list-controls">Older
            <span class="btn_icon__right cf-icon cf-icon-right"></span>
        </a>
        <form action="#o-filterable-list-controls">
            <label for="m-pagination_current-page">
                Page
                <span class="u-visually-hidden">
                    number out of 73 total pages
                </span>
            </label>
              <input type="hidden" name="page" value="2">
            <input id="m-pagination_current-page" name="page" type="number" min="1" max="73" pattern="[0-9]*" inputmode="numeric" value="2">
            <span class="m-pagination_label">
                of 73
            </span>
            <button class="btn btn__link" id="m-pagination_submit-btn" type="submit">
                Go
            </button>
        </form>
    </nav>
</div>

### Last Page

<div class="u-mb30">
  <nav class="m-pagination" role="navigation" aria-label="Pagination">
        <a class="btn
                  btn__super
                  m-pagination_btn-prev" href="?page=72#o-filterable-list-controls">
            <span class="btn_icon__left cf-icon cf-icon-left"></span>
            Newer
        </a>
        <a class="btn
                  btn__super
                  btn__disabled m-pagination_btn-next">
        Older
            <span class="btn_icon__right cf-icon cf-icon-right"></span>
        </a>
        <form action="#o-filterable-list-controls">
            <label for="m-pagination_current-page">
                Page
                <span class="u-visually-hidden">
                    number out of 73 total pages
                </span>
            </label>
                <input type="hidden" name="page" value="73">
            <input id="m-pagination_current-page" name="page" type="number" min="1" max="73" pattern="[0-9]*" inputmode="numeric" value="73">
            <span class="m-pagination_label">
                of 73
            </span>
            <button class="btn btn__link" id="m-pagination_submit-btn" type="submit">
                Go
            </button>
        </form>
    </nav>
</div>

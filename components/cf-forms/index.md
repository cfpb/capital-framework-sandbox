---
layout: default
title:  "cf-forms"
parent: "Components"
---

# Forms

## Form labels

### Default label

<label class="a-label">Form label</label>

### Label heading

<label class="a-label__heading">
    Form label heading
</label>

## Form fields

### Text fields

<div class="m-form-field">
    <label class="a-label" for="test_text-input">Label</label>
    <input class="a-text-input" type="text" placeholder="ABCD" id="test_text-input">
</div>

<div class="m-form-field">
    <label class="a-label" for="test_text-input2">Label</label>
    <textarea class="a-text-input" type="text" placeholder="ABCD" id="test_text-input2"></textarea>
</div>

### Checkboxes

<div class="m-form-field m-form-field__checkbox">
    <input class="a-checkbox" type="checkbox" id="test_checkbox">
    <label class="a-label" for="test_checkbox">Label</label>
</div>

### Large target checkboxes

#### Active

<fieldset class="o-form_fieldset">
    <legend class="a-label a-label__heading">
        Favorite Pet
    </legend>
    <ul class="m-list m-list__unstyled">
        <li>
            <div class="m-form-field
                        m-form-field__checkbox
                        m-form-field__lg-target">
                <input class="a-checkbox"
                       type="checkbox"
                       name="form_pets"
                       id="input_pets-1">
                <label class="a-label"
                       for="input_pets-1">
                    Dog
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__checkbox
                        m-form-field__lg-target">
                <input class="a-checkbox"
                       type="checkbox"
                       name="form_pets"
                       id="input_pets-2">
                <label class="a-label"
                       for="input_pets-2">
                    Cat
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__checkbox
                        m-form-field__lg-target">
                <input class="a-checkbox"
                       type="checkbox"
                       name="form_pets"
                       id="input_pets-3">
                <label class="a-label"
                      for="input_pets-3">
                    Mouse
                </label>
            </div>
        </li>
    </ul>
</fieldset>

#### Disabled

<fieldset class="o-form_fieldset">
    <legend class="a-label a-label__heading">
        Favorite Pet
    </legend>
    <ul class="m-list m-list__unstyled">
        <li>
            <div class="m-form-field
                        m-form-field__checkbox
                        m-form-field__lg-target">
                <input class="a-checkbox"
                       type="checkbox"
                       name="form_pets"
                       id="input_pets-1__disabled"
                       disabled>
                <label class="a-label"
                       for="input_pets-1__disabled">
                    Dog
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__checkbox
                        m-form-field__lg-target">
                <input class="a-checkbox"
                       type="checkbox"
                       name="form_pets"
                       id="input_pets-2__disabled"
                       disabled>
                <label class="a-label"
                       for="input_pets-2__disabled">
                    Cat
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__checkbox
                        m-form-field__lg-target">
                <input class="a-checkbox"
                       type="checkbox"
                       name="form_pets"
                       id="input_pets-3__disabled"
                       disabled>
                <label class="a-label"
                       for="input_pets-3__disabled">
                    Mouse
                </label>
            </div>
        </li>
    </ul>
</fieldset>

### Radio buttons

<div class="m-form-field m-form-field__radio">
    <input class="a-radio" type="radio" id="test_radio">
    <label class="a-label" for="test_radio">Label</label>
</div>

### Large target radio buttons

#### Active

<fieldset class="o-form_fieldset">
    <legend class="a-label a-label__heading">
        T-Shirt Size
    </legend>
    <ul class="m-list m-list__unstyled">
        <li>
            <div class="m-form-field
                        m-form-field__radio
                        m-form-field__lg-target">
                <input class="a-radio"
                       type="radio"
                       name="form_shirt"
                       id="input_shirt-1">
                <label class="a-label"
                       for="input_shirt-1">
                    Dog
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__radio
                        m-form-field__lg-target">
                <input class="a-radio"
                       type="radio"
                       name="form_shirt"
                       id="input_shirt-2">
                <label class="a-label"
                       for="input_shirt-2">
                    Cat
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__radio
                        m-form-field__lg-target">
                <input class="a-radio"
                       type="radio"
                       name="form_shirt"
                       id="input_shirt-3">
                <label class="a-label"
                       for="input_shirt-3">
                    Mouse
                </label>
            </div>
        </li>
    </ul>
</fieldset>

#### Disabled

<fieldset class="o-form_fieldset">
    <legend class="a-label a-label__heading">
        T-Shirt Size
    </legend>
    <ul class="m-list m-list__unstyled">
        <li>
            <div class="m-form-field
                        m-form-field__radio
                        m-form-field__lg-target">
                <input class="a-radio"
                       type="radio"
                       name="form_shirt"
                       id="input_shirt-1__disabled"
                       disabled>
                <label class="a-label"
                       for="input_shirt-1__disabled">
                    Dog
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__radio
                        m-form-field__lg-target">
                <input class="a-radio"
                       type="radio"
                       name="form_shirt"
                       id="input_shirt-2__disabled"
                       disabled>
                <label class="a-label"
                       for="input_shirt-2__disabled">
                    Cat
                </label>
            </div>
        </li>
        <li>
            <div class="m-form-field
                        m-form-field__radio
                        m-form-field__lg-target">
                <input class="a-radio"
                       type="radio"
                       name="form_shirt"
                       id="input_shirt-3__disabled"
                       disabled>
                <label class="a-label"
                       for="input_shirt-3__disabled">
                    Mouse
                </label>
            </div>
        </li>
    </ul>
</fieldset>

### Select box

#### Default State

<div class="m-form-field m-form-field__select">
    <label class="a-label" for="test_select">Label</label>
    <div class="a-select">
        <select id="test_select">
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>

#### Disabled State

<div class="m-form-field m-form-field__select">
    <label class="a-label" for="test_select">Label</label>
    <div class="a-select">
        <select id="test_select__disabled" disabled>
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>

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

## Form validation

### Form input error icon
<div class="m-form-field
            m-form-field__error">
    <label class="a-label__heading" for="form-input-error">Label</label>
    <input class="a-text-input a-text-input__error"
           type="text"
           value="Invalid input"
           id="form-input-error"
           aria-describedby="form-input-error_message">
    <div class="a-error-message" id="form-input-error_message" role="alert">
        <span class="cf-icon cf-icon-delete-round" aria-hidden="true"></span>
        This is a required question, please answer.
    </div>
</div>

## Form group

### Form group block
<!--
<div class="block">
    <div class="form-group">
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
    </div>
    <div class="form-group">
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
    </div>
    <div class="form-group">
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" title="Test input">
        </div>
    </div>
</div>

### Real world example
<div class="block">
    <div class="form-group">
        <label class="form-label-header">Form group</label>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
    </div>
    <div class="form-group">
        <label class="form-label-header">Form group</label>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
        <div class="form-group_item">
            <input type="text" value="Form group item" title="Test input">
        </div>
    </div>
</div>
-->

## Input with button

### Default input and button

<form class="o-form__input-w-btn">
    <div class="o-form__input-w-btn_input-container">
        <input class="a-text-input" type="text" title="Test input">
    </div>
    <div class="o-form__input-w-btn_btn-container">
        <button class="a-btn" type="submit">Search</button>
    </div>
</form>

## Button inside input

### Default button inside of an default input

<div class="m-btn-inside-input">
    <input class="a-text-input"
           type="text"
           value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable." title="Test input">
    <button class="a-btn a-btn__link">
        Clear
        <span class="cf-icon cf-icon-delete"></span>
    </button>
</div>


## Filter Form Examples

### Atomic Filter Form

<form class="o-form">

    <div class="o-form_group">
        <div class="content-l">

            <div class="content-l_col content-l_col-1">
                <div class="m-form-field">
                    <label class="a-label a-label__heading"
                           for="filter1_title">Item name</label>
                    <input class="a-text-input"
                           id="filter1_title"
                           maxlength="250"
                           name="filter1_title"
                           placeholder="Search for a specific word in item title"
                           type="text">
                </div>
            </div>

        </div>
    </div>

    <div class="content-l">

        <div class="content-l_col content-l_col-1-3">
            <div class="o-form_group">
                <fieldset class="o-form_fieldset">
                    <legend class="a-label a-label__heading"
                           for="categories">Category</legend>
                    <ul class="m-list m-list__unstyled">
                        <li class="m-form-field m-form-field__checkbox">
                            <input class="a-checkbox"
                                   type="checkbox"
                                   value="at-the-cfpb"
                                   id="filter1_categories_at-the-cfpb"
                                   name="filter1_categories">
                            <label class="a-label" for="filter1_categories_at-the-cfpb">At the CFPB</label>
                        </li>

                        <li class="m-form-field m-form-field__checkbox">
                            <input class="a-checkbox"
                                   type="checkbox"
                                   value="policy_compliance"
                                   id="filter1_categories_policy_compliance"
                                   name="filter1_categories" disabled>
                            <label class="a-label" for="filter1_categories_policy_compliance">Policy &amp; Compliance</label>
                        </li>

                        <li class="m-form-field m-form-field__radio">
                            <input class="a-radio"
                                   type="radio"
                                   value="data-research-reports"
                                   id="filter1_categories_data-research-reports"
                                   name="filter1_categories">
                            <label class="a-label" for="filter1_categories_data-research-reports">Data, research &amp; reports</label>
                        </li>

                        <li class="m-form-field m-form-field__radio">
                            <input class="a-radio"
                                   type="radio"
                                   value="info-for-consumers"
                                   id="filter1_categories_info-for-consumers"
                                   name="filter1_categories" disabled>
                            <label class="a-label" for="filter1_categories_info-for-consumers">Info for consumers</label>
                        </li>
                    </ul>
                </fieldset>
            </div>
        </div>

        <div class="content-l_col content-l_col-2-3">

            <div class="o-form_group">
                <div class="content-l">

                    <div class="content-l_col content-l_col-1-2">
                        <div class="m-form-field">
                            <label class="a-label a-label__heading"
                                   for="filter1_topics">Topic</label>
                            <div class="m-typeahead"
                                 data-js-hook="state_atomic_init">
                                <header class="m-typeahead_header">
                                    <input class="a-text-input"
                                           type="text"
                                           placeholder="Choose up to five"
                                           id="filter1_topics">
                                </header>
                            </div>
                        </div>
                    </div>

                    <div class="content-l_col content-l_col-1-2">
                        <div class="m-form-field">
                            <label class="a-label a-label__heading"
                                   for="filter1_authors">Author</label>
                            <div class="m-typeahead"
                                 data-js-hook="state_atomic_init">
                                <header class="m-typeahead_header">
                                    <input class="a-text-input"
                                           type="text"
                                           placeholder="Choose up to five"
                                           id="filter1_authors">
                                </header>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <div class="o-form_group">
                <div class="content-l">

                    <div class="content-l_col content-l_col-1">
                        <label class="a-label a-label__heading">Date Range</label>

                        <div class="content-l">

                            <div class="content-l_col content-l_col-1-2">
                                <div class="m-form-field">
                                    <label class="a-label a-label__heading"
                                           for="filter1_from_date">From:</label>
                                    <input class="a-text-input
                                                  js-filter_range-date
                                                  js-filter_range-date__gte"
                                           data-type="date"
                                           id="filter1_from_date"
                                           name="filter1_from_date"
                                           placeholder="mm/dd/yyyy"
                                           type="date">
                                </div>
                            </div>

                            <div class="content-l_col content-l_col-1-2">
                                <div class="m-form-field">
                                    <label class="a-label a-label__heading"
                                           for="filter1_to_date">To:</label>
                                    <input class="a-text-input
                                                  js-filter_range-date
                                                  js-filter_range-date__gte"
                                           data-type="date"
                                           id="filter1_to_date"
                                           name="filter1_to_date"
                                           placeholder="mm/dd/yyyy"
                                           type="date">
                                </div>
                            </div>

                        </div>

                    </div>
                </div>
            </div>

        </div>

    </div>

    <div class="content-l">
        <div class="content-l_col
                    content-l_col-1">

            <div class="o-form_group">
                <input class="a-btn" type="submit" value="Apply Filters">
                <a class="a-btn
                          a-btn__link
                          a-btn__warning"
                   href="/about-us/blog/">Clear filters</a>
            </div>

        </div>
    </div>

</form>

### Current CF-Gov Filter Form

<form>
    <div class="form-l">

        <div class="form-l_col
                    form-l_col-1">
            <div class="form-group">
                <label class="form-label-header" for="filter1_title">
                    Item name
                </label>
                <input id="filter1_title" maxlength="250" name="filter1_title" placeholder="Search for a specific word in item title" type="text">
            </div>
        </div>


        <div class="form-l_col
                    form-l_col-1-3">
            <div class="form-group">
                <label class="form-label-header" for="categories">
                Category
                </label>

                <input class="cf-input" type="checkbox" value="at-the-cfpb" id="filter1_categories_at-the-cfpb" name="filter1_categories">
                <label for="filter1_categories_at-the-cfpb">
                At the CFPB
                </label>

                <input class="cf-input" type="checkbox" value="policy_compliance" id="filter1_categories_policy_compliance" name="filter1_categories">
                <label for="filter1_categories_policy_compliance">
                Policy &amp; Compliance
                </label>

                <input class="cf-input" type="checkbox" value="data-research-reports" id="filter1_categories_data-research-reports" name="filter1_categories">
                <label for="filter1_categories_data-research-reports">
                Data, research &amp; reports
                </label>

                <input class="cf-input" type="checkbox" value="info-for-consumers" id="filter1_categories_info-for-consumers" name="filter1_categories">
                <label for="filter1_categories_info-for-consumers">
                Info for consumers
                </label>

            </div>
        </div>


        <div class="form-l_col
                    form-l_col__flush-bottom
                    form-l_col-2-3">
            <div class="form-l">


                <div class="form-l_col
                            form-l_col-1-2">
                    <div class="form-group">
                        <label class="form-label-header" for="filter1_topics">
                            Topic
                        </label>
                        <div class="cf-multi-select" data-js-hook="state_atomic_init">
                            <ul class="list__unstyled cf-multi-select_choices"></ul>
                            <header class="cf-multi-select_header"><input class="cf-multi-select_search" type="text" placeholder="Choose up to five" id="filter1_topics"></header>
                        </div>
                    </div>
                </div>

                <div class="form-l_col
                            form-l_col-1-2">
                    <div class="form-group">
                        <label class="form-label-header" for="filter1_authors">
                            Author
                        </label>
                        <div class="cf-multi-select" data-js-hook="state_atomic_init">
                            <ul class="list__unstyled cf-multi-select_choices"></ul>
                            <header class="cf-multi-select_header"><input class="cf-multi-select_search" type="text" placeholder="Choose up to five" id="filter1_authors"></header>
                        </div>
                    </div>
                </div>


                <div class="form-l_col
                            form-l_col__flush-bottom
                            form-l_col-1">
                    <div class="form-group">
                        <label class="form-label-header">
                            Date Range
                        </label>
                        <div class="form-l">
                            <div class="form-l_col
                                        form-l_col-1-2">
                                <div class="form-group">
                                    <label class="form-label-header" for="filter1_from_date">
                                        From:
                                    </label>
                                    <input class="js-filter_range-date js-filter_range-date__gte" data-type="date" id="filter1_from_date" name="filter1_from_date" placeholder="mm/dd/yyyy" type="text">
                                </div>
                            </div>
                            <div class="form-l_col
                                        form-l_col-1-2">
                                <div class="form-group">
                                    <label class="form-label-header" for="filter1_to_date">
                                        To:
                                    </label>
                                    <input class="js-filter_range-date js-filter_range-date__lte" data-type="date" id="filter1_to_date" name="filter1_to_date" placeholder="mm/dd/yyyy" type="text">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>

        <div class="form-l_col
                    form-l_col__flush-bottom
                    form-l_col-1">
            <input class="btn form-actions_item" type="submit" value="Apply Filters">
            <a class="btn btn__warning btn__link" href="/about-us/blog/">
                Clear filters
            </a>
        </div>

    </div>
</form>

## Form layout examples

### Large target inputs

<form class="o-form">

    <fieldset class="o-form_fieldset">
        <legend class="a-label a-label__heading">
            Coffee or Tea?
        </legend>
        <ul class="m-list m-list__unstyled content-l">
            <li class="content-l_col content-l_col-1-2">
                <div class="m-form-field m-form-field__checkbox m-form-field__lg-target">
                    <input class="a-checkbox"
                           type="checkbox"
                           name="form_drink"
                           id="input_drink-1">
                    <label class="a-label"
                           for="input_drink-1">
                        Coffee
                    </label>
                </div>
            </li>
            <li class="content-l_col content-l_col-1-2">
                <div class="m-form-field m-form-field__checkbox m-form-field__lg-target">
                    <input class="a-checkbox"
                           type="checkbox"
                           name="form_drink"
                           id="input_drink-2">
                    <label class="a-label"
                           for="input_drink-2">
                        Tea
                    </label>
                </div>
            </li>
        </ul>
    </fieldset>

    <fieldset class="o-form_fieldset">
        <legend class="a-label a-label__heading">
            Cereal or Yogurt?
        </legend>
        <ul class="m-list m-list__unstyled content-l">
            <li class="content-l_col content-l_col-1-2">
                <div class="m-form-field m-form-field__radio m-form-field__lg-target">
                    <input class="a-radio"
                           type="radio"
                           name="form_breakfast"
                           id="input_breakfast-1">
                    <label class="a-label"
                           for="input_breakfast-1">
                        Cereal
                    </label>
                </div>
            </li>
            <li class="content-l_col content-l_col-1-2">
                <div class="m-form-field m-form-field__radio m-form-field__lg-target">
                    <input class="a-radio"
                           type="radio"
                           name="form_breakfast"
                           id="input_breakfast-2">
                    <label class="a-label"
                           for="input_breakfast-2">
                        Yogurt
                    </label>
                </div>
            </li>
        </ul>
    </fieldset>

</form>

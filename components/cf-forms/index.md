---
layout: default
title:  "cf-forms"
parent: "Components"
---

## Form labels

### Label header

<label class="form-label-header">
    Form label header
</label>


## Form fields

### Text fields

<div class="m-form-field">
    <label class="a-label" for="test_text-input">Label</label>
    <input class="a-text-input" type="text" placeholder="ABCD" id="test_text-input">
</div>

<div class="m-form-field">
    <label class="a-label__heading" for="test_text-input2">Label</label>
    <input class="a-text-input" type="text" placeholder="ABCD" id="test_text-input2">
</div>

### Checkboxes

<div class="m-form-field__checkbox">
    <input class="a-checkbox" type="checkbox" id="test_checkbox">
    <label class="a-label" for="test_checkbox">Label</label>
</div>

### Radio buttons

<div class="m-form-field__radio">
    <input class="a-radio" type="radio" id="test_radio">
    <label class="a-label" for="test_radio">Label</label>
</div>

### Select box

<div class="m-form-field__select">
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

## Form validation

### Form input error icon
<div class="m-field m-field__error">
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

## Atomic form group with big checkboxes

### One-Column

#### Active

<fieldset class="o-form-input-group">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            Favorite Pet
        </legend>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_pets"
                   id="input_pets-1">
            <label class="a-input_label"
                   for="input_pets-1">
                Dog
            </label>
        </div>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_pets"
                   id="input_pets-2">
            <label class="a-input_label"
                   for="input_pets-2">
                Cat
            </label>
        </div>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_pets"
                   id="input_pets-3">
            <label class="a-input_label"
                   for="input_pets-3">
                Mouse
            </label>
        </div>
    </div>
</fieldset>

#### Disabled

<fieldset class="o-form-input-group">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            Favorite Pet
        </legend>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_pets__disabled"
                   id="input_pets-1__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_pets-1__disabled">
                Dog
            </label>
        </div>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_pets__disabled"
                   id="input_pets-2__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_pets-2__disabled">
                Cat
            </label>
        </div>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_pets__disabled"
                   id="input_pets-3__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_pets-3__disabled">
                Mouse
            </label>
        </div>
    </div>
</fieldset>

### Two-Column

#### Active

<fieldset class="o-form-input-group o-form-input-group__two-column">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            Coffee or Tea?
        </legend>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_coffee-tea"
                   id="input_coffee-tea-1">
            <label class="a-input_label"
                   for="input_coffee-tea-1">
                Coffee
            </label>
        </div>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_coffee-tea"
                   id="input_coffee-tea-2">
            <label class="a-input_label"
                   for="input_coffee-tea-2">
                Tea
            </label>
        </div>
    </div>
</fieldset>

#### Disabled

<fieldset class="o-form-input-group o-form-input-group__two-column">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            Coffee or Tea?
        </legend>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_coffee-tea__disabled"
                   id="input_coffee-tea-1__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_coffee-tea-1__disabled">
                Coffee
            </label>
        </div>
    </div>
    <div class="m-big-checkbox">
        <div class="m-big-checkbox_container">
            <input class="a-input"
                   type="checkbox"
                   name="form_coffee-tea__disabled"
                   id="input_coffee-tea-2__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_coffee-tea-2__disabled">
                Tea
            </label>
        </div>
    </div>
</fieldset>


## Atomic form group with big radio buttons

### One-Column

#### Active

<fieldset class="o-form-input-group">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            T-shirt size
        </legend>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_shirt"
                   id="input_shirt-1">
            <label class="a-input_label"
                   for="input_shirt-1">
                Small
            </label>
        </div>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_shirt"
                   id="input_shirt-2">
            <label class="a-input_label"
                   for="input_shirt-2">
                Medium
            </label>
        </div>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_shirt"
                   id="input_shirt-3">
            <label class="a-input_label"
                   for="input_shirt-3">
                Large
            </label>
        </div>
    </div>
</fieldset>

#### Disabled

<fieldset class="o-form-input-group">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            T-shirt size
        </legend>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_shirt__disabled"
                   id="input_shirt-1__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_shirt-1__disabled">
                Small
            </label>
        </div>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_shirt__disabled"
                   id="input_shirt-2__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_shirt-2__disabled">
                Medium
            </label>
        </div>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_shirt__disabled"
                   id="input_shirt-3__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_shirt-3__disabled">
                Large
            </label>
        </div>
    </div>
</fieldset>

### Two-Column

#### Active

<fieldset class="o-form-input-group o-form-input-group__two-column">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            Cereal or Yogurt?
        </legend>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_breakfast"
                   id="input_breakfast-1">
            <label class="a-input_label"
                   for="input_breakfast-1">
                Cereal
            </label>
        </div>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_breakfast"
                   id="input_breakfast-2">
            <label class="a-input_label"
                   for="input_breakfast-2">
                Yogurt
            </label>
        </div>
    </div>
</fieldset>

#### Disabled

<fieldset class="o-form-input-group o-form-input-group__two-column">
    <div class="form-l_col
                form-l_col-1
                u-mb0">
        <legend class="form-label-header">
            Cereal or Yogurt?
        </legend>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_breakfast__disabled"
                   id="input_breakfast-1__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_breakfast-1__disabled">
                Cereal
            </label>
        </div>
    </div>
    <div class="m-big-radio-button">
        <div class="m-big-radio-button_container">
            <input class="a-input"
                   type="radio"
                   name="form_breakfast__disabled"
                   id="input_breakfast-2__disabled"
                   disabled>
            <label class="a-input_label"
                   for="input_breakfast-2__disabled">
                Yogurt
            </label>
        </div>
    </div>
</fieldset>

## Form group

### Form group block

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

## Input with button

### Default input and button

<div class="input-with-btn">
    <div class="input-with-btn_input">
        <input type="text" title="Test input">
    </div>
    <div class="input-with-btn_btn">
        <button class="a-btn">Search</button>
    </div>
</div>

### Super input and button

<div class="input-with-btn">
    <div class="input-with-btn_input">
        <input class="input__super" type="text" title="Test input">
    </div>
    <div class="input-with-btn_btn">
        <button class="a-btn a-btn__super">Search</button>
    </div>
</div>

## Button inside input

### Default button inside of an default input

<div class="block">
    <div class="btn-inside-input">
        <input type="text"
               value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable." title="Test input">
        <button class="a-btn a-btn__link">
            Clear
            <span class="cf-icon cf-icon-delete"></span>
        </button>
    </div>
</div>

### Super button inside of a super input

<div class="block">
    <div class="btn-inside-input">
        <input class="input__super"
               type="text"
               value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable." title="Test input">
        <button class="a-btn a-btn__super a-btn__link a-btn__secondary">
            Clear
            <span class="cf-icon cf-icon-delete"></span>
        </button>
    </div>
</div>

## Select dropdown

### Optional select

<div class="form-l_col form-l_col-1">
    <label class="form-label-header"
           for="select_example">
            Optional select example
            <span class="micro-copy">&nbsp;(Optional)</span>
    </label>
    <div class="m-select"><!-- molecule -->
        <select id="select_example"> <!-- atom -->
            <option value="" disabled selected>Please select</option> <!-- atom -->
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>

### Disabled select

<div class="form-l_col form-l_col-1">
    <label class="form-label-header"
           for="select_example">
            Disabled select example
    </label>
    <div class="m-select">
        <select id="select_example" disabled>
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>

### Required select

<div class="form-l_col form-l_col-1">
    <label class="form-label-header"
           for="select_example">
            Required select example
    </label>
    <div class="m-select">
        <select id="select_example" required>
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>

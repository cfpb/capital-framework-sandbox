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


## Super input

## Example

<input class="input__super" type="text" value="Super input" title="Test input">
<button class="a-btn a-btn__super">Super</button>


## Input states

### Error state

<input class="error" type="text" value="Invalid input" title="Test input">

### Warning state

<input class="warning" type="text" value="Invalid input" title="Test input">

### Success state

<input class="success" type="text" value="Validated input" title="Test input">

### Disabled state

<input class="disabled" disabled="true" autocomplete="off" type="text" value="Validated input" title="Test input">

## Form icons

### Form input icons

<input type="text" value="" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-email"></span>

### Form input error icon

<input class="error" type="text" value="Invalid input" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-delete-round" role="alert"></span>

### Form input warning icon

<input class="warning" type="text" value="Invalid input" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-error-round" role="alert"></span>

### Form input success icon

<input class="success" type="text" value="Validated input" title="Test input">
<span class="cf-form_input-icon cf-icon cf-icon-approved-round"></span>

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


<div class="m-btn-inside-input">
    <input type="text"
        value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable."
        title="Test input"
        class="a-text-input">
    <div class="m-btn-inside-input_btn-container">
      <button class="a-btn a-btn__link">
          Clear
          <span class="cf-icon cf-icon-delete"></span>
      </button>
    </div>
</div>

&nbsp;

#### Disabled button

<div class="m-btn-inside-input">
    <input type="text"
        value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable."
        title="Test input"
        class="a-text-input a-text-input__disabled">
    <div class="m-btn-inside-input_btn-container">
      <button class="a-btn a-btn__link">
          Clear
          <span class="cf-icon cf-icon-delete"></span>
      </button>
    </div>
</div>

&nbsp;

#### Error state

<div class="m-btn-inside-input">
    <input type="text"
        value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable."
        title="Test input"
        class="a-text-input a-text-input__error">
    <div class="m-btn-inside-input_btn-container">
      <button class="a-btn a-btn__link">
          Clear
          <span class="cf-icon cf-icon-delete"></span>
      </button>
    </div>
</div>

&nbsp;

#### Warning state

<div class="m-btn-inside-input">
    <input type="text"
        value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable."
        title="Test input"
        class="a-text-input a-text-input__warning">
    <div class="m-btn-inside-input_btn-container">
      <button class="a-btn a-btn__link">
          Clear
          <span class="cf-icon cf-icon-delete"></span>
      </button>
    </div>
</div>

&nbsp;

#### Success state

<div class="m-btn-inside-input">
    <input type="text"
        value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable."
        title="Test input"
        class="a-text-input a-text-input__success">
    <div class="m-btn-inside-input_btn-container">
      <button class="a-btn a-btn__link">
          Clear
          <span class="cf-icon cf-icon-delete"></span>
      </button>
    </div>
</div>

&nbsp;

### Default button inside of a default input with button

<div class="o-form__input-w-btn">
    <div class="o-form__input-w-btn_input-container">
      <div class="m-btn-inside-input">
          <input type="text"
              value="This is some really long text to make sure that the button doesn't overlap the content in such a way that this input becomes unusable."
              title="Test input"
              class="a-text-input">
          <div class="m-btn-inside-input_btn-container">
            <button class="a-btn a-btn__link">
                Clear
                <span class="cf-icon cf-icon-delete"></span>
            </button>
          </div>
      </div>
    </div>
    <div class="o-form__input-w-btn_btn-container">
        <button class="a-btn">Search</button>
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
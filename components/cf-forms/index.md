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


# Dropdowns/Select element


## Atomic
<!--
   label:         Name of the field.

   placeholder:   Text for the placeholder.

   fields:        An array of all the fields to select.

   size:          The size of the field. Defaults to 1 (full-width).
                  Possible options: 1, 1-2, 1-3

   required:      Whether the field is required. Defaults to false.

   disabled:      Whether the field is disabled. Defaults to false.

   ========================================================================== 
   -->

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


## cfgov-refresh PRs

<div class="form-l_col form-l_col-1">
    <label class="form-label-header"
           for="select_example">
            Optional select example
            <span class="micro-copy">&nbsp;(Optional)</span>
    </label>
    <div class="cf-select"><!-- molecule -->
        <select id="select_example"> <!-- atom -->
            <option value="" disabled selected>Please select</option> <!-- atom -->
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>

<div class="form-l_col form-l_col-1">
    <label class="form-label-header"
           for="select_example">
            Disabled select example
    </label>
    <div class="cf-select">
        <select id="select_example" disabled>
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>

<div class="form-l_col form-l_col-1">
    <label class="form-label-header"
           for="select_example">
            Required select example
    </label>
    <div class="cf-select">
        <select id="select_example" required>
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
            <option value="option4">Option 4</option>
        </select>
    </div>
</div>


## Design Manual 

<div class="custom-select is-enabled">
    <select class="custom-select_select" data-placeholder="Please select">
        <option value="">Please select</option>
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
        <option value="option3">Option 3</option>
        <option value="option4">Option 4</option>
    </select>
    <span class="custom-select_icon cf-icon cf-icon-down"></span>
    <span class="custom-select_text custom-select_placeholder">Please select</span>
</div>


## Live site


<div class="cf-select">
  <select id="retirement-age-selector"><option value="">Choose age</option><option value="62">62</option><option value="63">63</option><option value="64">64</option><option value="65">65</option><option value="66">66</option><option value="67">67</option><option value="68">68</option><option value="69">69</option><option value="70">70</option></select>
</div>
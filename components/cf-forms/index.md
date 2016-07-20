---
layout: default
title:  "cf-forms"
parent: "Components"
---

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
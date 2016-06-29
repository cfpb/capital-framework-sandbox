---
layout: default
title:  "cf-tables"
parent: "Components"
---

## Responsive table styles for Small Screens

### Table base style, with small screen base style "stacked"

Shrink to mobile size to test.

<table class="table__stack-on-small">
  <thead>
    <tr>
      <th>Column 1</th>
      <th>Column 2</th>
      <th>Column 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Column 1">Row A</td>
      <td data-label="Column 2">Cell A2</td>
      <td data-label="Column 3">Cell A3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row B</td>
      <td data-label="Column 2">Cell B2</td>
      <td data-label="Column 3">Cell B3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row C</td>
      <td data-label="Column 2">Cell C2</td>
      <td data-label="Column 3">Cell C3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row D</td>
      <td data-label="Column 2">Cell D2</td>
      <td data-label="Column 3">Cell D3</td>
    </tr>
  </tbody>
</table>

### Table with small screen variation - "stacked with entry header"

Shrink to mobile size to test.

<table class="table__stack-on-small table__entry-header-on-small">
  <thead>
    <tr>
      <th>Column 1</th>
      <th>Column 2</th>
      <th>Column 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Column 1">Row A</td>
      <td data-label="Column 2">Cell A2</td>
      <td data-label="Column 3">Cell A3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row B</td>
      <td data-label="Column 2">Cell B2</td>
      <td data-label="Column 3">Cell B3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row C</td>
      <td data-label="Column 2">Cell C2</td>
      <td data-label="Column 3">Cell C3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row D</td>
      <td data-label="Column 2">Cell D2</td>
      <td data-label="Column 3">Cell D3</td>
    </tr>
  </tbody>
</table>

### Table with small screen variation - "Comparative with horizontal scroll"

Shrink to mobile size to test.

<div class="table-wrapper__scrolling">
  <table>
    <thead>
      <tr>
        <th>Column 1</th>
        <th>Column 2</th>
        <th>Column 3</th>
        <th>Column 4</th>
        <th>Column 5</th>
        <th>Column 6</th>
        <th>Column 7</th>
        <th>Column 8</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td data-label="Column 1">Row A</td>
        <td data-label="Column 2">Cell A2</td>
        <td data-label="Column 3">Cell A3</td>
        <td data-label="Column 4">Cell A4</td>
        <td data-label="Column 5">Cell A5</td>
        <td data-label="Column 6">Cell A6</td>
        <td data-label="Column 7">Cell A7</td>
        <td data-label="Column 8">Cell A8</td>
      </tr>
      <tr>
        <td data-label="Column 1">Row B</td>
        <td data-label="Column 2">Cell B2</td>
        <td data-label="Column 3">Cell B3</td>
        <td data-label="Column 4">Cell B4</td>
        <td data-label="Column 5">Cell B5</td>
        <td data-label="Column 6">Cell B6</td>
        <td data-label="Column 7">Cell B7</td>
        <td data-label="Column 8">Cell B8</td>
      </tr>
      <tr>
        <td data-label="Column 1">Row C</td>
        <td data-label="Column 2">Cell C2</td>
        <td data-label="Column 3">Cell C3</td>
        <td data-label="Column 4">Cell C4</td>
        <td data-label="Column 5">Cell C5</td>
        <td data-label="Column 6">Cell C6</td>
        <td data-label="Column 7">Cell C7</td>
        <td data-label="Column 8">Cell C8</td>
      </tr>
      <tr>
        <td data-label="Column 1">Row D</td>
        <td data-label="Column 2">Cell D2</td>
        <td data-label="Column 3">Cell D3</td>
        <td data-label="Column 4">Cell D4</td>
        <td data-label="Column 5">Cell D5</td>
        <td data-label="Column 6">Cell D6</td>
        <td data-label="Column 7">Cell D7</td>
        <td data-label="Column 8">Cell D8</td>
      </tr>
    </tbody>
  </table>
</div>


## Additional table styles

### Right-aligned cells.

Column 3 should be right aligned.

<table class="table__stack-on-small">
  <thead>
    <tr>
      <th>Column 1</th>
      <th>Column 2</th>
      <th>Column 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Column 1">Row A</td>
      <td data-label="Column 2">Cell A2</td>
      <td data-label="Column 3" class="table__right-align">Cell A3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row B</td>
      <td data-label="Column 2">Cell B2</td>
      <td data-label="Column 3" class="table__right-align">Cell B3</td>
    </tr>
  </tbody>
</table>

### Standard table, with stripes

<table class="table__striped">
  <thead>
    <tr>
      <th>Column 1</th>
      <th>Column 2</th>
      <th>Column 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Column 1">Row A</td>
      <td data-label="Column 2">Cell A2</td>
      <td data-label="Column 3">Cell A3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row B</td>
      <td data-label="Column 2">Cell B2</td>
      <td data-label="Column 3">Cell B3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row C</td>
      <td data-label="Column 2">Cell C2</td>
      <td data-label="Column 3">Cell C3</td>
    </tr>
    <tr>
      <td data-label="Column 1">Row D</td>
      <td data-label="Column 2">Cell D2</td>
      <td data-label="Column 3">Cell D3</td>
    </tr>
  </tbody>
</table>


## Sortable Tables

### Sample Sortable Table

<table class="table__sortable">
  <thead>
      <tr>
          <th>
              Agency
          </th>
          <th>
            <button class="sortable">
              Languages
            </button>
          </th>
          <th>
            <button class="sortable sortable__start-up" data-sort_type="number">
              Distance
            </button>
          </th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td>
              Alpha
          </td>
          <td data-label="Languages">
              English
          </td>
          <td data-label="Distance">
              2.6 mi
          </td>
      </tr>
      <tr>
          <td>
              Beta
          </td>
          <td data-label="Languages">
              English, Spanish
          </td>
          <td data-label="Distance">
              1.4 mi
          </td>
      </tr>
      <tr>
          <td>
              Gamma
          </td>
          <td data-label="Languages">
              English, French, Spanish
          </td>
          <td data-label="Distance">
              1.4 mi
          </td>
      </tr>
      <tr>
          <td>
              Delta
          </td>
          <td data-label="Languages">
              English, Spanish
          </td>
          <td data-label="Distance">
              3.2 mi
          </td>
      </tr>
      <tr>
          <td>
              Epsilon
          </td>
          <td data-label="Languages">
              English
          </td>
          <td data-label="Distance">
              1.6 mi
          </td>
      </tr>
      <tr>
          <td>
            Zeta
          </td>
          <td data-label="Languages">
            English, Spanish
          </td>
          <td data-label="Distance">
            1.2 mi
          </td>
      </tr>
      <tr>
          <td>
              Eta
          </td>
          <td data-label="Languages">
              English
          </td>
          <td data-label="Distance">
              11.1 mi
          </td>
      </tr>
  </tbody>
</table>

# Temporary Documentation for components

#### Custom select


#### Custom select with input

```html
<!-- Components must be wrapped with row class -->
<div class="row">
  
  <!-- Column for select component -->
  <div class="col-sm-3 select-col">
    <label class="def-label" for="">
      <div class="c-select">

        <!-- fontawesome dropdown icon -->
        <span class="dropdown-control">
          <i class="fa fa-chevron-down"></i>
        </span>

        <!-- Basic Styled Select(Extended by the button compo.) -->
        <select class="basic-select" name="" id="">
          <option value="">Facebook</option>
        </select>

      </div>
    </label>
  </div>

  <!-- Column for input component -->
  <div class="col-sm-9 input-col">
    <label class="def-label" for="">&nbsp;

      <!-- Basic Style for input -->
      <input class="basic-input" type="text">
    </label>
  </div>

</div>
```

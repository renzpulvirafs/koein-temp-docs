# Koein custom component cheatsheet

#### Input
```html
<input class="basic-input">
```

##### Example
![input](https://user-images.githubusercontent.com/42379594/44150827-406b4ccc-a0d3-11e8-9c1f-d00438f63ab7.png)



#### Checkbox
By default the `<input>` tag is hidden from the user
so we can show our own customized/styled checkbox.
```html
<label class="checkbox-container">Yes·
  <input type="checkbox" checked="checked">
  <span class="checkmark"></span>
</label>                                    
```
##### Example
![checkbox](https://user-images.githubusercontent.com/42379594/44149872-288cdfc4-a0d0-11e8-8f7c-9e1ea9014d1a.png)



#### Custom select
```html
<div class="c-select"> <!-- Custom Select Wrapper -->
  <span class="dropdown-control"> <!-- Dropdown-icon -->
    <i class="fa fa-chevron-down"></i>
  </span>
  
  <select class="basic-select" name="" id=""> <!-- Basic styled select -->
    <option value="">Facebook</option>
  </select>
</div>
```

##### Example
![select](https://user-images.githubusercontent.com/42379594/44150828-41e2358e-a0d3-11e8-9222-5578391690c6.png)



#### Custom select with input

```html
<!-- Components must be wrapped with row class and sel-put class-->
<div class="row sel-put">
  <div class="col-sm-6 remove-p-r">
    <div class="row">
      <div class="form__controls col-sm-3 pr-0 select-col">
        <label class="def-label" for="">Social Media
          <div class="c-select">
            <span class="dropdown-control">
              <i class="fa fa-chevron-down"></i>
            </span>
            <select class="selput-select border-right-0" name="" id="">
              <option value="">Facebook</option>
            </select>
          </div>
        </label>
      </div>
      <div class="form__controls col-sm-9 pl-0 input-col">
        <label class="def-label" for="">&nbsp;
          <input class="basic-input" type="text">
        </label>
      </div>
    </div>
  </div>
</div>
```

##### Example
![select-with-input](https://user-images.githubusercontent.com/42379594/44152383-fd56815e-a0d7-11e8-81b6-b333f6705267.png)

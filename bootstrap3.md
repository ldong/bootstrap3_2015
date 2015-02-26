# Bootstarp 3

Author: Lin Dong

Date: Thu Feb 26 02:44:40 PST 2015

Notes I took while diving deep with [Adi Purdila](https://webdesign.tutsplus.com/courses/bootstrap-30-essentials)

Please note that the version of bootstrap used was **3.0**.

See my previous notes for [bootstrap2](https://github.com/ldong/bootstrap2_2013)

## Meta

Meta
1. extra-small devices: xs < 768px
2. small device: sm >= 768px
3. medium devices: md >= 992px
4. large devies: lg >= 1200px


## Layout

Bootstrap became fluid instead of fixed, mobile first, and everything is flat.

Using theme.css to get the bootstrap2 old look.

3 div element for layout:
1. row
2. col
3. col-offset-number

## New Stuff

1. `push / pull`
2. `glyphicon`
3. `list-group`

Panel:

* header
* body
* footer

## Navbar
```
<nav class='navbar navbar-defualt' role='navigation'>
  <div class="navbar-header">
    <button class="navbar-toggle" type="button" data-toggle='collapse' data-toggle='#test-navbar'>
      <span class='sr-only'>Toggle Navigation</span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
    </button>
    <a class="navbar-brand" href="#">The brand</a>
  </div>

  <div class="collapse navbar-collapse" id='test-navbar'>
    <p class="navbar-text navbar-right">Signed in as <a class="navbar-link" href="#">Hi</a></p>
  </div>
</div>

```

## Modal

```
modal fade
  modal-dialog
    modal-content
      modal-header
        modal-title
      modal-body
      modal-footer
```

## Removed

`submenus`, `typeahead`, `accordion`. [Details](http://getbootstrap.com/migration/)


```html
<button id="demo-collapse" class="collapse in" data-toggle='collapse' data-target='#demo-collapse'></button>

<div id="dmo-collapse" class="collapse in">
  <p>Ipsum sunt in voluptate aspernatur et. Voluptatibus atque maxime beatae?</p>
</div>

<div id="accordion" class="panel-group">

  <div class="panel panel-default">
  	<div class="panel-heading">
      <h4 class="panel-title">
        <a href="#collapse-1" data-toggle='collapse' data-parent='#accordion'>
          Toggle group 1
        </a>
      </h4>
    </div>
    <div id="collapse-1" class="panel-collapse collapse in">
      <div class="panel-body">
      <p>Adipisicing est a praesentium beatae esse quasi at ratione ipsam.</p>
      </div>
    </div>
  </div>
</div>
```

Typeahead can be found [here](https://twitter.github.io/typeahead.js/examples/)



## Form
All textual `<input>`, `<textarea>`, and `<select>` elements with class .form-control have a width of 100%.

[form-control(http://www.w3schools.com/bootstrap/bootstrap_forms.asp)

# Reference

[HTML5 Semantic Elements](http://www.w3schools.com/html/html5_semantic_elements.asp)

[Block Level Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)

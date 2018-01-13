# materialize-rtl
materialize rtl support

added after Original materialize:
```html
<!-- materialize -->
<link rel="stylesheet" href="materialize.min.css"/>

<!-- materialize right-to-left -->
<link rel="stylesheet" href="materialize.rtl.min.css"/>
```

CDN:
```html
<!-- latest materialize -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0-alpha.3/css/materialize.min.css"/>

<!-- materialize right-to-left -->
<link rel="stylesheet" href="https://rawgit.com/atechninfo/materialize-rtl/master/materialize.rtl.min.css"/>
```

material icons (add the class "rtlx"):
```html
<i class="material-icons rtlx">play_arrow</i>
```

Navbar:
```html
  <nav>
    <div class="nav-wrapper">
      <a href="#" class="brand-logo">Logo</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="sass.html">Sass</a></li>
        <li><a href="badges.html">Components</a></li>
        <li><a href="collapsible.html">JavaScript</a></li>
      </ul>
    </div>
  </nav>
```
  
Sidenav:
```javascript
$('.sidenav').sidenav({
  edge: 'right'
});
```

Range:  
```javascript
// -> https://refreshless.com/nouislider/slider-options/#section-direction
var slider = document.getElementById('my-range');
noUiSlider.create(slider, {
  //...
  direction: 'rtl',
  //...
});
```


support "Offsets, Push and Pull"  http://next.materializecss.com/grid.html#grid-offsets

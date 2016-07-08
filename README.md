# BASIC-ISOTOPE
**Filtering**
```
$grid.isotope({ filter: '*' })
```
Isotope can hide and show item elements with the filter option. Items that match that filter will be shown. Items that do not match will be hidden.

**Selectors**
```
<div class="grid">
<div class="element-item transition metal">...</div>
<div class="element-item post-transition metal">...</div>
<div class="element-item alkali metal">...</div>
<div class="element-item transition metal">...</div>
<div class="element-item lanthanoid metal inner-transition">...</div>
<div class="element-item halogen nonmetal">...</div>
<div class="element-item alkaline-earth metal">...</div>
</div>
```

The simplest way to filter items is with selectors, like classes. For example, each item element can have several identifying classes: transition, metal, lanthanoid, alkali, etc.

Preview: http://codepen.io/raphalimadev/pen/KrvxjE

Site official: http://isotope.metafizzy.co

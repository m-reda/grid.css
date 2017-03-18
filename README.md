# Pure CSS grid system
Weekend project.

### Columns
Screen  | Class Prefix | Screen Size
--------|--------------|------------
Mobile  | .m           | <768px
Tablet  | .t           | 768px to 991px
Browser | .b           | 992px to 1199px
Large   | .l           | ≥ 1200px

Screen  | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10   | 11   | 12
--------|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|------|-----
Mobile  | .m1 | .m2 | .m3 | .m4 | .m5 | .m6 | .m7 | .m8 | .m9 | .m10 | .m11 | .m12
Tablet  | .t1 | .t2 | .t3 | .t4 | .t5 | .t6 | .t7 | .t8 | .t9 | .t10 | .t11 | .t12
Browser | .b1 | .b2 | .b3 | .b4 | .b5 | .b6 | .b7 | .b8 | .b9 | .b10 | .b11 | .b12
Large   | .l1 | .l2 | .l3 | .l4 | .l5 | .l6 | .l7 | .l8 | .l9 | .l10 | .l11 | .l12

-----------

### Visibility
Screen  | Visible | Hidden
--------|---------|--------
Mobile  | .m-show | .m-hide
Tablet  | .t-show | .t-hide
Browser | .b-show | .b-hide
Large   | .l-show | .l-hide

-----------

### Container Width
Screen  | Screen Width     | Container Width
--------|------------------|----------------
Mobile  | 1200px or higher |	1170px
Tablet  | 992px to 1199px  |	970px
Browser | 768px to 991px   |	750px
Large   | Less than 768px  |	100%

-----------

### Customize by SASS
Variable          | Type      | Default Value
------------------|-----------|------------------------------
$direction        | *String*  | rtl
$columnsNumber    | *Integer* | 12
$screensNames     | *Array*   | ('m', 't', 'b', 'l')
$screensSizes     | *Array*   | (0, 768px, 992px, 1200px)
$containerWidth   | *Array*   | (100%, 750px, 970px, 1170px);
$columnsPrefix    | *String*  | *Empty*


-----------

### Example
```html
<div class="container">
    <div class="row">
        <div class="m6 b4"></div>
        <div class="m6 b8"></div>
    </div>
</div>
```

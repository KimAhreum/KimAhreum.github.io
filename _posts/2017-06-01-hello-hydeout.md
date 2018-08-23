---
layout: post
title: Hello Hydeout! Hello Ahreum! 
---

#ONE
##TWO
###THREE
####four
#####five
######six(MAX)


### Yellow Box
```scss
$sidebar-bg-color: #202020 !default;
$sidebar-sticky: true !default;
$layout-reverse: false !default;
$link-color: #268bd2 !default;
```

To override these variables, create your own `assets/css/main.scss` file.
Define your own variables, then import in Hydeout's SCSS, like so:

### White Box
```
---
# Jekyll needs front matter for SCSS files
---

$sidebar-bg-color: #ac4142;
$link-color: #ac4142;
$sidebar-sticky: false;
@import "hydeout";
```

See the [_variables](_sass/hydeout/_variables.scss) file for other variables
you can override.

### Box
`_includes/custom-head.html` 
`_includes/custom-foot.html`.

### New Features

* Hydeout also adds a new tags page (accessible in the sidebar) and a new
  "category" layout for dedicated category pages.

  ```yaml
  disqus:
    shortname: my-disqus-shortname
  ```


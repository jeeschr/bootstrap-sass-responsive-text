# Responsive Type for Bootstrap Sass

Add responsive type to Bootstrap using Sass. Tested with [bootstrap-sass](https://github.com/twbs/bootstrap-sass) v. 3.3.6.

### Customizations

Set base font-size and line-height at each breakpoint

Use scale values to transform sizes

Allow for different type scales to be applied for each breakpoint

### Note

This changes sizes of headings and body text only. This will not work on text on buttons, badges, tooltips, popovers, carousel controls, and some form elements.

### Usage

Place both **responsive-less.scss** and **responsive-type-variables.scss** in the bootstrap-sass folder. 

Make sure to add

```
@import "responsive-type-variables";
```

after

```
@import "bootstrap/variables";
``` 

And add

```
@import "responsive-type";
```

after

```
@import "bootstrap/type";
``` 

in the _bootstrap.scss file.

### Thanks

This Sass port is inspired by https://github.com/rkhleics/bootstrap-responsive-type courtesy **Andy Babic** - <http://twitter.com/andyjbabic>

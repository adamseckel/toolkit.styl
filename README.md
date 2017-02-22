# toolkit.styl
tachyons.io inspired Atomic css classes in Stylus and CSS3 for fast, mobile-first, prototyping and web design.


Why did I write this in stylus? Also, why didn't I fork tachyons.io?

This is an tiny (1kb gzipped) unopinionated, atomic css library builder. 

Enter your own values in src/variables.styl, and compile the library with your projects colors, font-scale, and breakpoints, or use the default.

# The Framework:
`.mv-10` applies `margin-top: 10; margin-bottom: 10`

`.mv-10-lg` applies `margin-top: 10; margin-bottom: 10;` to devices with screen size larger than your `lg` breakpoint
`10` is a number in the unit of your specification, `px`, `em`, `rem` etc.

# Customize:

Your projects offsts to use for margins, paddings, gutters
```
$offsets = 0 5 10 20 40 60
```

Your projects default Border Properties
```
$border-width = 1
$border-radius = 2px
```

Your projects default Unit
```
$unit = 'px'
```

Your projects breakpoints
```
$breakpoints = {
  sm: 0,
  lg: 1024
}
```

Your projects Colors as a `name: hex`, object.
```
$colors = {
  black: #000000
}
```

Your projects font-sizes as a `name: font-size`, object.
```
$font-scale = {
  '1': 60,
  '2': 30,
  '3': 20,
  '4': 18,
  '5': 12,
  '6': 10
}
```

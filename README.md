# Kite CSS

Light weight & robust layout helper CSS Framework. 

# Usage

```html
<div class="grid">
	<div class="grid__cell grid__cell-3">
		<p>3</p>
	</div>	
	<div class="grid__cell grid__cell-9">
		<p>9</p>
	</div>	
</div>
```

The `.grid` element is grid-row, the `.grid__cell` element is grid-cell.  
The `.grid__cell` element must be the child of a `.grid`.

The `.grid__cell` has paddings for side gutter, so you should not style it. You should style inner element.

# Customize

Default Kite styles are:

- 12 units.
- 20px gutter (`padding-left: 10px; padding-right: 10px`).
- 60px columm.
- Fixed 960px container (`($column + $gutter) * $unit`).

You can change these styles. See kite.scss Setting section.

# Browser Support and Testing

- Latest Stable: Chrome, Safari

We need more tests! ;(

# History

## 0.0.1 (2014-02-21)

- Preview release

# Special thanks

It is inspired by both [Griddle](https://github.com/necolas/griddle) and [csswizardry-grids](https://github.com/csswizardry/csswizardry-grids).

# License

The MIT License.

Copyright (c) 2014 Hiroki Tani <contact@inkdesign.jp>
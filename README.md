# Grid

## A Desktop First Grid System
Simply because most of the time you (well I) get a design made for desktop and you have to figure out along the way how to make it look sweet on smaller devices.


## Ok, so now?
... Nothing here atm



## How to use
### Implement
Take the grid folder, add it to your project and `@import "grid/grid"`.

### Settings
All settings/vars can be overwritten in your own sass file, just add the vars before you include the grid and those will be used instead of the default ones. Never change the values in the grid files incase you want to update.

For example:

```scss
$fixed-grid: true;
@import "grid/grid";
```

This will change the container from being fluid to using fixed breakpoints.

### Markup
```html
<div class="container">
	<div class="row">
		<div class="col-3 col-md-6 col-xs-12">One</div>
		<div class="col-3 col-md-6 col-xs-12">Two</div>
		<div class="col-3 col-md-6 col-xs-12">Three</div>
		<div class="col-3 col-md-6 col-xs-12">Four</div>
	</div>
</div>
```
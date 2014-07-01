# Grid

## A Desktop First Grid System
Simply because not everyone is using a modern browser, and you do not want these users to have to use the mobile version.


## Ok, so now?
... Nothing here atm



## How to use
### Implement
Take the grid folder, add it to your project and `@import "grid/grid"`. Or you can take one of the `.css` files in the css folder.

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
angular-fixie-menu
==================

Angularjs directive to create "fixie menus" that will remain fixed once a user scrolls past a specified offset-top or element id.

### Much Work Needed

This is still pretty rough - just look at the source and you'll see.... Refactoring, Karma tests, and example page need to be done.

## Examples

### Include module
```javascript
angular.module('app', ['8bitsquid.fixieMenu']);
```

#### Menu fixed when scrolled past known offset-top position
```html
<div class="my-menu" fixie-menu fixie-menu-offset="196">
    ... Menu Markup ...
</div>
```

#### Menu fixed when scrolled past element
```html
<div class="my-menu" fixie-menu fixie-menu-offset="my-element-id">
    ... Menu Markup ...
</div>
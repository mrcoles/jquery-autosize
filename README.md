jquery-autosize
======================

jQuery Autosize **updated for meteor 0.9.0** ("a plugin to automatically adjust textarea height") repackaged for Meteor.

## Installation

1. `meteor add copleykj:jquery-autosize`
1. Call `this.$(selector).autosize()` in your `Template.templateName.onRendered(…)` callback, where `selector` is a jQuery selector.

Example:

````javascript
Template.templateName.onRendered({
  this.$('#textarea-selector').autosize(); // `this.$` scopes queries to the current template
});
````

## Documentation

http://www.jacklmoore.com/autosize/

## Original package

https://github.com/jackmoore/autosize/

## Author

The Meteor repackage was created by Spendflow and updated by Kelly Copley (@copleykj) for the new 0.9.0 packaging system.

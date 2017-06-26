# search-fields-dialog

A Polymer Element showing search fields in a modal dialog.

### Example
```html
<search-fields-dialog
	date-config='{"dateStart": "postingDate", "dateEnd": "postingDate"}'
	search-fields-config="[[searchFieldsConfig]]"
	search-parameters="{{searchParameters}}"
	process-request="{{processRequest}}">
</search-fields-dialog>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve


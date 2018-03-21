# search-fields-dialog

A Polymer Element showing search fields in a configurable styled dialog.

### Example
```html
<search-fields-button
  toggle-dialog="[[buttonCallbacks.toggleDialog]]"
  handle-search="[[buttonCallbacks.handleSearch]]"
  free-text-search-fields="[[freeTextSearchFields]]">
</search-fields-button>

<search-fields-dialog
  button-callbacks="{{buttonCallbacks}}"
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


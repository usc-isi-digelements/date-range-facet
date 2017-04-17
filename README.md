# date-range-facet

A Polymer Element that displays date pickers to be used for a range filter.

Example:
```html
  <date-range-facet
    style="width: 250px;"
    date-start-key="dateStart"
    date-start-title="From"
    date-start-prefix-label="From"
    date-start-identifier="start"
    date-end-key="dateEnd"
    date-end-title="To"
    date-end-prefix-label="To"
    date-end-identifier="end"
    search-param-subset="{{facetSelection.dates}}">
  </date-range-facet>
```

### Styling

To style elements within, see the styling info for [date-picker-display](https://github.com/DigElements/date-picker-display).

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

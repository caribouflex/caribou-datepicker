[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/PolymerElements/caribou-datepicker)

## &lt;caribou-datepicker&gt;

`<caribou-datepicker>` is a Polymer 2 custom input element with a picker overlay used to select a date.

This element follow the material design guidelines : [Pickers](https://material.io/guidelines/components/pickers.html#pickers-usage)

This element can be used juste like that, but also be decomposed.

If you don't want to use the input build in, you can use your custom input and juste use the `<caribou-calendar>` element.

### Styling

To customize the `<caribou-datepicker>` globally, on you instance you can set these properties : 

Custom property | Description | Default
----------------|-------------|----------
`--header-overlay-background-color` | Color of the header background | `--primary-color`
`--header-text-secondary-color` | Color of the text not in focus in the header | `--primary-light-color`
`--action-button-color`| Text color of the action button | `--primary-color`
`--current-active-day-color`| Color of the current date value | `--primary-color`
`--current-selected-day-color`| Color of the selected date | `--primary-color`
`--current-selected-year-color`| Color of the current year selected | `--primary-color`


To see the styling by element check the `<caribou-calendar>`, `<caribou-year>`, `<caribou-month>`.

## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
    <link rel="import" href="caribou-datepicker.html">
    <style>html{font-family: 'Roboto', sans-serif; height:500px;}</style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<caribou-datepicker init-with-current-date label="My Caribou Date Picker" error-massage="Oops.. You are out of time !">
</caribou-datepicker>
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## License
Apache License 2.0


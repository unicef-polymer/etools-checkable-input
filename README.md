# \<etools-checkable-input\>

Checkbox or radio input with label aligned top, right, bottom and left.
It also has a disabled state. It's based on paper-checkbox and paper-radio-button.

## Usage
```html
<etools-checkable-input type="checkbox" label="Your label" label-alignment="top" checked="true" is-disabled="true" label-text-transform="capitalize"></etools-checkable-input>
<etools-checkable-input type="radio" label="Your label" label-alignment="right" checked="true" is-disabled="false" label-text-transform="uppercase"></etools-checkable-input>
```

You can combine the element attributes as you need.
Available attributes:
* type: String, it can be 'checkbox' or 'radio'
* label: String, the element label
* labelAlignment: String, possible values: 'top', 'bottom', 'right', 'left'
* checked: Boolean, the element value
* isDisabled: Boolean, disabled state
* labelTextTransform: String, values: 'capitalize' or 'uppercase'

## Styling

You can use defined variables and mixins to change element style.

Custom property | Description | Default
----------------|-------------|----------
`--etools-checkable-input-size` | Input size | `16px`
`--etools-checkable-input-checked-color` | Input checked color | `#4a90e2`
`--etools-checkable-input-unchecked-color` | Input unchecked color | `#737373`
`--etools-checkable-input-font-size` | Label font size | `12px`
`--etools-checkable-input-label` | Mixin applied to the label | `{}`
`--etools-checkable-input-disabled-color` | Disabled color | `#d1d1d1`
`--etools-checkable-input-ripple-color` | Radio btn ripple(#ink) color | `--primary-color`

## Install
```bash
$ bower install --save etools-checkable-input
```

## Preview element locally
Install needed dependencies by running: `$ bower install`.
Make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `$ polymer serve` to serve your element application locally.

## Running Tests

```
$ polymer test
```

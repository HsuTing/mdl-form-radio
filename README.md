# Radio for mdl-form

## Start

Install package:
```
  npm install mdl-form mdl-form-radio react jquery
```

You need to see [mdl-form](https://github.com/HsuTing/mdl-form.git).

## Parameter

- `style` -> change style
- `className` -> class
- `item` -> array of radios
  * `style` -> change the style of this radio
  * `value` -> this radio value
  * `label` -> name of this radio
  * `isChecked` -> if you use `isChecked: true`, it will be checked.
- `isNotRequire` -> if you use `isNotRequire: true`, it can be empty.
- `change`(function) -> you can do something when radio is click. `1st` argument is this component value.

## Example

```
{   
  'id': 'component_id',
  'className': 'class',
  'item': [
    {
      'style': {'color': 'red'},
      'value': '1',
      'label': 'radio-0'
    },
    {
      'style': {'color': 'blue'},
      'value': '2',
      'label': 'radio-1'
    }
  ]
}
```

# Radio for mdl-form

## Parameter

- `style` -> change style
- `item` -> array of radios
  * `style` -> change the style of this radio
  * `value` -> this radio value
  * `label` -> name of this radio
- `isNotRequire` -> if you use `isNotRequire: true`, it can be empty.
- `change`(function) -> you can do something when radio is click. `1st` argument is this component value.

## Example

```
{   
  'id': 'component_id',
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

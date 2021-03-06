# myp-drawer

## Props

| Prop name    | Description | Type           | Values | Default                                                                                               |
| ------------ | ----------- | -------------- | ------ | ----------------------------------------------------------------------------------------------------- |
| pos          |             | string         | -      | 'bottom'                                                                                              |
| bgType       |             | string         | -      | 'none'                                                                                                |
| duration     |             | number         | -      | 300                                                                                                   |
| overlay      |             | object         | -      | {<br> timingFunction: ['ease-in', 'ease-out'],<br> duration: 300,<br> bg: '',<br> bgType: 'mask'<br>} |
| height       |             | number\|string | -      | 0                                                                                                     |
| standout     |             | number\|string | -      | '0'                                                                                                   |
| leftOffset   |             | number\|string | -      | -1                                                                                                    |
| rightOffset  |             | number\|string | -      | -1                                                                                                    |
| bottomOffset |             | number\|string | -      | -1                                                                                                    |
| topOffset    |             | number\|string | -      | -1                                                                                                    |
| width        |             | number\|string | -      | 750                                                                                                   |
| animation    |             | object         | -      | {<br> timingFunction: 'ease-in-out'<br>}                                                              |
| left         |             | string         | -      | '0'                                                                                                   |
| top          |             | string         | -      | '0'                                                                                                   |
| right        |             | string         | -      | '0'                                                                                                   |
| bottom       |             | string         | -      | '0'                                                                                                   |
| boxStyle     |             | string         | -      | ''                                                                                                    |

## Events

| Event name     | Type      | Description |
| -------------- | --------- | ----------- |
| overlayClicked | undefined |

## Slots

| Name    | Description | Bindings |
| ------- | ----------- | -------- |
| overlay |             |          |
| default |             |          |

---

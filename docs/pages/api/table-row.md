---
filename: /packages/material-ui/src/TableRow/TableRow.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# TableRow API

<p class="description">The API documentation of the TableRow React component. Learn more about the props and the CSS customization points.</p>

```js
import { TableRow } from '@material-ui/core';
```

Will automatically set dynamic row height
based on the material table element parent (head, body, etc).

## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">children</span> | <span class="prop-type">node</span> |  | Should be valid &lt;tr> children such as `TableCell`. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">component</span> | <span class="prop-type">elementType</span> | <span class="prop-default">'tr'</span> | The component used for the root node. Either a string to use a DOM element or a component. |
| <span class="prop-name">hover</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the table row will shade on hover. |
| <span class="prop-name">selected</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the table row will have the selected shading. |

The `ref` is forwarded to the root element.

Any other props supplied will be provided to the root element (native element).

## CSS

- Style sheet name: `MuiTableRow`.
- Style sheet details:

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">root</span> | <span class="prop-name">MuiTableRow-root</span> | Styles applied to the root element.
| <span class="prop-name">selected</span> | <span class="prop-name">Mui-selected</span> | Pseudo-class applied to the root element if `selected={true}`.
| <span class="prop-name">hover</span> | <span class="prop-name">MuiTableRow-hover</span> | Pseudo-class applied to the root element if `hover={true}`.
| <span class="prop-name">head</span> | <span class="prop-name">MuiTableRow-head</span> | Styles applied to the root element if table variant="head".
| <span class="prop-name">footer</span> | <span class="prop-name">MuiTableRow-footer</span> | Styles applied to the root element if table variant="footer".

You can override the style of the component thanks to one of these customization points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If that's not sufficient, you can check the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/TableRow/TableRow.js) for more detail.

## Notes

The component can cause issues in [StrictMode](https://reactjs.org/docs/strict-mode.html).

## Demos

- [Tables](/components/tables/)


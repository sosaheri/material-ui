---
filename: /packages/material-ui/src/Menu/Menu.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# Menu API

<p class="description">The API documentation of the Menu React component. Learn more about the props and the CSS customization points.</p>

```js
import { Menu } from '@material-ui/core';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">anchorEl</span> | <span class="prop-type">object<br>&#124;&nbsp;func</span> |  | The DOM element used to set the position of the menu. |
| <span class="prop-name">autoFocus</span> | <span class="prop-type">bool</span> |  | If `true` (default), the menu list (possibly a particular item depending on the menu variant) will receive focus on open. |
| <span class="prop-name">children</span> | <span class="prop-type">node</span> |  | Menu contents, normally `MenuItem`s. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">disableAutoFocusItem</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | Same as `autoFocus=false`. |
| <span class="prop-name">MenuListProps</span> | <span class="prop-type">object</span> | <span class="prop-default">{}</span> | Props applied to the [`MenuList`](/api/menu-list/) element. |
| <span class="prop-name">onClose</span> | <span class="prop-type">func</span> |  | Callback fired when the component requests to be closed.<br><br>**Signature:**<br>`function(event: object, reason: string) => void`<br>*event:* The event source of the callback<br>*reason:* Can be:`"escapeKeyDown"`, `"backdropClick"`, `"tabKeyDown"` |
| <span class="prop-name">onEnter</span> | <span class="prop-type">func</span> |  | Callback fired before the Menu enters. |
| <span class="prop-name">onEntered</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu has entered. |
| <span class="prop-name">onEntering</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu is entering. |
| <span class="prop-name">onExit</span> | <span class="prop-type">func</span> |  | Callback fired before the Menu exits. |
| <span class="prop-name">onExited</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu has exited. |
| <span class="prop-name">onExiting</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu is exiting. |
| <span class="prop-name required">open&nbsp;*</span> | <span class="prop-type">bool</span> |  | If `true`, the menu is visible. |
| <span class="prop-name">PopoverClasses</span> | <span class="prop-type">object</span> |  | `classes` prop applied to the [`Popover`](/api/popover/) element. |
| <span class="prop-name">transitionDuration</span> | <span class="prop-type">number<br>&#124;&nbsp;{ enter?: number, exit?: number }<br>&#124;&nbsp;'auto'</span> | <span class="prop-default">'auto'</span> | The length of the transition in `ms`, or 'auto' |
| <span class="prop-name">variant</span> | <span class="prop-type">'menu'<br>&#124;&nbsp;'selectedMenu'</span> | <span class="prop-default">'selectedMenu'</span> | The variant to use. Use `menu` to prevent selected items from impacting the initial focus and the vertical alignment relative to the anchor element. |

The `ref` is forwarded to the root element.

Any other props supplied will be provided to the root element ([Popover](/api/popover/)).

## CSS

- Style sheet name: `MuiMenu`.
- Style sheet details:

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">paper</span> | <span class="prop-name">MuiMenu-paper</span> | Styles applied to the `Paper` component.
| <span class="prop-name">list</span> | <span class="prop-name">MuiMenu-list</span> | Styles applied to the `List` component via `MenuList`.

You can override the style of the component thanks to one of these customization points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If that's not sufficient, you can check the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/Menu/Menu.js) for more detail.

## Inheritance

The props of the [Popover](/api/popover/) component are also available.
You can take advantage of this behavior to [target nested components](/guides/api/#spread).

## Notes

The component can cause issues in [StrictMode](https://reactjs.org/docs/strict-mode.html).

## Demos

- [App Bar](/components/app-bar/)
- [Menus](/components/menus/)


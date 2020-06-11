---
filename: /packages/material-ui-lab/src/TimelineOppositeContent/TimelineOppositeContent.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# TimelineOppositeContent API

<p class="description">The API documentation of the TimelineOppositeContent React component. Learn more about the props and the CSS customization points.</p>

## Import

```js
import TimelineOppositeContent from '@material-ui/lab/TimelineOppositeContent';
// or
import { TimelineOppositeContent } from '@material-ui/lab';
```

You can learn more about the difference by [reading this guide](/guides/minimizing-bundle-size/).



## Component name

The `MuiTimelineOppositeContent` name can be used for providing [default props](/customization/globals/#default-props) or [style overrides](/customization/globals/#css) at the theme level.

## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">children</span> | <span class="prop-type">node</span> |  | The content of the component. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |

The `ref` is forwarded to the root element.

Any other props supplied will be provided to the root element (native element).

## CSS

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">root</span> | <span class="prop-name">.MuiTimelineOppositeContent-root</span> | Styles applied to the root element.
| <span class="prop-name">alignRight</span> | <span class="prop-name">.MuiTimelineOppositeContent-alignRight</span> | Styles applied to the root element if `align="right"`.

You can override the style of the component thanks to one of these customization points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If that's not sufficient, you can check the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui-lab/src/TimelineOppositeContent/TimelineOppositeContent.js) for more detail.

## Demos

- [Timeline](/components/timeline/)

---
filename: /src/styles/MuiThemeProvider.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# MuiThemeProvider

This component takes a `theme` property.
It makes the `theme` available down the React tree thanks to React context.
This component should preferably be used at **the root of your component tree**.

## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span style="color: #31a148">children *</span> | node |  | You can only provide a single element with react@15, a node with react@16. |
| disableStylesGeneration | bool | false | You can disable the generation of the styles with this option. It can be useful when traversing the React tree outside of the HTML rendering step on the server. Let's say you are using react-apollo to extract all the queries made by the interface server side. You can significantly speed up the traversal with this property. |
| sheetsManager | object | null | The sheetsManager is used to deduplicate style sheet injection in the page. It's deduplicating using the (theme, styles) couple. On the server, you should provide a new instance for each request. |
| <span style="color: #31a148">theme *</span> | union:&nbsp;object&nbsp;&#124;<br>&nbsp;func<br> |  | A theme object. |

Any other properties supplied will be [spread to the root element](/customization/api#spread).


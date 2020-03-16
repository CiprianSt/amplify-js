# amplify-button

<!-- Auto Generated Below -->


## Properties

| Property            | Attribute  | Description                                                 | Type                              | Default     |
| ------------------- | ---------- | ----------------------------------------------------------- | --------------------------------- | ----------- |
| `disabled`          | `disabled` | Disabled state of the button                                | `boolean`                         | `false`     |
| `handleButtonClick` | --         | (Optional) Callback called when a user clicks on the button | `(evt: Event) => void`            | `undefined` |
| `type`              | `type`     | Type of the button: 'button', 'submit' or 'reset'           | `"button" or "reset" or "submit"` | `'button'`  |


## Dependencies

### Used by

 - [amplify-form-section](../amplify-form-section)
 - [amplify-sign-in](../amplify-sign-in)
 - [amplify-sign-out](../amplify-sign-out)
 - [amplify-sign-up](../amplify-sign-up)
 - [rock-paper-scissor](../amplify-examples/rock-paper-scissor)

### Graph
```mermaid
graph TD;
  amplify-form-section --> amplify-button
  amplify-sign-in --> amplify-button
  amplify-sign-out --> amplify-button
  amplify-sign-up --> amplify-button
  rock-paper-scissor --> amplify-button
  style amplify-button fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
`<simple-alert>` shows an alert on your page and device notification.

To use, insert `<simple-alert>` in the body:

    <body>
      <simple-alert></simple-alert>

Example:
    <body>
      <simple-alert autoshow message="Hello">
      </simple-alert>
    
To show the message instantly.

Example:
    <body>
      <simple-alert notify-device message="Hello">
      </simple-alert>
    
To enable push notifications per device.

### Styling
The following custom properties and mixins are available for styling:
Custom property | Description | Default

----------------------------|--------------------------------------------|----------

`--dark-primary-color` | The background-color of the message | `#303F9F`

`--text-primary-color` | The text color of the message       | `#ffffff`

### Fonts
The following variable is applied for the font of the element
`--paper-font-common-base`
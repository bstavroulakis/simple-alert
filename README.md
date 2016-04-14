### Status
[![Build Status](https://travis-ci.org/bstavroulakis/simple-alert.svg?branch=master)](https://travis-ci.org/bstavroulakis/simple-alert)

### General Info `<simple-alert>`

`<simple-alert>` shows an alert on your page and a push notification on your device.

To use, insert `<simple-alert>` in the body:

    <body>
      <simple-alert></simple-alert>

Example:

To show the message instantly.
```
    <body>
      <simple-alert autoshow message="Hello">
      </simple-alert>
``` 


Example:

To enable push notifications per device.

```
    <body>
      <simple-alert notify-device message="Hello">
      </simple-alert>
``` 


### Documentation Page

http://bstavroulakis.github.io/simple-alert/components/simple-alert/

### Demo Page

http://bstavroulakis.github.io/simple-alert/components/simple-alert/demo/

### Styling
The following custom properties and mixins are available for styling:
Custom property | Description | Default

----------------------------|--------------------------------------------|----------

`--dark-primary-color` | The background-color of the message | `#303F9F`

`--text-primary-color` | The text color of the message       | `#ffffff`

### Fonts
The following variable is applied for the font of the element
`--paper-font-common-base`
---
id: iframe
title: Iframe
---
# Iframe

Iframe widget is used to embed another HTML page into the current one and display iframes in your app.

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Iframe ](/img/widgets/iframe/iframe.png)

</div>

## Properties

### URL

Sets the **URL** of the page to embed.

### General
#### Tooltip

A Tooltip is often used to specify extra information about something when the user hovers the 
mouse pointer over the widget.

Under the <b>General</b> accordion, you can set the value in the string format. 
Now hovering over the widget will display the string as the tooltip.

<div style={{textAlign: 'center'}}>

![ToolJet - widget- button](/img/tooltip.png)

</div>

## Layout

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Iframe ](/img/widgets/iframe/layout.png)

</div>

### Show on desktop

Toggle on or off to display the widget in desktop view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.
### Show on mobile

Toggle on or off to display the widget in mobile view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.

## Styles

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Iframe ](/img/widgets/iframe/styles.png)

</div>

### Visibility

Toggle on or off to control the visibility of the widget. You can programmatically change its value by clicking on the `Fx` button next to it. If `{{false}}` the widget will not be visible after the app is deployed. By default, it's set to `{{true}}`.

### Disable

This is `off` by default, toggle `on` the switch to lock the widget and make it non-functional. You can also programmatically set the value by clicking on the `Fx` button next to it. If set to `{{true}}`, the widget will be locked and becomes non-functional. By default, its value is set to `{{false}}`.

:::info
Any property having `Fx` button next to its field can be **programmatically configured**.
:::
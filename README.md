# Nerd Wix Alert

Nerd Wix Alert is a web component that will display a toast-style alert message. The style of the message depends on if the alert is an error, info, success, or warn. 

## 🚀 Quick Start

Here are samples on how to use the different alert styles.

```js
$w("#alert").setAttribute("success", "This is a success message.");
$w("#alert").setAttribute("info", "This is an error message.");
$w("#alert").setAttribute("warn", "This is a warning message.");
$w("#alert").setAttribute("error", "This is an error message.");
```

### Settings

When you add the custom element to the page, there are two attributs you should set.

1. **duration** - Number of milliseconds for the alert to display. 
2. **position** - What part of the screen the alert should show. Valid values are: top-left, top-center, top-right, bottom-left, bottom-center, bottom-right

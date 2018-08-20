## Overview 
Checkbox are rendered by default as square boxes that are checked (ticked) when activated. They allow you to select single values for submission in a form (or not).

**Note:** Radio buttons are similar to checkboxes, but with an important distinction — radio buttons are grouped into a set in which only one radio button can be selected at a time, whereas checkboxes allow you to turn single values on and off. Where multiple controls exist, radio buttons allow one to be selected out of them all, whereas checkboxes allow multiple values to be selected.

## Usage
Checkbox component allows the users to select any combination of options in a group of check boxes. A group of check boxes is used for independent choices. A group of check boxes can also be used to select from a set of one or more choices.

### How to use   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

### Example 
Input the component field with the attribute value:
``` 
Checked = true
Id = check
```
Save it and run.
When the page is loaded the attribute "checked = true" specifies whether the checkbox is checked or not. And the "id = check" is the unique id given for the checkbox which can be used to apply styles or give reference to point to the checkbox.
## Associated Attributes
- **Checked:** Used to check whether the checkbox is checked or not.
- **Color:** Takes the color based on angular material thing.
- **Disabled:** Used to check whether the checkbox is disabled or not.
- **Id:** A unique id for the checkbox input.
- **Labelposition:** Specifies whether the label should appear after or before the checkbox. Defaults to 'after'
- **Name:** Specifies the name for the component
- **Required:** Used to check whether the checkbox is required or not.
- **Value:** Specifies the value attribute of the native input element.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


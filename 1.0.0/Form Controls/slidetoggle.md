{
"name" : "slide-toggle",
"type" : "Component"
"category": “Form Controls”
"version" : "1.0.0",
"averageRating" : 1,
"description" : "Is an on/off control that can be toggled through clicking or dragging",
"guide" : "”,
"platformSupportVersion" : "4.0.0",
"publisher" : "Prashanth",
}

## Guide: 
### Overview: 
Slide toggle component is used to toggle between on/off. Toggle allows the user to change a setting between two states.

#### Usage
A toggle is a specialized control which has the ability to be selected. Typically a toggle is rendered similarly to a button.

#### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
Class = toggle
Text = on/off
```
Save it and run.
When the page is loaded "class = toggle" will assign the class name as toggle, which can be used to point to a class in a style sheet. And the "text = on/off" is the text that is displayed next to the component.

### Associated Attributes:
- **Style:** Used to specify the inline style. It is applied to the specific element.
- **Class:** It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
- **Required:** used to check whether the slide-toggle is required or not. Value should be boolean i.e. either true or false.
- **Text:** Specifies the text to be displayed for the slide-toggle when the application is run.
- **Id:** A unique id for the slide-toggle input.
- **Labelposition:** Whether the label should appear after or before the slide-toggle. Defaults to 'after'. Values to be specified are before and after.
- **Name:** Name value will be applied to the input element if present. Value should be either string or null.
- **Change:** An event will be dispatched each time the slide-toggle changes its value. ",
- **Checked:** Used to check whether the slide-toggle element is checked or not.
- **Color:** specifies the theme color for the component.

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +


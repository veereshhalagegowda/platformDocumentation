## Overview 
Slide toggle component is used to toggle between on/off. Toggle allows the user to change a setting between two states.

## Usage
A toggle is a specialized control which has the ability to be selected. Typically a toggle is rendered similarly to a button.

### How to use   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

### Example
Input the component field with the attribute value:
``` 
Class = toggle
Text = on/off
```
Save it and run.
When the page is loaded "class = toggle" will assign the class name as toggle, which can be used to point to a class in a style sheet. And the "text = on/off" is the text that is displayed next to the component.

## Associated Attributes
- **Style**: It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).

- **Class**: "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space seperated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
    ```css
    .class1 {
        border-radius:10px;
        flex-basis:10%;
        height:100px;
    }
    .class2 {
        border-radius:10px;
        flex-basis:10%;
        height:100px;
    }
    
- **Required:** used to check whether the slide-toggle is required or not. Value should be boolean i.e. either true or false.
- **Text:** Specifies the text to be displayed for the slide-toggle when the application is run.
- **Id:** A unique id for the slide-toggle input.
- **Labelposition:** Whether the label should appear after or before the slide-toggle. Defaults to 'after'. Values to be specified are before and after.
- **Name:** Name value will be applied to the input element if present. Value should be either string or null.
- **Change:** An event will be dispatched each time the slide-toggle changes its value. ",
- **Checked:** Used to check whether the slide-toggle element is checked or not.
- **Color:** specifies the theme color for the component.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

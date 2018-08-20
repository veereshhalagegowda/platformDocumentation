## Overview 
Button toggle component is used to toggle between on/off. When the button is clicked it will be activated and when the button is clicked again the button will be deactivated.

## Usage
A Toggle is a specialized control which has the ability to be selected. It is used to activate button on/off.

### How to use   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

### Example 
Input the component field with the attribute value:
``` 
Class = toggle
buttonname = on/off
```
Save it and run.
When the page is loaded "class = toggle" attribute will assign the class name as toggle, which can be used to point to a class in a style sheet. The "buttonname = on/off" attribute is the name given to the button that is displayed when the page is loaded.

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
    
    ```
- **Value:** MatButtonToggleGroup reads this to assign its own value.
- **Buttonname:** Specifies the button name.
- **Name:** Name attribute for the underlying input element.
- **Id:** The unique ID for this button toggle.
- **Checked:** Used to check whether the button is checked. Value should be boolean i.e. either true or false.
- **Changed:** Is the event emitted when the group value changes.",
- **Click:** Is the event used to check whether the button is clicked or not. Value should be boolean i.e. either true or false.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:**
    - Angular CLI version: 5.0.0 +
    - Cordova version: 7.1.0 +

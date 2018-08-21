## Overview
The raisedbutton component represents a clickable button. The button appears raised compared to a normal button component.

## Usage
Raisedbutton provides the user a simple way to trigger an event, like searching for a query at a search engine, or to interact with dialog boxes, like confirming an action. It can be used to represent that the button is important.

### How to use   
1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example 
Input the component field with the attribute value:
``` 
buttonname = submit
Click = true
```
Save it and run.
When the page is loaded the value "buttonname = submit" will be name of the button that will be displayed on the button. And "click = true" is the event that check when the button is pressed.

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
- **Buttonname:** specifies the button name that is to be displayed on the screen.
- **Color:** takes the color based on angular material thing.
- **Click:** Is an event that checks when the button is clicked. The value should be boolean i.e. either true or false.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

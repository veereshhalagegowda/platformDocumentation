## Overview
Mini fab button is a button in round shape. Mini FABs (Floating Action Buttons) are standard material design components. They are shaped as a circle that represents a promoted action. When pressed, it may contain more related actions. Mini FABs as its name suggests are floating over the content in a fixed position.

## Usage
Mini fab component can be used to contain more related actions.

### How to use  
1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example
1. Input the component field(s) with the attribute value(s):
    ``` 
    fabicon = decorate
    Click = clickEvent()
    ```
    In the "Ts" file write the following function
    ```
    clickEvent() { 
        alert("Button clicked!!!");
    }
    ```
2. Save it and run.
3. When the page is loaded the value "fabicon = decorate" will be the name of the button that will be displayed on the button and "click = clickEvent()" is the event that checks when the button is pressed. On clicking the button the alert message "Button clicked!!!" will be displayed.

## Associated Attributes
- **Style**: It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).

- **Class**: "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space separated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
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
    
- **fabicon:** specifies the button text for the icon.
- **Color:** Takes the color based on the angular material thing.
- **Click:** Is an event that checks when the button is clicked.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


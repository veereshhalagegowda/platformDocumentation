## Overview: 
The tooltip will be displayed below the element but this can be configured using the matTooltipPosition input. The tooltip can be displayed above, below, left, or right of the element. By default the position will be below. If the tooltip should switch left/right positions, then the positions before and after should be used instead of left and right, respectively.

## Usage
Tooltip is used to display text (or other content) when you hover over an HTML element. 

### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

### Example: 
Input the component field with the attribute value:
``` 
matTooltip = This is tooltip
tooltip text = tooltip 
```
Save it and run.
When the page is loaded the value "matTooltip = This is tooltip" is the text that will be displayed when the mouse hovers over the tooltip area. And "tooltip text = tooltip" is text that is displyed on the tooltip field when the page is loaded.

## Associated Attributes:
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
    
- **Tooltip text:** Specifies the text that has to be displayed when the application is run.
- **Mattooltip:** It specifies the the message to be displayed in the tooltip. Value has to be string. Example: message: string
- **Mattooltipposition:** Allows the user to define the position of the tooltip relative to the parent element. Example: position: left | right | above | below | before |after
- **Mattooltipshowdelay:** Specifies the default delay in ms before showing the tooltip after show method is called 
- **Mattooltiphidedelay:** The default delay in ms before hiding the tooltip after hide method is called.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

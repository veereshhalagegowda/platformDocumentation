## Overview
The expansion-description component is used for describing the expansion panel components. It can be used inside the ExpansionPanelHeader component or it can be used individually to display the description.

## Usage
Expansion-description is used to write description for the expansion panel content. Only the description will be displayed.

### How to use  
1. Drag and drop the expansion panel component. 
2. Inside the expansion panel component, drag and drop the expansion header component. And inside expansion-header component drag and drop the expansion-description component.
3. Double click the expansion-description component to display the list of attributes that can be used with it.
4. Fill the attributes which are needed and save the page.

### Example
1. Input the component field with the attribute value:
``` 
description = This is a description panel
```
2. Save it and run.
3. When the page is loaded the attribute value "description = This is a description panel" will be displayed. And when the description is clicked, the expansion-header panel will be extended.

## Associated Attributes
- **Style:** It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).
- **Class:** "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space separated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
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
- **description:** This attribute used to give description for the expansion panel. 
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
- Angular CLI version: 5.0.0 + 
- Cordova version: 7.1.0 + 

## Overview
Tabs are used to navigate between different views within the same context. Only one view is rendered at a time. Tabs should always be used inside a “Tab Group” component.

## Usage
Tabs are useful for containing and navigating between contextually related but distinct contents.

### How to use

1. Drag and drop the “Tab Group” component from the “Navigation” category.
2. Drag and drop the “Tab” component(s) inside the “Tab Group” component.
3. Set the “label” attribute of the “Tab” component(s).
4. Drag and drop the components needed within each “Tab” component.
5. Save the changes.

### Example
1. Create a page.
2. Drag and drop the “Tab Group” component from the “Navigation” category.
3. Drag and drop 2 “Tab” components inside the “Tab Group” component.
4. Set the values of first and second Tabs' “label” property to “Image” and “Tab2” respectively.
5. Drag and drop "Image" component from the "Form Controls" category and set its attributes.
6. Drag and drop 2 “Card” components from “Layout” category into each of the tabs.
7. Set height of each card  to 50px. (style = height:50px;).
8. Set the color of each card. eg. color:pink. 
9. Save the changes.
10. Now, the tabs can be navigated.

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

- **label**: It is the name of the tab as seen in the app. Takes string as its value.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

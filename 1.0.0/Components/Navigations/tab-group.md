## Overview
Tabs should always be used inside a “Tab Group” component. “Tab Group” component is a container component that is used to contain one or more “Tab” components. “Tab” components should be contained in the “Tab Group” component.

## Usage
Tabgroup component used whenever tab(s) are used. A tab can not exist outside of the tab group component.

### How to use

1. Drag and drop the “Tab Group” Component from the “Navigation” category.
2. Drag and drop the “Tab” component(s) inside the “Tab Group” component.
3. Set the “label” attribute of the “Tab” component(s).
4. Drag and drop the components needed within each “Tab” component.

### Example
1. Create a page.
2. Drag and drop the “Tab Group” Component from the “Navigation” category.
3. Drag and drop 3 “Tab” components inside the “Tab Group” component.
4. Set the values of 1st, 2nd and 3rd Tab’s “label” property as “Tab1”, “Tab2” and “Tab3” respectively.
5. Drag and drop a “Card” component from “Layout” category into each of the tabs.
6. Set height of each card  to 100px. (style = height:100px;)
7. Set the color of each card. (eg.: color:pink;)
8. Now, the tabs can be navigated.

## Associated Attributes
- **Style**: It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).

- **Class**: "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space seperated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
    ```cssupdated "Class" attribute's description.
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

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +



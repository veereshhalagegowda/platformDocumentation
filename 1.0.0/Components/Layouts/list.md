## Overview
A list component contains list-item components in the form of line items. 
## Usage
List component contains number of list-item components, there is no requirement to set the number of columns. It is an unordered list, and the list items will come one below the other. 
## How to use
1. Drag and drop a list-component.
2. Set the attribute such as style and class. 
3. Now various list-items component can be inserted inside the list-component.

### Example
**Display a list of three items** 
1. Drag and drop a list-component and set the attribute such as style and class.
2. Drag and drop a list-item component inside the list-component, set the attributes for list-item such as style, class, *ngFor and label.
3. *ngFor is used to iterate through the object and access the items of the objects, if folders is a object which has attribute as name(name of folder) as a string type, with three items in the folder object, set the field in ngFor as let folder of folders.
4. Label attribute displays the name as list items, provide the name as (folder .name), this will access the folders object and get the name value. If the folders object contains three values such as photos, work and document, then the list items will be photos, work and document.
5. Save and run, a list with three items will be displayed.

## Associated Attributes 
- **Style:** It accepts a string value and affects different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).
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
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 + 

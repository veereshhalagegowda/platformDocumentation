## Overview
A menu is a set of options presented to the user of a computer application to help the user find information or execute a function.

## Usage
Menu is used when the user is to be provided with the ability to select from a list of options without consuming the GUI layout.

### How to use

1. Drag and drop the “Menu” component from the “Navigation” section.
2. Set the “matMenu” attribute to a string value.
3. Drag and drop the “Menu Item” component(s) inside the “Menu” component.
4. Set the “MenuItemName” of “Menu Item” component to a string value.
5. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute.
6. Set the “[matMenuTriggerFor]” attribute to the same value as the “matMenu” of the “Menu” component.
7. Save the changes.

### Example

1. Create a page called “page”.
2. Drag and drop the “Menu” component.
3. Set the “matMenu” attribute to “menu”.
4. Drag and drop 3 “Menu Item” components inside the “Menu” component.
5. Set the “MenuItemName” attribute of the first "Menu Item" component to “item1”.
6. Set the “MenuItemName” attribute of the second "Menu Item" component to “item2”.
7. Set the “MenuItemName” attribute of the third "Menu Item" component to “item3”.
8. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute to “Menu” and “[matMenuTriggerFor]” attribute to “menu”.
9. Save the changes.
10. Now, when the “Menu” button is clicked, it will reveal the list of menu items (“item1”, “item2”, “item3”).

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

- **xPosition**: Specifies the horizontal position of the menu list. Values can be : “before” or “after”

- **yPosition**: Specifies the vertical position of the menu list.Values can be: “above” or “below”

- **templateRef**: Creates a template reference variable. Takes string as its value.

- **items**: DEPRECATED.

- **matMenu**: Takes string as its value. Value should be same as “[matMenuTriggerFor]” attribute’s value of the “Menu” component.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

## Overview
A menu is a list of options from which an option can be selected to perform a specific operation. A menu item is the individual option that can be selected. A menu item is always contained in the “Menu” component. 

## Usage
Menu items are what makes up a menu. Menu items are used to provide options within a menu.

### How to use

1. Drag and drop the “Menu” component from the “Navigation” section.
2. Set the “matMenu” attribute to a string value.
3. Drag and drop the “Menu Item” component(s) inside the “Menu” component.
4. Set the “MenuItemName” of “Menu Item” component to a string value.
5. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute.
6. Set the “[matMenuTriggerFor]” attribute to the same value as the “matMenu” of the “Menu” component.

### Example

1. Create a page called “page”.
2. Drag and drop the “Menu” component.
3. Set the “matMenu” attribute as “menu”.
4. Drag and drop 3 “Menu Item” components inside the “Menu” component.
5. Set the “MenuItemName” as “item1”, “item2” and “item3” respectively.
6. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute as “Menu” and “[matMenuTriggerFor]” attribute to “menu”.
 7. Now, when the “Menu” button is clicked, it will reveal the list of menu items (“item1”, “item2”, “item3”).

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

- **MenuItemName**: It is the name of the menu item that appears in the application. Takes string as its value.(eg.: item1)

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

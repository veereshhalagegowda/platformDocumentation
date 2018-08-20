## Overview
A menu button is always associated with a “Menu” component that contains a list of “Menu Items”. When a menu button is clicked, the associated menu will be shown.

## Usage
A menu button is used to provide an interface for the user to trigger a menu list. The menu appears where the menu button exists.

### How to use

After creating a Menu,

1. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute.
2. Set the “[matMenuTriggerFor]” attribute to the same value as the “matMenu” attribute of the “Menu” component.
3. Save the changes.

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
- **MenuName**: It is the name of the menu button that appears in the application. Takes string as its value.
(eg. Menu)

- **Color**: It takes the color based on the angular material theme. Takes "primary", "accent" or "warn" as its value.

- **[matMenuTriggerFor]**: It should have the same value as the “matMenu” attribute of the associated “Menu” component. Takes string as its value.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


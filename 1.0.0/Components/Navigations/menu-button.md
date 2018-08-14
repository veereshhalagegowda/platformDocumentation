{
  "name" : "menu-button",
  "type" : "Component",
  "category": "Navigation",
  "version" : "1.0.0" ,
  "average Rating" : 1,
  "description" : “A button that triggers the menu associated with it.",
    "guide":"",
   "platformSupportVersion " : "4.0.0",
  " publisher" : "Sankarshan"
}


## Guide
### Overview
A menu button is always associated with a “Menu” component that contains a list of “Menu Items”. When a menu button is clicked , the associated menu will be shown. Menu is hidden 

### Usage
A menu button is useful when there is a need to design an interface for users to select from a set of options without consuming the GUI layout.

### How to use

After creating a Menu,

1. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute.
2. Set the “[matMenuTriggerFor]” attribute to the same value as the “matMenu” of the “Menu” component.

### Example

1. Create a page called “page”.
2. Drag and drop the “Menu” component.
3. Set the “matMenu” attribute as “appMenu”.
4. Drag and drop 3 “Menu Item” components inside the “Menu” component.
5. Set the “MenuItemName” as “item1”, “item2” and “item3” respectively.
6. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute as “Menu” and “[matMenuTriggerFor]” attribute to “appMenu”.
7. Now, when the “Menu” button is clicked, it will reveal the list of menu items (“item1”, “item2”, “item3”).


### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given.An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.(eg. background:orange).

- **Class**: It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name.It accepts string value. (eg. class=”side-container”).

- **MenuName**: It is the name of the menu button that appears in the application. Takes string as its value.
(eg.: Menu)

- **[matMenuTriggerFor]**: It should have the same value as the “matMenu” attribute of the associated “Menu” component. Takes string as its value.

### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
	- Angular CLI version: 5.0.0 + 
	- Cordova version: 7.1.0 +


{
  "name" : "menu",
  "type" : "Component",
  "category": "Navigation",
  "version" : "1.0.0" ,
  "average Rating" : 1,
  "description" : ”menu is a container for the list of options.",
    "guide":"",
   "platformSupportVersion " : "4.0.0",
  " publisher" : "Sankarshan"
}


## Guide
### Overview
A menu is a set of options presented to the user of a computer application to help the user find information or execute a function.

### Usage
Menu is used when the user is to be provided with the ability to select from a list of options without consuming the GUI layout.

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
3. Set the “matMenu” attribute as “appMenu”.
4. Drag and drop 3 “Menu Item” components inside the “Menu” component.
5. Set the “MenuItemName” as “item1”, “item2” and “item3” respectively.
6. Drag and drop the “Menu Button” component to the desired position and set “MenuName” attribute as “Menu” and “[matMenuTriggerFor]” attribute to “appMenu”.
 7. Now, when the “Menu” button is clicked, it will reveal the list of menu items (“item1”, “item2”, “item3”).

### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given.An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.(eg. height:100%).

- **Class**: It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name.It accepts string value. (eg. class=”side-container”).

- **xPosition**: Specifies the horizontal position of the menu list. Values can be : “before” or “after”

- **yPosition**: Specifies the vertical position of the menu list.Values can be: “above” or “below”

- **templateRef**: Creates a template reference variable. Takes string as its value.

- **items**: DEPRECATED.

- **matMenu**: Takes string as its value. Value should be same as “[matMenuTriggerFor]” attribute’s value of the “Menu” component.

### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
	- Angular CLI version: 5.0.0 + 
	- Cordova version: 7.1.0 +

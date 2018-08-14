{
  "name" : "tab",
  "type" : "Component",
  "category": "Navigation",
  "version" : "1.0.0" ,
  "average Rating" : 1,
  "description" : “Tabs organize content into separate views where only one view can be visible at a time.",
    "guide":"",
   "platformSupportVersion " : "4.0.0",
  " publisher" : "Sankarshan"
}


## Guide
### Overview
Tabs are used to navigate between different views within the same context. Only one view is rendered at a time. Tabs should always be used inside a “Tab Group” component.

### Usage
Tabs are useful for containing and navigating between contextually related but distinct contents.

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

### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given.An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.(eg. background:orange).

- **Class**: It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=”side-container”).

- **label**: Name of the Tab that. Takes string as its value.

### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


{
  "name" : "tab-group",
  "type" : "Component",
  "category": "Navigation",
  "version" : "1.0.0" ,
  "average Rating" : 1,
  "description" : “Tab Group component is the container component for the Tab components.",
    "guide":"",
   "platformSupportVersion " : "4.0.0",
  " publisher" : "Sankarshan"
}


## Guide
### Overview
Tabs should always be used inside a “Tab Group” component. “Tab Group” component is a container component that is used to contain one or more “Tab” components. “Tab” components should be contained in the “Tab Group” component.

### Usage
Tabgroup component used whenever tab(s) are used. A tab can not exist outside of the tab group component.

### How to use

Drag and drop the “Tab Group” Component from the “Navigation” category.
Drag and drop the “Tab” component(s) inside the “Tab Group” component.
Set the “label” attribute of the “Tab” component(s).
Drag and drop the components needed within each “Tab” component.

### Example
Create a page.
Drag and drop the “Tab Group” Component from the “Navigation” category.
Drag and drop 3 “Tab” components inside the “Tab Group” component.
Set the values of 1st, 2nd and 3rd Tab’s “label” property as “Tab1”, “Tab2” and “Tab3” respectively.
Drag and drop a “Card” component from “Layout” category into each of the tabs.
Set height of each card  to 100px. (style = height:100px;)
Set the color of each card. (eg.: color:pink;)
Now, the tabs can be navigated.

### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.(eg. background:orange).

- **Class**: It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=”side-container”).

### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +



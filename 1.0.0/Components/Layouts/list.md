
{
  "name" : "List",
  "type" : "Component"
  "category": “Layout”
  "version" : "1.0.0",
  "averageRating" : 1,
  "description" : " list is a container component that wraps and formats a series of line items. As the base list component, it provides Material Design styling, but no behavior of its own.",
  "platformSupportVersion" : "4.0.0",
  "publisher" : "Ayush"

}



## Guide:
### Overview:
A list component contains a number of list-items components and it forms a list.Basically a list component is a container that stores list items. There will not be any layout for list component.

##### Usage:
List component contains number of list-item components, in this there is no requirement to set the number of columns, it can be anything. It is a unordered list, and the list items will come one below the other. 

##### How to use
Drag and drop a list-component, and set the attribute such as style and class. Now various list-items component can be inserted inside the list-component.

###### Example
**Display a list of three items-**

- Drag and drop a list-component and set the attribute such as style and class.
- Drag and drop a list-items component inside the list-component. And for the list-items set the attribute such as style, class, *ngFor and label.
-   *ngFor is used to iterate through the object and access the items of the objects, so if folders is a object which has attribute as name(name of folder) which is a string, and there are three items in the folder object. So set the field in ngFor as 
let folder of folders .
4 Label attribute give the name which will be displayed as a list items, so provide the name as (folder .name), this will access the folders object and get the name value from that. So if the folders object contains three values such as photos, work and document, then the list will be generated which contains the list items as photos, work and document.
- Save and run, a list will three items will be displayed.
 

### Associated Attributes:
**Style**-accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

**Class**- it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar).

### Support 
- Devices: Android, iOS
- Browsers:  Latest version of all modern browsers
- Dependencies version:
 Angular CLI version: 5.0.0 + 
 Cordova version: 7.1.0 +







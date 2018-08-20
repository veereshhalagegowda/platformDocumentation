## Overview:
Expansion panel outlet component is a container which provides the expandable view, where some of the content will be hidden and it will be displayed when the user clicks on the expandable panel component, it can contain various component such as expansion header, expansion title, and expansion description etc.


## Usage: 
Expansion panel component can be used where the data to be displayed in a expanded view, and will be shown and hidden onclick event. Only the title and description will be shown and other components will be hidden and they will displayed when the user clicks on it. 

### Example 
- Drag and drop a expansion panel outlet component, and inside that drag and drop a expansion panel component.
- Drag and drop a expansion header component inside the expansion panel.
- Drag and drop a expansion title and expansion description component inside the expansion header component.
- Click on the title and provide the title= Personal Detail and click on description component and provide the description attribute as enter your name.
- Save and run.
- A expansion panel will be displayed with the title as Personal Detail and description as enter your name. Many other component can be inserted inside it and it can be implemented more.


## Associated Attributes 
- **Style-** It accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

- **Class-** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar)

- **displayMode:** The display mode used for all expansion panels in the accordion. Currently two display modes exist:
1: default - a gutter-like spacing is placed around any expanded panel, placing the expanded panel at a different elevation from the rest of the accordion. 
2: flat - no spacing is placed around expanded panels, showing all panels at the same elevation.

- **Multi-** It accepts boolean values as true or false. And depending on the value it checks, whether the accordion should allow multiple expanded accordion items simultaneously or not.




## Support 
### Devices: Android, iOS
### Browsers:  Latest version of all modern browsers
### Dependencies version
 **Angular CLI version:** 5.0.0 + 
 **Cordova version:** 7.1.0 +












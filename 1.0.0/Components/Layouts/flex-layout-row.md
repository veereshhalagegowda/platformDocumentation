


## Overview
Flex-layout-row is used to set the positions or flow of the child components horizontally. It has following properties like style ,Class ,fxFlex ,fxLyoutWrap ,fxLayoutgap, Fxlayoutalign, fxShow ,fxHide.

**Note:** By default some of the attributes will be set to default values. Change it according to the need.

## Usage
Flex-layout-row is used to display the components in a row. Components placed inside flex-layout-row appears horizontally.

### How to use
Drag and drop the flex-layout-row component, set the required attributes. After that drag and drop any other components inside the flex-layout-row component.

### Example 
- Drag and drop a flexlayoutrow component.

- Set the component attributes value with “layout direction = start” and perpendicular “direction = start”

- Drag and drop some other components like button and textbox inside the flexlayoutrow component.

- Save it and run.

- When the page is loaded the components button and textbox appears horizontally. And the value “layout direction = start” and perpendicular “direction = start” specifies the direction in which the flex starts.

## Associated Attributes 
- **Style-** It accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

- **Class-** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar)

- **fxFlex-** This property should be used on elements within a fxLayout container and identifies the resizing of that element within the flexbox container flow such as flex-grow,flex basis, flex-shrink,flex-grow.
- **wrap**- property specifies whether the flexible items should wrap or not. It has values such as nowrap,wrap,wrap-reverse,initial,inherit.
- **fxLayoutGap-** This can be used to specify margin gaps on children within a flexbox container. It accepts integer value. Such as 20px, 5em etc.
- **Layout Direction-** This can be used to specify how the children components of this component should be aligned horizontally. It accepts string values such as center,start,end etc.
- **Perpendicular  Direction-** This can be used to specify how the children components should be aligned vertically. It accepts string values such as center,start,end etc.
- **fxShow-** this directive allows developers to dynamically show the element. It accepts boolean values such as true or false.
- **fxHide-** this directive allows developers to dynamically hide the element. It accepts boolean values such as true or false.

## Support 
### Devices: Android, iOS
### Browsers:  Latest version of all modern browsers
### Dependencies version
 **Angular CLI version:** 5.0.0 + 
 **Cordova version:** 7.1.0 +

### Overview: 
The expansion-title component is used to display the title for the expansion panel components. It can be used inside the ExpansionPanelHeader component or it can be used individually to display the title.

#### Usage
Expansion-title is used to display title for the expansion panel content. Only the title will be displayed, and the other components will be displayed after clicking the title.

#### How to use:   
- Drag and drop the expansion panel component. 
- Inside the expansion panel component, drag and drop the expansion header component. And inside expansion-header component drag and drop the expansion-title component.
- Double click the expansion-title component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
title = this is expansion panel title
```
Save it and run.
When the page is loaded the attribute value "title = this is expansion panel title" will be displayed. And when the title is clicked, the expansion-header panel will be extended.

### Associated Attributes:
- **style:** Used to specify the inline style.
- **class:** It specifies one or more classnames for an element. The class attribute is mostly used to point to a class in a style sheet.
place
- **title:** Specifies the title that is to be displayed when the page is loaded. 

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +

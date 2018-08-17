### Overview: 
The expansion-panel-header shows a summary of the panel content and acts as the control for expanding and collapsing. This header may optionally contain panel-title and panel-description. By default, the expansion-panel header includes a toggle icon at the end of the header to indicate the expansion state. This icon can be hidden via the hideToggle property.

#### Usage
Expansion-header is used to show the summary of the panel content. 

#### How to use:   
- Drag and drop the expansion panel component. 
- Inside the expansion panel component, drag and drop the expansion header component.
- Double click the expansion header component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
collapsedheight = 50
expandedheight =  50
```
Save it and run.
When the page is loaded the attribute value "collapsedheight = 50". And "expandedheight = 50" specifies the height of header when the header is collapsed and expanded.

### Associated Attributes:
- **style:** Used to specify the inline style.
- **class:** It specifies one or more classnames for an element. The class attribute is mostly used to point to a class in a style sheet.
place
- **collapsedheight:** Specifies the height of the header while the panel is collapsed. 
- **expandedheight:** Specifies the height of the header while the panel is expanded.

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +

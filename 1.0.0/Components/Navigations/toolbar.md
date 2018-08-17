### Overview
A toolbar is a container which contains headers, titles, menus or actions that perform specific functions. 

### Usage
They are designed to provide easy and immediate access to users' most frequently used functions or provide relavent information about the page or application.

### How to use
1. Drag and drop “Toolbar” component from the “Navigation” section inside a page’s container where the toolbar component should be rendered .
2. Fill in the “Content” attribute with what toolbar should contain.


### Example
1. Create a page.
2. Drag and drop the "Toolbar" component from "Navigation" section.
3. set the "Content" attribute to "I'm a toolbar".

### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given.An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.  
(eg. height:50px; background: orange).

- **Class**: it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name.It accepts string value. (eg. class=toolbar).

- **Color**: takes the color based on angular material thing.Takes "primary", "accent" and "warn" as its value.

- **Content**: This is displayed inside the toolbar. Its value can be plain text or valid html tags.  
eg: 
```This is a toolbar```
or  
html tags like,  
```html
<button mat-button>I'm a button</button>
```

### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
	- Angular CLI version: 5.0.0 + 
	- Cordova version: 7.1.0 +

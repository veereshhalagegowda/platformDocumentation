## Overview
A toolbar is a container which contains headers, titles, menus or actions that perform specific functions. 

## Usage
They are designed to provide easy and immediate access to users' most frequently used functions or provide relevant information about the page or application.

### How to use
1. Drag and drop the “Toolbar” component from the “Navigation” section into a page’s container where the toolbar component should be rendered .
2. Fill in the “Content” attribute with the value the toolbar should contain.


### Example
1. Create a page.
2. Drag and drop the "Toolbar" component from the "Navigation" section.
3. Set the "Content" attribute to "I'm a toolbar".

## Associated Attributes
- **Style**: It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).

- **Class**: Class attribute is used to point to a class in a style sheet. A class contains multiple styles. Class can be created in the "Style" (someting). It accepts string value which are the class names in the style sheet (eg. class=toolbar).

- **Color**: It takes the color based on the angular material theme. Takes "primary", "accent" or "warn" as its value.

- **Content**: This is displayed inside the toolbar. Its value can be plain text or valid html tags.  
    eg.
    ```
    This is a toolbar
    ``` 
    or  html tags like,
    ```html  
    <button mat-button>I'm a button</button>
    ```

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

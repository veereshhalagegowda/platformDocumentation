## Overview
The icon component represents an icon in the application. Icons are most effective when they improve visual interest and grab the user's attention. They help guide users while they're navigating a page.

## Usage
Icons are used when we need to improve visual interest and grab the user's attention. They help guide users while they're navigating a page.

### How to use   
1. Drag and drop the component.
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example 
1. Input the component field(s) with the attribute value(s):
    ``` 
    iconname = home
    class = icon
    ```
2. Save it and run.
3. When the page is loaded the value "iconname = home" will be the name of the icon that will be displayed on the button and "class = icon" is the name of the class that can be used to point to a class in a style sheet.

## Associated Attributes
- **Style:** It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).
- **Class:** "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space separated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
    ```css
    .class1 {
        border-radius:10px;
        flex-basis:10%;
        height:100px;
    }
    .class2 {
        border-radius:10px;
        flex-basis:10%;
        height:100px;
    }
- **Iconname:** Specifies a name for the icon. Image path should be given or the image should be placed inside the assets folder.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

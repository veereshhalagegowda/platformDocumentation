## Overview
Form component are the container which contains several components such as input, radio button, checkbox, buttons etc. Users interacts with all this component and can change the value according to that.
## Usage
A form component can be used whenever there is a requirement for data-entry task. It is basically a block in which other component can be inserted such as a paragraph, a button, a input text etc.
### How to use
1. Drag and drop a form component.
2. Set the style and class attribute.
3. Drag and drop other components inside this such as input, buttons etc.

### Example
**Display a login page** 
1. Display a block as a login page .
2. Drag and drop a form component.
3. Drag and drop a paragraph component inside and set the text as Username.
4. Drag and drop a input component.
5. Drag and drop a paragraph, below the input and set the text as password.
6. Drag and drop a input for password.
7. Drag and drop a button component below input and name the button as Submit and set the onClick attribute.
8. Save and Run the studio.
9. A login page is created in which a user can give his username and password and he can  submit.

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
    ```
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 + 

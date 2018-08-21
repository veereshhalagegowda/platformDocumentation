## Overview
The select component is used along with one or more option elements, creates a drop-down list of options for a web form. The select element creates the list and each option element is displayed as an available option in the list.

## Usage
Select component is used to select the list of options available within the select field. When clicked it displays the list in the drop-down view, where the user can select the option.

### How to use   
1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example 
1. Input the component field with the attribute value:
    ``` 
    placeholder = select
    class = select
    ```
2. Save it and run.
3. When the page is loaded the value "placeholder = select" will display the value “Select”. And "class = select" is the class name that can be used to point in a style sheet.

## Associated Attributes
- **Style**: It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).

- **Class**: "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space separated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
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
    
- **Value:** it specifies the pre-defined text that is displayed in the select area. when the select field is clicked, it displays the value that is entered in the field when the application is run. Example “Select” defined in this field will display Select in the select field when the application is run.
- **Placeholder:** used to hold the defined text value. Example “Select” holds the value Select for the field when the application is run.
- **Required:** specifies that the field is required and should not hold empty values. 
- **Ngmodel:** used for two-way data binding. The ng-model attribute is used to bind the data in your model to the view presented to the user.
- **Multiple:** This property allows the user to select multiple options. The value given should be a boolean value i.e. either true or false. 
- **Onopen:** Event emitted when the select panel has been toggled
- **Change:** Event emitted when the selected value has been changed by the user.
- **Optiondata:** Display the options which are entered when the user clicks on the select option.
- **Ngfor:** Used for iterating.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


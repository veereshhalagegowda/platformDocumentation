## Overview 
The Datepicker component is used to present an interface which makes it easy for users to select the date. Tapping on the component will display a picker interface that can be used to select a date.

## Usage
Datepicker component is used to select the date easily instead of entering it manually. 

### How to use   
1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example 
1. Input the component field with the attribute value:
``` 
opened = true
placeholder = datepicker 
```
2. Save it and run.
3. When the page is loaded the "opened = true" is the event that will be emitted when the datepicker is opened. And "placeholder = datepicker" is text that will be displayed in the datepicker field when the page is loaded. 

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
    
- **placeholder:** Used to hold the defined text value. Example “Calendar” holds the value Calendar for the field.
- **value:** Specifies the new value for the target datepicker input. Value has to be either null or the letter “D”.
- **Min:** Specifies the minimum valid date. The value should be either null or the letter “D” 
- **max:** Specifies the maximum valid date. The value should be either null or the letter “D”
- **Startat:** Specifies the date to open the calendar to initially. It should be in the format D | null
- **Startview:** Specifies the view that the calendar should start in. It should be in the format 'month' | 'year'
- **Touchui:** Specifies whether the calendar UI is in touch mode. In touch mode, the calendar opens in a dialog rather than a popup and elements have more padding to allow for bigger touch targets. The value should be a boolean i.e. either true or false.
- **Id:** Specifies the id for the datepicker calendar. The value should be string.
- **Selectedchanged:** Is an event that is emitted when the selected date is changed. The value should be a boolean i.e. either true or false.
- **Opened:** Specifies whether the calendar is open or not. The value should be a boolean i.e. either true or false.
- **Disabled:** Specifies whether the datepicker pop-up should be disabled or not. The value should be a boolean i.e. either true or false.
- **Open:** Is an event called when the calendar is open (Has been deprecated).
- **Close:** Is an event called when the calendar is closed (Has been deprecated).
- **Matdatepickerfilter:** It is a function that can be used to filter out dates within the datepicker. The value should be given in this format. (date: D | null) => boolean(true or false)
- **Ngmodel:** used for two-way data binding. The ng-model attribute is used to bind the data in your model to the view presented to the user.
- **Name:** Specifies the name for the date picker.
- **Picker:** It is an id for the date picker.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

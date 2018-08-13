{
"name" : "date-picker",
"type" : "Component"
"category": “Form Controls”
"version" : "1.0.0",
"averageRating" : 1,
"description" : "The datepicker allows users to enter a date either through text input, or by choosing a date from the calendar.",
"guide" : "",
"platformSupportVersion" : "4.0.0",
"publisher" : "Prashanth",
}

## Guide: 
### Overview: 
The Datepicker component is used to present an interface which makes it easy for users to select date. Tapping on the component will display a picker interface that can be used to select date.

#### Usage
Datepicker component is used to select the date easily instead of entering it manually. 

#### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
opened = true
placeholder = datepicker 
```
Save it and run.
When the page is loaded the "opened = true" is the event that will be emitted when the datepicker is opened. And "placeholder = datepicker" is text that will be displayed in the datepicker field when the page is loaded. 

### Associated Attributes:
- **style:** Used to specify the inline style.
- **class:** Specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
- **placeholder:** Used to hold the defined text value. Example “Calendar” holds the value Calendar for the field.
- **value:** Specifies the new value for the target datepicker input. Value has to be either null or the letter “D”.
- **Min:** Specifies the the minimum valid date. The value should be either null or the letter “D” 
- **max:** Specifies the the maximum valid date. The value should be either null or the letter “D”
- **Startat:** Specifies the date to open the calendar to initially. It should be in the format D | null
- **Startview:** Specifies the view that the calendar should start in. It should be in the format 'month' | 'year'
- **Touchui:** Specifies whether the calendar UI is in touch mode. In touch mode the calendar opens in a dialog rather than a popup and elements have more padding to allow for bigger touch targets. Value should be a boolean i.e. either true or false.
- **Id:** Specifies the id for the datepicker calendar. Value should be string.
- **Selectedchanged:** Is an event that is emitted when the selected date is changed. The value should be a boolean i.e. either true or false.
- **Opened:** Specifies whether the calendar is open or not. The value should be a boolean i.e. either true or false.
- **Disabled:** Specifies whether the datepicker pop-up should be disabled or not. The value should be a boolean i.e. either true or false.
- **Open:** Is an event called when the calendar is open (Has been deprecated).
- **Close:** Is an event called when the calendar is closed (Has been deprecated).
- **Matdatepickerfilter:** It is a function that can be used to filter out dates within the datepicker. Value should be given in this format. (date: D | null) => boolean(true or false)
- **Ngmodel:** used for two way data binding. The ng-model attribute is used to bind the data in your model to the view presented to the user.
- **Name:** Specifies the name for the date picker.
- **Picker:** It is an id for the date picker.

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +

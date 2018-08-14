{
"name" : "select",
"type" : "Component"
"category": “Form Controls”
"version" : "1.0.0",
"averageRating" : 1,
"description" : "Is a form control for selecting a value from a set of options",
"platformSupportVersion" : "4.0.0",
"publisher" : "Prashanth",
}

## Guide: 
### Overview: 
The select component is used along with one or more option elements, creates a drop-down list of options for a web form. The select element creates the list and each option element is displayed as an available option in the list.

#### Usage
Select component is used to select the list of options available within the select field. When clicked it displays the list in drop-down view, where the user can select the option.

#### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
placeholder = select
required = true
```
Save it and run.
When the page is loaded the value "placeholder = select" will display the value “ Select”. And the required field attribute specifies that it is compulsory to select the option from the component.

### Associated Attributes:
- **style:** Used to specify the inline style.
- **class:** it specifies one or more classnames for an element. The class attribute is mostly used to point to a class in a style sheet.
- **Value:** it specifies the pre-defined text that is displayed in the select area. when the select field is clicked, it displays the value that is entered in the field when the application is run. Example “Select” defined in this field will display Select in the select field when the application is run.
- **Placeholder:** used to hold the defined text value. Example “Select” holds the value Select for the field, when the application is run.
- **Required:** specifies that the field is required and should not hold empty values. Input given should be either true or false.
- **Ngmodel:** used for two way data binding. The ng-model attribute is used to bind the data in your model to the view presented to the user.
- **Multiple:** This property allows the user to select multiple options. The value given should be a boolean value i.e. either true or false. 
- **Onopen:** Event emitted when the select panel has been toggled
- **Change:** Event emitted when the selected value has been changed by the user.
- **Optiondata:** Display the options which are entered when the user clicks on the select option.
- **Ngfor:** Used for iterating.

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +


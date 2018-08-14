{
"name" : "text-area",
"type" : "Component"
"category": “Form Controls”
"version" : "1.0.0",
"averageRating" : 1,
"description" : "Input-text is a component that allows native <input> and <textarea> elements to work with text, numbers and special characters.",
"guide" : "”,
"platformSupportVersion" : "4.0.0",
"publisher" : "Prashanth",
}
## Guide: 
### Overview: 
Text area component is a form control field to input user data such as numbers, alphabets, special characters, password, email, search etc. Input can be used within the forms to capture the data from the user. 

#### Usage
Text-area component specifies an input field where the user can enter data. <input> elements are used within a <form> element to declare input controls that allow users to input data. An input field can vary in many ways, depending on the type attribute.

#### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
value = input text here
required = true 
```
Save it and run.
When the page is loaded the "value = input text here" will be the text that will be displayed. And the "required = true" specifies that the user has to compulsorily input the text. 

### Associated Attributes:
- **style:** Used to specify the inline style. It is applied to the specific element.
- **class:** It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
- **Value:** It specifies the pre-defined text that is displayed in the text area when the application is run. Example “hello” defined in this field will display hello in the text field when the application is run.
- **Placeholder:** used to hold the defined text value. Example “Name” holds the value Name for the text field.
- **Required:** specifies that the text field should be filled and should not hold empty values. Value should be boolean i.e. either true or false.
- **Color:** takes the color based on angular material thing.
- **Name:** specifies the name for the text field.
- **Ngmodel:** used for two way data binding. The ng-model attribute is used to bind the data in your model to the view presented to the user. The ng-model attribute is used for, Binding controls such as input, text area and selects in the view into the model.

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +

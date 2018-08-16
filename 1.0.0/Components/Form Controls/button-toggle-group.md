{
  "name" : "button-toggle-group",
  "type" : "Component",
  "category": “Form Controls",
  "version" : "1.0.0" ,
  "average Rating" : 1,
  "description" : “button toggle group contains buttons among which only one button can be selected at a time.”,
    "guide":"",
   "platformSupportVersion " : "4.0.0",
  " publisher" : "Sankarshan"
}


## Guide
### Overview
Button toggle group contains many buttons whose behaviour is similar to radio buttons. Only one of the buttons can be selected at a time.

### Usage
Selecting any one of the unselected buttons in a button group will unselect the previuosly selected button and selects the currently selected button.


### How to use

1. Drag and drop the “Button Toggle Group” component from “Forms Control” Category where it is needed in that page.
2. Double click on the component and give values to the attributes.

### Example

1. Create a page called “page”.
2. Drag and drop the “Button Toggle Group” component.
3. Double click on that component.
4. In “Ts” file, create a property called “buttons” and set its value as below.
    ```typescript
    buttons = [{"value":"Bold"}, {"value":"italic"}, {"value":"strike"}];
    ```
5. Set the value of [toggleOptions] to “buttons”.
6. Write a function in Ts file as below:
```typescript
  onValueChange(){
       console.log("val changed")
   }
```

6. Set the (valueChanged) attribute to “onValueChange()”.
7. Set [disableIndex] to “0”.
7. Save the changes.
8. Open the address where the app is running, and try selecting a button from the button group.
9. Console will output “val changed”. 


### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.
- **Class**: It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=”btgroup”).
- **[toggleOptions]**: Takes the name of an array of objects of type {“value”: “buttonValue”}.
    ```typescript
    Eg.     buttons = [{"value":"Bold"}, {"value":"italic"}, {"value":"strike"}];
    ```

- **[align]**: Sets the alignment of the buttons in button group. Takes 'vertical' or 'Horizontal' as its value.(with single quotes)
- **[disableIndex]**: Index of the button that should be disabled by default. Takes number as its value
- **[checkIndex]**:  Index of the button that should be seleted by default. takes number as its value.
- **(valueChange)**: Takes function( that is defined in Ts file) name as argument which will be called whenever the value of button group changes. Eg: onValChange().
- **(indexChange)**:  Takes function( that is defined in Ts file) name as argument which will be called whenever different button gets selected in button group. Eg: onIndexChange().

### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +



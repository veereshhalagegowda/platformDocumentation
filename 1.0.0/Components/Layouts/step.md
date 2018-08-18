## Overview:
Step component can contain anything, such as a textbox,buttons,radio buttons,checkbox, images etc. So the step component can only be used inside a stepper component.A page can be just divided into steps using stepper and step.  

## Usage:
Step component can be used to create a page that is divided into various steps, it can be displayed as horizontally or vertically. 


### How to use:
Drag and drop a stepper component and fill the required properties.

### Example:
**Create a stepper with login process.**
- Drag and drop a stepper component. In matHorizontalStepper set the same value to make it horizontal.Suppose there are three steps component, labeled as getUsername, getPassword, and submit.
- Drag and drop three step components inside stepper component, and give the label as getUsername,getPassword and submit.

- Click at the stepper component and set the attribute such as type=horizontal, selected=getUsername  and set the index as 0 so that the getUsername step will come at first.
- Now in getUsername step drag and drop a input text to accept username from the user, now drag and drop a input component inside getPassword step to accept password, and in submit step drag and drop a button and name that button as Login.
- So by providing all this information save and run.
- A stepper will be displayed with getUsername,getPassword and submit label will be displayed. 


  

## Associated Attributes:
- **Style-** It accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

- **Class-** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar).


- **Label-** Label is the name given to the step and each step will have  different labels. It accepts text values.



- **completed-** This accepts boolean values as true or false depending on whether step is marked as completed.

- **editable:** This attribute accepts boolean value as true or false to make it whether the user can return to this step once it has been marked as completed.

- **interacted-** This attribute is used to check whether user has seen the expanded step content or not. it accepts boolean values and by default the value will  be false.

- **optional-** This attribute accepts boolean values as true or false, to make it whether the given step is optional.


- **[stepControl]-**




## Support 
### Devices:Android, iOS
### Browsers:  Latest version of all modern browsers
 ### Dependencies version: 
 **Angular CLI version:** 5.0.0 + 
 **Cordova version:** 7.1.0 +











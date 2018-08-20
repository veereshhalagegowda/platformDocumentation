## Overview 
Stepper component is used to divide the content into steps. So a page can be divided into parts instead of getting the information at the same page, get the information at the different steps.
A task can be divided into certain steps  or parts and each of them will have some actions.

## Usage
So if there is a requirement of creating a login page where username and password should be given and after that submit button, so this can be divided into three steps such as at the first step get the username, then second step get the password, and at the last step submit option should be there. This is where the stepper component can be used.




### How to use
Drag and drop a stepper component and fill the required properties.

### Example:
**Create a stepper with login process.** 
- Drag and drop a stepper component. In matHorizontalStepper set the same value to make it horizontal.Suppose there are three steps component, labeled as getUsername, getPassword, and submit.
- Drag and drop three step components inside stepper component, and give the label as getUsername,getPassword and submit.

- Click at the stepper component and set the attribute such as type=horizontal, selected=getUsername  and set the index as 0 so that the getUsername step will come at first.
- Now in getUsername step drag and drop a input text to accept username from the user, now drag and drop a input component inside getPassword step to accept password, and in submit step drag and drop a button and name that button as Login.
- So by providing all this information save and run.
- A stepper will be displayed with getUsername,getPassword and submit label will be displayed. 



  

## Associated Attributes 
- **Style:** It accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

- **Class:** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar).


- **linear:** The linear attribute can be set on mathorizontalstepper and mat vertical stepper to create a linear stepper that requires the user to complete previous steps before proceeding to following steps. It accepts boolean value as true or false.

- **type:** This accepts one of the two values either horizontal or vertical. If the stepper is horizontal then give the type as horizontal and vice versa. 


- **matHorizontalStepper:** mat-horizontal-stepper attribute can be used to create a horizontal stepper, means the step will be displayed in horizontal direction. So if the steps should be displayed in a row then just provide the value as mat horizontal stepper.                   

- **matVerticalStepper:** mathorizontalstepper selector can be used to create a horizontal stepper, the steps will be displayed in vertical direction. So if the steps should be displayed in a row then just provide the value  as mat Vertical stepper. 

- **selected:** The step that is selected, give the step label that should be selected by default at the first step. It will contain the  label of one of the stepper.

- **selectedIndex:** It accepts a number ,in this attribute the step that should be selected at first give the index of that step. So the index starts at 0, so whichever step should be selected at first, provide the index of that (index=position-1). 

- **selectionChange-** This is a eventEmitter that will be emitted when the selected step has changed from previous to next.




## Support 
### Devices: Android, iOS
### Browsers:  Latest version of all modern browsers
### Dependencies version
 **Angular CLI version:** 5.0.0 + 
 **Cordova version:** 7.1.0 +










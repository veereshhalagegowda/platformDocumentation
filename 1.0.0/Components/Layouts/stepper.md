## Overview
Stepper component is used to divide the content into steps. So a page can be divided into parts instead of getting the information at the same page, get the information at the different steps. A task can be divided into certain steps or parts and each of them will have some actions.
## Usage
So if there is a requirement of creating a login page where username and password should be given and after that submit button, so this can be divided into three steps such as at the first step get the username, then second step get the password, and at the last step submit option should be there. This is where the stepper component can be used.
### How to use
1. Drag and drop a stepper component.
2. Fill the required properties.

### Example
**Create a stepper with login process** 
1. Drag and drop a stepper component. In matHorizontalStepper set the same value to make it horizontal.Suppose there are three steps component, labeled as getUsername, getPassword, and submit.
2. Drag and drop three step components inside stepper component, and give the label as getUsername,getPassword and submit.
3. Click at the stepper component and set the attribute such as type=horizontal, selected=getUsername  and set the index as 0 so that the getUsername step will come at first.
4. Now in getUsername step drag and drop a input text to accept username from the user, now drag and drop a input component inside getPassword step to accept password, and in submit step drag and drop a button and name that button as Login.
5. So by providing all this information save and run.
6. A stepper will be displayed with getUsername,getPassword and submit label will be displayed. 

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
- **linear:** The linear attribute can be set on mathorizontalstepper and mat vertical stepper to create a linear stepper that requires the user to complete previous steps before proceeding to following steps. It accepts boolean value as true or false.
- **type:** This accepts one of the two values either horizontal or vertical. If the stepper is horizontal then give the type as horizontal and vice versa. 
- **matHorizontalStepper:** mat-horizontal-stepper attribute can be used to create a horizontal stepper, means the step will be displayed in horizontal direction. So if the steps should be displayed in a row then just provide the value as mat horizontal stepper.              - **matVerticalStepper:** mathorizontalstepper selector can be used to create a horizontal stepper, the steps will be displayed in vertical direction. So if the steps should be displayed in a row then just provide the value  as mat Vertical stepper. 
- **selected:** The step that is selected, give the step label that should be selected by default at the first step. It will contain the  label of one of the stepper.
- **selectedIndex:** It accepts a number ,in this attribute the step that should be selected at first give the index of that step. So the index starts at 0, so whichever step should be selected at first, provide the index of that (index=position-1). 
- **selectionChange:** This is a eventEmitter that will be emitted when the selected step has changed from previous to next.
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 + 

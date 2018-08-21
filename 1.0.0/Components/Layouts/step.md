## Overview 
Step component can contain anything, such as a textbox,buttons,radio buttons,checkbox, images etc. So the step component can only be used inside a stepper component.A page can be just divided into steps using stepper and step.  
## Usage 
Step component can be used to create a page that is divided into various steps, it can be displayed as horizontally or vertically. 
### How to use 
1. Drag and drop a stepper component.
2. fill the required properties.
### Example:
**Create a stepper with login process.** 
1. Drag and drop a stepper component. In matHorizontalStepper set the same value to make it horizontal.Suppose there are three steps component, labeled as getUsername, getPassword, and submit.
2. Drag and drop three step components inside stepper component, and give the label as getUsername,getPassword and submit.
3. Click at the stepper component and set the attribute such as type=horizontal, selected=getUsername  and set the index as 0 so that the getUsername step will come at first.
4. Now in getUsername step drag and drop a input text to accept username from the user, now drag and drop a input component inside getPassword step to accept password, and in submit step drag and drop a button and name that button as Login.
5. So by providing all this information save and run.
6. A stepper will be displayed with getUsername, getPassword and submit label will be displayed. 
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
- **Label:** Label is the name given to the step and each step will have  different labels. It accepts text values.
- **completed:** This accepts boolean values as true or false depending on whether step is marked as completed.
- **editable:** This attribute accepts boolean value as true or false to make it whether the user can return to this step once it has been marked as completed.
- **interacted:** This attribute is used to check whether user has seen the expanded step content or not. it accepts boolean values and by default the value will  be false.
- **optional:** This attribute accepts boolean values as true or false, to make it whether the given step is optional.
- **stepControl:**
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
- Angular CLI version: 5.0.0 + 
- Cordova version: 7.1.0 + 

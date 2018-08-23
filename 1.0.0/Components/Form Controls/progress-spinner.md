## Overview
Progress spinner component is a circular indicator of progress and activity.

## Usage
A progress spinner is a graphical element which is used to show the loading of a process or an activity. The progress spinner keeps spinning until the specified activity is completed.

### How to use   
1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Fill the attributes which are needed and save the page.

### Example 
1. Input the component field(s) with the attribute value(s):  
    `strokewidth = 100`  
    `mode = determinate`
2. Save it and run.
3. When the page is loaded the "strokewidth = 100" will be the size of the progress spinner component that will be displayed and "mode = determinate" is the mode in which the progress spinner is displayed.

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
- **Mode:** Specifies the mode of the progress circle. The value should be either determinate or indeterminate.
- **Strokewidth:** Specifies the stroke width of the progress spinner. The value should be a number.
- **Value:** Specifies the value of the progress circle. The value should be a number.
- **Color:** Takes the color based on the angular material theme.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


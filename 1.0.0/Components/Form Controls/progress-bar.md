## Overview: 
Horizontal progress-bar is used for indicating progress and activity. It is used to indicate the progress of the work that has been completed. 

## Usage
Progress bar is a graphical control element used to visualize the progression of an extended computer operation, such as a download, file transfer, or installation.

### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

### Example: 
Input the component field with the attribute value:
``` 
value = 55
mode = determinate
```
Save it and run.
When the page is loaded the "value = 55" will be the percentage of work completed that will be displayed in the progress bar. And "mode = determinate" is the mode in which the progress bar is displayed(by default the mode will be determinate).

## Associated Attributes:
- **style:** Used to specify the inline style.
- **class:** Specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
- **Mode:** Is used to select the mode. Input must be one of these values: determinate, indeterminate, buffer, query, defaults to 'determinate'. 
- **Color:** Takes the color based on angular material thing.
- **Value:** Value of the progress bar. Defaults to zero. Input value should be a number.
- **Buffervalue:** Specifies buffer value of the progress bar. Defaults to zero. Input value should be a number.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


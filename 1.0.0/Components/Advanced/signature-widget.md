## Overview
Signature Widget component creates a canvas for handwritten signatures where it is dropped. It contains options to “save” a signature, “undo” a stroke, “reset” the canvas and “cancel” the operation. 

## Usage
Signature Widget Component is used when there is a need for handwritten signature. It also removes the need to scan and upload the signature.

### How to use

1. Drag and drop the “Signature Widget” component from the “Advanced” Category where it is needed in that page.
2. Double click on the component and give values to the attributes.
3. Save the changes.

## Example

1. Create a page called “page”.
2. Drag and drop the “Signature Widget” component.
3. Double click on that component.
4. In “Ts” file, create a property called “color” and set its value to ‘rgb(0,0,0)’.
    ```typescript
    color = 'rgb(0,0,0)'
    ```
5. Set the value of [backgroundColor] to “color”.
6. Set the [dotSize] attribute to '3' and [penColor] to ‘rgb(255,255,255)’.
7. Set the value of [mode] to 'click-fullscreen' (with single quotes). Save the changes.
8. Go to the address where the app is running. Click the pencil icon to display the canvas.
9. The canvas is now black and anything written on it is white.
10. Draw something. Click on save icon.(or 'X' icon to cancel and exit the canvas).
11. After the signature is saved, if there is a need to edit it, click on the 'pencil' icon.


## Associated Attributes
- **Style:** It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).

- **Class:** "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space seperated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
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
- **[(imageData)]:** It takes a property name that is defined in Ts file which stores the signature image data.
- **[mode]:** Mode of the canvas. Takes ‘responsive’ and ‘click-fullscreen’ as its value (with single quotes).
- **[dotSize]:** Radius of a single dot. Takes number as its value.
- **[minWidth]:** Minimum width of a line.
- **[maxWidth]:** Maximum width of a line.
- **[throttle]:**  The max rate (per millisecond) at which the next point is drawn.
- **[minDistance]:** Add the next point only if the previous one is farther than x pixels.
- **[backgroundColor]:** Color of the canvas. Color format accepted is ‘rgb(255,255,255)’ (with single quotes).
- **[penColor]:** Color used to draw the lines. Color format accepted is ‘rgb(255,255,255)’ (with single quotes).
- **[velocityFilterWeight]:** Weight used to modify new velocity based on the previous velocity.
- **[onBegin]:** Function that should be executed when stroke begins. It takes function name as its value.
- **[onEnd]:** Function that should be executed when stroke ends. It takes function name as its value.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


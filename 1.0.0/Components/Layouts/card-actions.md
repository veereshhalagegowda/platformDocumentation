## Overview
A card actions is a component that is a container of buttons. And after clicking the button some actions should be performed.
## Usage
Card actions can be used as a container that contains buttons.
### How to use
Drag and drop a card actions component, provide the style and class attributes. A button component can be placed inside card actions.
### Example
**Display a card with a paragraph and card actions that has two button like and subscribe** 
- Drag and drop a card.
- Drag and drop a paragraph component inside the card.
- Drag and drop a card actions inside the card below the paragraph.
- Drag and drop two button components and set the name of the buttons as like and subscribe and provide the onclick attribute as actions.
- Save and Run.
- A card will be displayed with the paragraph and two buttons like and subscribe.
## Associated Attributes
- **Style:** It accepts a string value and affects different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).
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
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
- Angular CLI version: 5.0.0 + 
- Cordova version: 7.1.0 + 

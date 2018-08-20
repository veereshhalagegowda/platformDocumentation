## Overview
A card footer is a sub-container of card. In this we can give the information which will be displayed as a footer in the card.
## Usage
Card footer can be used where the data should be displayed as footer, at the bottom of any container. It can contain data such as string value ,logo or anything  inside it. 
### How to use     
Drag and drop a card footer component where it can be used, basically it is used at the bottom that is below every components.
### Example
**Display a card with a title, a image, a paragraph about that image and a card footer** 
- Drag and drop a card component and provide the style and class for that. 
- Drag and drop a card title inside the card and give the title=Taj Mahal.
- Drag and drop a paragraph inside the card component below the card-title and provide the path of the image in imgSrc attribute that is stored in the system so if the image is in asset folder then the path can be (asset\android\taj.jpg) and,the image taj.jpg will be displayed on the screen. 
- Now,drag and drop a paragraph component inside card below the card-image and in text attribute provide some information about the image.
- Now drag and drop a card footer inside the card below all components and drag a paragraph component inside the footer component and provide some text that can be displayed as a footer on the screen.  
- Drag and drop a card component and provide the style and class for that.
- Drag and drop a card title inside the card and give the title=Tajmahal.
- Drag and drop a paragraph inside the card component below the card-title and provide the path of the image in imgSrc attribute that is stored in the system so if the image is in asset folder then the path can be (asset\android\taj.jpg) and,the image taj.jpg will be displayed on the screen.
- Now,drag and drop a paragraph component inside card below the card-image and in text attribute provide some information about the image.
- Now drag and drop a card footer inside the card below all components and drag a paragraph component inside the footer component and provide some text that can be displayed as a footer on the screen.
## Associated Attributes
- **Style**: It accepts a string value and affects the different properties (height, width, color etc.) of the component based on the values provided (eg. background:orange;height:200px;).

- **Class**: "Class" attribute is used to point to a class in a style sheet. A class contains one or more style statements. Classes are created inside the "Style" tab which is opened by selecting the "Style" side menu. The "Class" attribute accepts space seperated class names (eg. class1 class2) which are defined in the "Style" tab as shown below.
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
- **Class:** It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value,  (eg. class=toolbar).
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:**
- Angular CLI version: 5.0.0 + 
- Cordova version: 7.1.0 + 












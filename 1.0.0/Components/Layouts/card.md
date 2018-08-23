## Overview
Cards component are surfaces that display content and actions on a single topic. They should be easy to scan for relevant and actionable information. Cards support a wide variety of content including images, text, actions and more. 
## Usage
It can be used as a container for the multiple components like card-title, card-subtitle, card-image card-action, card-header and card-footer etc, that will be put inside a card and can be displayed as a single item. Basically card component groups together all these components and displays that as a single block.
### How to use
1. Drag and drop a card-component.
2. Now the components like card-header, card-title, card-subtitle, card-image, and card-actions can be put inside the card.

### Example
**Display a Card with a title, image and a paragraph**
1. Drag and drop a card, a empty card will be displayed.
2. Drag and drop a card-title component inside card and set the title = Blog.
3. Now drag and drop a card-image component inside the card below the card-title and in imgSrc field set the path of the image which is stored in assets folder, so the path can be assets:\android\wallpaper.jpg. So the wallpaper image will be loaded.
4. To give some information (block of text) about the image drag and drop a paragraph tag inside the container below the card-image, and provide a information in the text attribute.
5. Save and Run the code.
6. A card with a title as Blog, a wallpaper image, and some block of text will be displayed on the screen.

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
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
- Angular CLI version: 5.0.0 + 
- Cordova version: 7.1.0 +

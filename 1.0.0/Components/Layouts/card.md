## Overview
Cards component are surfaces that display content and actions on a single topic.They should be easy to scan for relevant and actionable information.Cards support a wide variety of content including images, text, actions and more. 
## Usage
It can be used as a container for the multiple components like card-title,card-subtitle,card-image card-action,card-header and card-footer etc,that will be put inside a card and can be displayed as a single item. Basically card component groups together all these components and displays that as a single block.                                                                                                                                       

### How to use
Drag and drop a card and now the component like card-header, card-title, card-subtitle, card-image, and card-actions can be put inside the card.


### Example
**Display a Card with a title,image and a paragraph-** 

- Drag and drop a card,a empty card will be displayed.

- Drag and drop a card-title component inside card and set the title = Blog.

- Now drag and drop a card-image component inside the card below the card-title and in imgSrc field set the path of the image which is stored in assets folder, so the path can be assets:\android\wallpaper.jpg .So the wallpaper image will be loaded.
 
- To give some information (block of text) about the image drag and drop a paragraph tag inside the container below the card-image, and provide a information in the text attribute.

- Run the code, a card with a title as Blog, a wallpaper image, and some block of text will be displayed on the screen.

 
## Associated Attributes
- **Style-** it accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element .An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

- **Class-** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar)

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 + 






## Overview
Image component is used to insert an image into a page.

## Usage
The image in used to display an image in a page. The image has two required attributes: src and alt. 

**Note:** Images are not technically inserted into the page, images are linked to HTML pages. The image  component creates a holding space for the referenced image.

### How to use   
1. Drag and drop the component. 
2. Double click the component to display the list of attributes that can be used with it.
3. Place the images inside the assets editor and save the image inside one of the folders available inside assets editor, and give the path in imgsrc attribute.
4. Fill the attributes which are needed and save the page.

### Example 
Input the component field with the attribute value:
``` 
imgsrc = /home/prashanth/Documents/neutrinos.png
Alt  = Neutrinos
```
Save it and run.
When the page is loaded "imgsrc = /home/prashanth/Documents/neutrinos.png" will display the image that is specified in the path. And the "alt = Neutrinos" will display the text Neutrinos if the image cannot be loaded or not found.

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
    
- **Imgsrc:** The src attribute specifies the URL(web address) of the image. Images should be saved inside assets editor and placed within the folders Android or Materiallcons or Web or iOS folders and the appropriate path should be given.
- **Alt:** THe alt attribute provides an alternate text for an image, if the user cannot view it.

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


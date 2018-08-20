## Overview
The sidenav components are designed to add side content to a fullscreen app. Sidenav typically contains the links for different pages in the app or links for different sections in that page. Sidenav is a fixed layout whose slide-in and slide-out activity can be bound to an action (ex. Button press, checkbox etc.). 
Sidenav component has meaning only when it is placed inside the “Sidenav Container” component.

## Usage
Sidenav is useful when the user needs to have immediate access to the most used pages/components of an app.

### How to use

1. Drag the “Sidenav” component from the “Navigation” section and drop it inside the “Sidenav Container” component.
2. Populate the “Sidenav” component with the content that is required in the sidenav of that page.
3. Save the changes.

### Example

1. Create a page called “page”.
2. Drag and drop the “Sidenav Container”.
3. Drag and drop the “Sidenav” component inside the “Sidenav Container”.
4. Drag and drop a HTML component.
5. Write an anchor tag inside that HTML component with “href” attribute set to “http://www.neutrinos.co”  and “target” attribute to “blank”.
	```html
	<a href="http://www.neutrinos.co">neutrinos</a>
	```
6. Save the changes.
7. Now, pressing the button will open the neutrinos website.

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
- **mode**: Sidenav can render in one of three different ways based on the “mode” property.
	* over - Sidenav floats over the primary content, which is covered by a backdrop
	* push - Sidenav pushes the primary content out of its way, also covering it with a backdrop
	* side - Sidenav appears side-by-side with the main content, shrinking the main content's width to make space for the sidenav.
- **opened**: It decides whether the sidenav is opened. It can be “true” or “false”.
- **position**: Position can be either "start" or "end" which places the side content on the left or right side. Default is "start".

- **fxLayout**: Specifies the flex-direction and whether the contents should be wrapped or not.  
Eg.: fxLayout=”column wrap”

- **(opened)**: Takes function as the value which is executed when the sidenav is opened.

- **(closed)**: Takes function as the value which is executed when the sidenav is closed.

- **(toggle)**: Takes function as the value which is executed when the sidenav is toggled.




## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +



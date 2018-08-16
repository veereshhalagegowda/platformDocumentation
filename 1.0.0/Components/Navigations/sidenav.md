### Overview
The sidenav components are designed to add side content to a fullscreen app. Sidenav typically contains the links for different pages in the app or links for different section in that page. Sidenav is a fixed layout whose slide-in and slide-out activity can be bound to an action (ex. Button press, checkbox etc..). 
Sidenav component has meaning only when it is placed inside the “Sidenav Container” component.
Everything that is not contained within the “Sidenav “ component will appear as main content that is outside the sidenav bar.

### Usage
Sidenav is useful when the user needs to have immidiate access to the most used pages/components of an app.

### How to use

1. Drag and drop the “Sidenav” component from the “Navigation” section inside the “Sidenav Container” component.
2. Populate the “Sidenav” component with the content that is required in the sidenav of that page.

### Example

1. Create a page called “page”.
2. Drag and drop the “Sidenav Container”.
3. Drag and drop the “Sidenav” component inside the “Sidenav Container”.
4. Drag and drop a HTML component.
5. Write an anchor tag inside that HTML component with “href” attribute set to “http://www.neutrinos.co”  and “target” attribute to “blank”.
6. Now, pressing the button will open the neutrinos website.

### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given.An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.(eg. color:blue).
- **Class**: It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name.It accepts string value.   (eg. class=sidenav).

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




### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
	- Angular CLI version: 5.0.0 + 
	- Cordova version: 7.1.0 +



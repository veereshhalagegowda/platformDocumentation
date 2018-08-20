## Overview
Paths can be configured for every page in an app using the Routes menu in the left panel. These paths specify how a page can be reached. A page can have child paths.
Router Outlet defines the position of a navigated page within a page from where it is navigated. It acts as a placeholder for the navigated page.

## Usage
Router Outlet is used to render a page in a desired location within another page.


### How to use
1. Configure the paths and child paths using “Routes” menu.
2. Drag and drop “Router Outlet” component from the “Navigation” section inside a page’s container where the routed page should be rendered .

### Example
1. Create 2 pages called “home” and “child”.
2. Define a route for the “child” page as a child path of the home component.
3. Create a button component in the "home" page.
4. Set the button’s **routerLink** attribute to “child” page’s path.
5. Drag and drop the “Router Outlet” component from the “Navigation” category in the “home” page container where the routed page(“child”) should be rendered.
6. Now, when the button is clicked, the "child" page will be rendered where the "Router Outlet" component was placed in "home" page.


## Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given.An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.  
(eg. color:blue).

- **Class**: it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name.It accepts string value.   (eg. class=toolbar)


## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

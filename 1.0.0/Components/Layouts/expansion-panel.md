## Overview
Expansion panel is a container which contains some of the components such as  expansion header, expansion title,expansion description etc. Expansion panel can be used alone with all these component or it can be put inside a expansion panel outlet component.
## Usage
Expansion panel component can be used where the data to be displayed in a expanded view, and will be shown and hidden onclick event. Only the title and description will be shown and other components will be hidden and they will displayed when the user clicks on it. 
### How to use
1. Drag and drop a expansion panel component.
2. Fill the attributes such as style, class, ngFor, opened, closed, hideToggle and expanded.
3. Now a container is there various exapansion component can be placed inside this.
### Example
1. Drag and drop a expansion panel outlet component, and inside that drag and drop a expansion panel component.
2. Drag and drop a expansion header component inside the expansion panel.
3. Drag and drop a expansion title and expansion description component inside the expansion header component.
4.  Click on the title and provide the title= Personal Detail and click on description component and provide the description attribute as enter your name.
5. Save and run.
6. A expansion panel will be displayed with the title as Personal Detail and description as enter your name. Many other component can be inserted inside it and it can be implemented more.
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
    - ***ngFor:** ngFor is used when there are multiple expanded panel components. So in that case ngFor is used to iterate through a array or object of expanded panel to display them.And the object or aara will be defined in .ts file. 
- **opened:** This attribute contains an event that should be emitted every time the Accordion Item is opened, so a method or function will be defined and it will be called. Inside the function the actions will be defined that what should happen when the item is open.
- **closed:** This attribute contains an event that should be emitted every time the Accordion Item is closed, so a method or function will be defined and it will be called. Inside the function the actions will be defined that what should happen when the item is closed.
- **hideToggle:** It accepts boolean values as true or false, this attribute is used to check whether the expansion indicator should be hidden.
- **expanded:** It accepts any type of values, to check whether the Accordion Item is expanded.
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
- Angular CLI version: 5.0.0 + 
- Cordova version: 7.1.0 + 

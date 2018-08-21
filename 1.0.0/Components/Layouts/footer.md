## Overview 
A footer component typically contains authorship information, copyright information,contact information, sitemap, back to top links, related documents. There can be several footer components in one document.
## Usage 
A footer components is used when the content should be displayed at the bottom of the page. It can contain multiple components inside it. In footer the data can be anything such as contact information, copyright etc.
### How to use
Drag and drop a footer component and any component could be added, for text content components such as paragraph component etc., can be added
### Example
**Display a block with a title a subtitle, a paragraph component and a footer.** 
- Drag and drop a header component, and provide the style and class attribute.
- Now drag and drop a h3 component inside header for a title and provide the text such as Agra. The title will be set as Agra.
- After setting the title, drag and drop a h5 component inside header below h3 component to set a subtitle because subtitle should be smaller than title, and provide the subtitle as Taj Mahal.
- Now drag and drop a paragraph component inside the header component below the h5 component, and provide some text as content that will be displayed below subtitle.
- Drag and drop a footer component below the header component.
- Drag and drop a paragraph component inside footer component, give the content as (published by a blogger).
- Save and Run, a block with title Taj in h3,a subtitle with Agra in h5 and a paragraph with some content in header component and a footer at the bottom will be displayed.
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
    ## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 + 

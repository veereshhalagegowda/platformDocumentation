
{
  "name" : "header",
  "type" : "Component"
  "category": “Layout”
  "version" : "1.0.0",
  "averageRating" : 1,
  "description" : "The header component represents a container for introductory content or a set of navigational links. ",
  "platformSupportVersion" : "4.0.0",
  "publisher" : "Ayush"

}



## Guide:
### Overview:
A header element typically contains:
- one or more heading elements (<h1> - <h6>)
- logo or icon
- authorship information
There can be several header component in one document.



##### Usage:
A header components is used when the content should be displayed with some special properties such as bigger font size, or when the text should be in bold.Various components can be inserted inside a header component. It has two attributes style and class.


##### How to use
Drag and drop a header component and inside that some component can be inserted such as h1-h6 component, paragraph component etc. 

##### Example
**Display a header component with title  a subtitle in and a paragraph component.**
- Drag and drop a header component, and provide the style and class attribute.
- Now drag and drop a h3 component inside header for a title and provide the text such as Agra. So the title will be set as Agra.
- After setting the title, drag and drop a h5 component inside header below h3 component to set a subtitle because subtitle should be smaller than title, and provide the subtitle as Taj Mahal.

- Now drag and drop a paragraph component inside the header component below the h5 component, and provide some text as content that will be displayed below subtitle.
- Save and Run, a block with title Taj in h3,a subtitle with Agra in h5 and a paragraph will be displayed.
  


### Associated Attributes:
**Style-** accepts string value and it is applied as inline css to element and it is affected based on property given. An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
(eg. color:blue).

**Class-** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name. It accepts string value. (eg. class=toolbar).

### Support 
- **Devices:** Android, iOS
- **Browsers**:  Latest version of all modern browsers
- **Dependencies version:** 
 Angular CLI version: 5.0.0 + 
 Cordova version: 7.1.0 +








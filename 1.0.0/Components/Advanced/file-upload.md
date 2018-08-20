## Overview
File Upload is a button by clicking which the selected files can be uploaded.

## Usage
When the user is needed to upload certain files (such as  scanned images, log file etc.), this component is used to provide that interface.


### How to use

1. Drag and drop the “File Upload” component from the “Advanced” Category where it is needed in that page.
2. Double click on the component and give values to the attributes.
3. Save the changes.

### Example

1. Create a page called “page”.
2. Drag and drop the “File Upload” component.
3. Double click on that component.
4. In “Ts” file, create a property called “uploadOptions” and set its value as below.
    ```typescript
   uploadOptions = {"entityName":"users",
    "metadata":{"key":"sankarshanaj@gmail.com"}
    }
    ```
5. Set the value of [uploadOptions] to “uploadOptions”.
6. Write a function in Ts file as below:
    ```typescript
      onSuccess(){
           console.log("Succesfully uploaded!")
       }
    ```

7. Save the changes.
8. Open the address where the app is running.
9. A button with “choose file” as its value should appear.
10. Click the button, select the file to upload.
11. Click on the button again to upload.


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
- **[uploadOptions]**: Takes the name of the object that is defined in Ts file. The object is of type:
    ```typescript
    {“entityName”: “buttonValue”, “metadata”:{“key”: “aUniqueKey”}}
    ```
    >Where ,
        “entityName” is the name under which the files with same “entityName” are grouped.
        “key” is used to uniquely identify the uploaded file.
    
    
    eg.
    ```typescript
      uploadOptions = {"entityName":"users",
      "metadata":{"key":"sankarshanaj@gmail.com"}}
    ```
- **(onSuccess)**: Takes function (that is defined in Ts file) name as argument which will be called when the upload is successful. eg. onSuccess()
- **(indexChange)**: Takes function (that is defined in Ts file) name as argument which will be called when an error occurs. eg. onError()

## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +



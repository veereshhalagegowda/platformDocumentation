### Overview
File Upload is a button by clicking which the selected files can be uploaded.

### Usage
When the user is needed to upload certain files (such as  scanned images, log file etc…) , this component is used to provide that interface.


### How to use

1. Drag and drop the “File Upload” component from “Advanced” Category where it is needed in that page.
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
8. Open the address where the app is running
9. A button with “choose file” as its value should appear.
10. Click the button, select the file to upload.
11. Click on the button again to upload.


### Associated Attributes
- **Style**: Accepts string value and it is applied as inline css to element and it is affected based on property given.An inline CSS is used to apply a unique style to a single HTML element.An inline CSS uses the style attribute of an HTML element.
- **Class**: It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.The class name can be used by CSS to perform certain tasks for elements with the specified class name.It accepts string value. (eg. class=”btgroup”).
- **[uploadOptions]**: Takes the name of the object of type :
    ```typescript
    {“entityName”: “buttonValue”, “metadata”:{“key”: “aUniqueKey”}}.
    ```
    >Where ,
        “entityName” is the name under which the files with same “entityName” are grouped.
        “key” is used to uniquely identify the uploaded file.
    
        Eg.

      uploadOptions = {"entityName":"users",
      "metadata":{"key":"sankarshanaj@gmail.com"}}

- **(onSuccess)**: Takes function( that is defined in Ts file) name as argument which will be called when the upload is successful. Eg: onSuccess().
- **(indexChange)**:  Takes function( that is defined in Ts file) name as argument which will be called when an error occurs. Eg: onError().

### Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +



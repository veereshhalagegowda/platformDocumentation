




## Overview 
This is component which allows us to create a container of list of particular rows and columns. The column will contain the attribute and the row will contain the data of the particular attribute, and the output will be a list. It must specify a cols attribute which sets the number of columns in the grid. The number of rows will be automatically determined based on the number of columns and the number of items. 


## Usage 
It is a container of list which has user defined layout, the layout will be set by the user, w.r.to that layout a list item will be placed inside that layout.

### How to use 
Drag and drop a grid list component and set the attributes such as style, class, cols, gutterSize, rowHeight. Based on the values for the attributes, the list item will be displayed on the screen.

### Example
**Display a grid list component with a grid-tile component and under that 3 items.** 
- Drag and drop a grid list component and fill the attribute (such as cols = 4) the number of columns depends on this value and row height will be the height of the row (such as rowHeight=100px).
- Drag and drop a grid tile component inside a grid list. It contains attribute such as colspan,rowspan,ngfor and label.
**colspan-** Allows a single table cell to span the width of more than one cell or column.
So in this case give colspan=1
  **rowspan-** Allows a single table cell to span the height of more than one cell or row.
Give rowspan=1
 **Label-** This attribute contains the data of the cell that will be stored inside the row, to be displayed as a list item.
**ngFor-** This attribute is used to iterate through the list item which is stored in the object. It will iterate through each item and display that data.
```sh
Displaylist.html file
<mat-grid-list cols="2" rowHeight="100px">
  <mat-grid-tile
      *ngFor="let tile of tiles" // in *ngFor attribute
         {{tile.text}}    // label attribute
  </mat-grid-tile>
</mat-grid-list>
 ```
  ``` sh
Displaylist.ts
       tiles: Tile[] = [
       {text: 'One'},
       {text: 'Two'},
       {text: 'Three},
    {text: 'Four'},
  ];
  ```
   So in the above example grid has two columns, and tile is a array which has four items which contains string value that are basically labels. So using ngFor the labels will be displayed.

- Save and Run
- A table with four items will be displayed inside a grid-list.


      
 


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

- **Cols-** This property is used to specify the number of columns in the list. It accepts an integer value and is a  mandatory field. The list creation is dependent on this value.

- **gutterSize-** The gutter size can be set to any px, em, or rem value with the gutterSize property. If no units are specified, px units are assumed. By default the gutter size is 1px.

- **row-Height-** The height of the rows in a grid list can be set via the rowHeight attribute. Row height for the list can be calculated in three ways:
- Fixed height: The height can be in px, em, or rem. If no units are specified, px units are        assumed (e.g. 100px, 5em, 250).
- Ratio: This ratio is column-width:row-height, and must be passed in with a colon, not a decimal (e.g. 4:3).
- Fit: Setting rowHeight to fit This mode automatically divides the available height by the number of rows. Please note the height of the grid-list or its container must be set.




## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 + 







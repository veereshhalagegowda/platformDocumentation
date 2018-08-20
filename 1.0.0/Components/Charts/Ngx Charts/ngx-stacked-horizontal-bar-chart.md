## Overview
A stacked horizontal bar chart is similar to the normal bar chart with a difference that in a stacked horizontal bar chart, the data values are plotted using a horizontal bar (row direction). It provides a good comparison of the data which is placed in the row direction. It is also known as a column chart."

## Usage
A stacked horizontal bar chart is widely used in industries, health centers, Data analysis, IT companies etc.
The use case for stacked horizontal bar chart depends on the scope where it is being used. For example, the insurance companies use this chart to display the report of all the insured clients categorized under male or female in particular year or months, IT (Information Technology) companies use this chart for the analysis of the product and service used by their client. Similarly, in the health domain, this chart is used for the treatment analysis and new drugs research data analysis. In all these scopes of the domain, the main use of a stacked horizontal bar chart is for comparison of data categorized on different parameters. 
There are some other popular use cases where bubble chart is used. Some of them are:
-   Insurance companies
-   Industries 
-   Health centers
-   Data analysis

### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the stacked horizontal bar chart from Ngx Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the dataset. Sample is given below:- 
    * Dataset which consists of all other parameters like labels, and legends. 
        ```ts
        dataSet=[
         {
           "name": "Germany",
           "value": 40632
         },
         {
           "name": "United States",
           "value": 
	```
## Associated Attributes
- **Legends (Boolean):** It display category of data that is used in plotting the stacked horizontal bar chart. If it is true, it shows the legends otherwise it does not show.
- **[xAxisLabel] (String):** It gives the name to the x-axis.  For example,
    ```typescript
    [xAxisLabel] = "Country"
    ```
- **[yAxisLabel] (String):** It gives the name to the y-axis.  For example,
    ```typescript
    [yAxisLabel] = "No. of Clients"
    ```
-  **[showXAxisLabel] (True/False):** It displayes the name that is given to the [xAxisLabel]. If it is true, it will display otherwise it does not. For example,
    ```typescript
    [showXAxisLabel]  = 'True' OR [showXAxisLabel]  = 'False'
    ```
-  **[showYAxisLabel] (True/False):** It displayes the name that is given to the [yAxisLabel]. If it is true, it will display otherwise it does not. For example,
    ```typescript
    [showYAxisLabel] = 'True' OR [showYAxisLabel] = 'False'
    ```
-   **Key:** Key is used to provide user custom key point into the chart. It is like a user’s custom parameter provided to the chart section.
-   **Value:** It is a value of the key that the user provided manually. For example,
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

-   **Results (object[]):** It provide a data to the chart which is plotted on a graph using horizontal bars. For example,
    ```ts
    dataSet=[
     {
       "name": "India",
       "value": 135148
     },
     {
       "name": "United States",
       "value": 121652
     },
     {
       "name": "Germany",
       "value": 157885
     },
     {
       "name": "France",
       "value": 965782
     },
     {
       "name": "United Kingdom",
       "value": 987564
     }
    ]
    ```
-   **fxLayout:** It is a flex layout provided to the chart. It provides different orientation such as row orientation, column orientation to the chart. For example, 
    ```ts
    fxLayout = 'row' OR fxLayout = 'column'
    ```
-   **fxFlex:** It is a directive for fxLayout which is used on it for resizing the elements within the flexbox container flow. It provide three options i.e fxFlex Grow, fxFlex shrink, and fxFlex basis. Here is a example of implementation of fxFlex.
    ```html
    <div fxFlex="<grow> <shrink> <basis>"></div>
    ```
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +

## Overview
Polar area chart gives detailed comparison information from its structure. The radius of the slice differs according the value in datasets whereas in pie chart the radius of each slice are same. In this chart, the difference in data can be found easily looking at the radius of the slice.

## Usage
A polar area chart is used as a optional to the pie chart in different fields such as hospitals, retails, industries, data science and analytics etc.
Let us consider a health center scenario where a particular hospital wants to plot a chart for the record of its patient admitted to different wards. The chart should indicate the overall hospital and divided into different section which represent the wards of the hospital. This can be done by using pie chart however it would not provide proper readability from the chart. Therefore, in this case if polar area chart is used, it would provide global understanding them just from the structure of the chart slice.   
There are some other popular use cases where pie chart is used. Some of them are:
-   Industries
-   Industries
-   Government offices
-   Retails
-   Hospitals
-   Government surveys
-   Experimental surveys
### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the polar area chart from Ng Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the following in the component class :- 
    * A dataset array (contains y-axis values and labels of the legend). For example,
        ```typescript 
        public polarChartData: Array<any> = [
        {data:[25, 11, 8, 9, 18, 29]}
        ];
        ```
    * A labels array (contains x-axis values). For example,
        ```typescript
        public polarChartLabels:string[] = ['Emergency & Casualty', 'Labor Ward', 'Endoscopy Ward', 'Coronary Ward', 'Surgical Ward','General Ward'];
        ```
    * Legend value (either true or false). For example, 
        ```typescript
        public legend=false;
        ```
    * Options value. For example,
        ```typescript
        public polarChartOptions:any = {
        responsive: true
        };
        ```
4. Now switch back to Html file of the page and 
5. Provide the dataset array name in the [datasets] attribute. For example,
        ```
		[datasets] = polarChartData
		```
6. Provide the labels name in [labels] attribute. For example,
        ```
        [labels] = polarChartLabels
        ```
7. Provide the options name in [options] attribute. For example,
        ```
        [legend] = legend
        ```
8. Provide the legend name in [legend] attributes. For example,
        ```
		[options] = polarChartOptions
		```
9. Save the page and run the application 
### Example
Consider an example of hospital where hospital wants to plot a chart for the record of its patient admitted to different wards such as emergency & casualty, labor ward, Endoscopy Ward, Coronary Care ward, and Surgical Ward.

| Hospital Wards | Emergency &  Casualty | Labor Ward | Endoscopy Ward | Coronary Ward | Surgical Ward | General Ward |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| **Patients (%)** | 25 | 11 | 8 | 9 | 18 | 29 |

-   #### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
public polarChartData: Array<any> = [
        {data:[25, 11, 8, 9, 18, 29]}
];
```
-   #### Labels:
Here is a sample of labels that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
public polarChartLabels:string[] = ['Emergency & Casualty', 'Labor Ward', 'Endoscopy Ward', 'Coronary Ward', 'Surgical Ward','General Ward'];
```
-   #### Legend
Here is a sample of legend that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
  public legend=true;
```
-   #### Options:
Here is a sample of options that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
 public polarChartOptions:any = {
   responsive: true };
```
## Associated Attributes
- **Label (String Array):** Labels are the identity of the data series in a chart. It appears in the legend and tooltips. It gives a specific name to each section of the chart area. For example, 
    ```typescript
    public polarChartLabels:string[] = ['Emergency & Casualty', 'Labor Ward', 'Endoscopy Ward', 'Coronary Ward', 'Surgical Ward','General Ward'];
    ```

-   **Datasets (JSON Objects Array):** It is a data of the chart which is framed on a circular slice. For example,
    ```typescript
    public polarChartData: Array<any> = [
     {data:[25, 11, 8, 9, 18, 29]}
    ];
    ```
- **chartHover/chartClick (mouse Events):** It is a event which appears when the mouse is taken or clicked over slice of the polar area chart. For example, displaying label and point value when mouse is clicked on the slice of of the chart or mouse is moved over it. 
- **Legends (Boolean):** It is a name given to the same category of data that is used in plotting the polar chart. If it is true, it shows the legends otherwise it does not show.
- **Color (Color/color hexadecimal code):** This property provides user desire color to the polar chart. For example, 
    ```css
    background-color: #92a8d1;
    ```
-   **Key:** Key is used to provide user custom key point into the chart. It is like a user’s custom parameter provided to the chart section.
-   **Value:** It is a value of the key that the user provided manually. For example,
-   **style:** Used to specify the inline style. It is applied to the specific element. For example 
    ```css
    text {
    	color: maroon;
    }
    ```
    Here in this examplee, the text we type will be in maroon color
-   **class:** It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
## Support 
### Devices : 
-   Android
-   iOS
### Dependencies Version
-   **Angular CLI Version**
    -   Version 5.0.0 +
-   **Cordova Version**
    -   Version 7.1.0 +


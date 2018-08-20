## Overview
Doughnut chart is similar to the pie chart but the different is doughnut chart have a circular hollow gap at the middle of the chart. This circular hollow gap is called as “cutoutPercentage” which represents what percentage of the inner should be cut out.

## Usage
A Doughnut chart is widely used in business world, mass media, and institutions.
Let us consider a health center scenario where a particular hospital wants to plot a chart for the record of its patient admitted to different wards. The chart should indicate the overall hospital and divided into different section which represent the wards of the hospital. This can be achieved using  Doughnut chart where a complete chart presents the hospital and divided slice of pie represent the wards of the hospital. 
There are some other popular use cases where pie chart is used. Some of them are:
-   Pharmaceutical Industries (indicating the different section of drugs)
-   Industries (for providing information on different product and services )
-   Government offices (like revenue department)
-   Retails (for different types of product they provide)

### How to use
1. Open the newly created page.
2. Drag and drop the doughnut chart from Ng Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the following in the component class :- 
    * A dataset array (contains y-axis values and labels of the legend). For example,
        ```typescript 
        public doughnutChartData: Array<any> = [
        {data:[25, 11, 8, 9, 18, 29]}
        ];
        ```
    * A labels array (contains x-axis values). For example,
        ```typescript
        public doughnutChartLabels:string[] = ['Emergency & Casualty', 'Labor Ward', 'Endoscopy Ward', 'Coronary Ward', 'Surgical Ward','General Ward'];
        ```
    * Legend value (either true or false). For example, 
        ```typescript
        public legend=false;
        ```
    * Options value. For example,
        ```typescript
        public doughnutChartOptions:any = {
        responsive: true
        };
        ```
4. Now switch back to Html file of the page and provide the dataset array name in the [datasets] attribute. For example,
        ```
		[datasets] = doughnutChartData
		```
6. Provide the labels name in [labels] attribute. For example,
        ```
        [labels] = doughnutChartLabels
        ```
7. Provide the options name in [options] attribute. For example,
        ```
        [legend] = legend
        ```
8. Provide the legend name in [legend] attributes. For example,
        ```
		[options] = doughnutChartOptions
		```
9. Save the page and run the application. 
### Example
Consider an example of hospital where hospital wants to plot a chart for the record of its patient admitted to different wards such as emergency & casualty, labor ward, Endoscopy Ward, Coronary Care ward, and Surgical Ward.

| Hospital Wards | Emergency &  Casualty | Labor Ward | Endoscopy Ward | Coronary Ward | Surgical Ward | General Ward |
| :------: | :------: | :------: | :------: | :------: | :------: | :------: |
| **Patients (%)** | 25 | 11 | 8 | 9 | 18 | 29 |

#### Datasets
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
public doughnutChartData: Array<any> = [
     {data:[25, 11, 8, 9, 18, 29]}
 ];
```
#### Labels
Here is a sample of labels that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
public doughnutChartLabels:string[] = ['Emergency & Casualty', 'Labor Ward', 'Endoscopy Ward', 'Coronary Ward', 'Surgical Ward','General Ward'];
```
#### Legend
Here is a sample of legend that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
  public legend=true;
```
#### Options
Here is a sample of options that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
 public doughnutChartOptions:any = {
   responsive: true };
```
## Associated Attributes
- **Label (String Array):** Labels are the identity of the data series in a chart. It appears in the legend and tooltips. It gives a specific name to each slice in the doughnut chart. For example, 
    ```typescript
    public doughnutChartLabels:string[] = ['Emergency & Casualty', 'Labor Ward', 'Endoscopy Ward', 'Coronary Ward', 'Surgical Ward','General Ward'];
    ```

-   **Datasets (JSON Objects Array):** It is a data of the chart which is framed on a circular slice depending upon the dataset values. For example,
    ```typescript
    public doughnutChartData: Array<any> = [
     {data:[25, 11, 8, 9, 18, 29]}
    ];
    ```
- **chartHover/chartClick (mouse Events):** It is a event which appears when the mouse is taken or clicked over slice of the doughnut chart. For example, displaying label and point value when mouse is clicked on the slice of of the chart or mouse is moved over it. 
- **Legends (Boolean):** It is a name given to the same category of data that is used in plotting the doughnut chart. If it is true, it shows the legends otherwise it does not show.
- **Color (Color/color hexadecimal code):** This property provides user desire color to the doughnut chart. For example, 
    ```css
    background-color: #92a8d1;
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
## Support
- **Devices:** Android, iOS
- **Browsers:**  Latest version of all modern browsers
- **Dependencies version:** 
    - Angular CLI version: 5.0.0 + 
    - Cordova version: 7.1.0 +


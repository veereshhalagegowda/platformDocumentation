## Overview
It plots the point using the bubble in three dimensions at the same time. The place to plot the data value is determined by the first two dimensions and the corresponding horizontal and vertical axes. The third dimension of the chart represents the size of the individual bubble which depends on the data values. 

## Usage
A bubble chart is widely used in industries, health centers, climate, government surveys etc.
Let's consider a use case in Industry, where the industry wants to show the service and product provided in the different part of the country. The collected data need to plot on a map of the country region. The bubble graph displays the service of the corresponding industry in the different part of the country. 
There are some other popular use cases where bubble chart is used. Some of them are:
-   Government Survey
-   Health care centers
-   Industries
-   Experimental surveys
### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the bubble chart from Ng Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the following in the component class :- 
    * A dataset array (contains y-axis values and labels of the legend). For example,
        ```typescript 
        public bubbleChartData: Array<any> =
        [{
        label: ['Deer Population'],
        data: [{
            x: 100,
            y: 5,
            r: 10
            }, {
            x: 60,
            y: 30,
            r: 20
            }, {
            x: 40,
            y: 60,
            r: 25
            }, {
            x: 80,
            y: 80,
            r: 50
            }]
        }];
        ```
    * A labels array (contains x-axis values). For example,
        ```typescript
        public bubbleChartLabels:string[] = ['Deer Population'];
        ```
    * Legend value (either true or false). For example, 
        ```typescript
        public legend=false;
        ```
    * Options value. For example,
        ```typescript
        public bubbleChartOptions:any = {
        responsive: true
        };
        ```
4. Now switch back to Html file of the page and 
5. Provide the dataset array name in the [datasets] attribute. For example,
        ```
		[datasets] = bubbleChartData
		```
6. Provide the labels name in [labels] attribute. For example,
        ```
        [labels] = radarChartLabels
        ```
7. Provide the legend name in [legend] attribute. For example,
        ```
        [legend] = legend
        ```
8. Provide the option name in [Options] attributes. For example,
        ```
		[options] = radarChartOptions
		```
9. Save the page and run the application 
### Example
Consider a survey on population at different part of the country. The number of population in particular area need to be displayed on on a country map using a bubble. For example,

| Data/Area | X | Y | Radius of Circle |
| ------ | ------ | ------ | ------ |
| **Area 1** | 100 | 50 | 20 |
| **Area 2** | 60 | 30 | 10 |
| **Area 3** | 80 | 65 | 15 |
-   ###### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
public bubbleChartData: Array<any> =
      [{
   label: ['Deer Population'],
   data: [{
     x: 100,
     y: 5,
     r: 10
   }, {
     x: 60,
     y: 30,
     r: 20
   }, {
     x: 40,
     y: 60,
     r: 25
   }, {
     x: 80,
     y: 80,
     r: 50
   }]
}];
```
-   #### Labels:
Here is a sample of labels that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
public bubbleChartLabels:string[] = ['Deer Population'];
```
-   #### Legend
Here is a sample of legend that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
  public legend=true;
```
-   #### Options:
Here is a sample of options that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
 public bubbleChartOptions:any = {
   responsive: true };
```
## Associated Attributes
- **Label (String Array):** Labels are the identity of the data series in a chart. It appears in the legend and tooltips. It gives a specific name to each data plotted in circular shape.  For example, 
    ```typescript
    public bubbleChartLabels:string[] = ['Deer Population'];
    ```

-   **Datasets (JSON Objects Array):** It is a data of the chart which is framed on a circular slice. For example,
    ```typescript
    public bubbleChartData: Array<any> =
      [{
    label: ['Deer Population'],
    data: [{
     x: 100,
     y: 5,
     r: 10
    }, {
     x: 60,
     y: 30,
     r: 20
    }, {
     x: 40,
     y: 60,
     r: 25
    }, {
     x: 80,
     y: 80,
     r: 50
    }]
    }];
    ```
- **chartHover/chartClick (mouse Events):** It is a event which appears when the mouse is taken or clicked over chart area. For example, displaying label and point value when mouse is clicked on the bubble of of the chart or mouse is moved over it. 
- **Legends (Boolean):** It is a name given to the same category of data that is used in plotting the bubble chart. If it is true, it shows the legends otherwise it does not show.
- **Color (Color/color hexadecimal code):** This property provides user desire color to the radar chart. For example, 
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

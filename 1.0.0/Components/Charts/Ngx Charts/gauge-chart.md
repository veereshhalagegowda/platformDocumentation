## Overview
It uses needles to show the information about the data values on a speedometer. Each section in the gauge needle is colored with different color and placed on different axis. 

## Usage
A gauge chart is widely used in executive dashboard reports to show key business indicators. They are useful for comparing small number of variables using a multiple needles on speedometer space.
### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the gauge chart from Ngx Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the dataset. Sample is given below:- 
    * Dataset which consists of all other parameters like labels, and legends. For example, 
        ```ts
        ngxGaugeChartData = [
      {
        "name": "Germany",
        "value": 40632
      },
      {
        "name": "United States",
        "value": 49737
      },
      {
        "name": "France",
        "value": 36745
      },
      {
        "name": "United Kingdom",
        "value": 36240
      },
      {
        "name": "Spain",
        "value": 33000
      },
      {
        "name": "Italy",
        "value": 35800
      }
         ]
        ```
4. Now switch back to Html file of the page and provide the dataset array name in the [datasets] attribute. For example,
        ```
		[results] = ngxGaugeChartData
		```
5. Save the page and run the application 
### Example
Consider a IT company wants a dashboard reports for different branch to show key business performance indicators so that it can be compared easily with KPI (Key Performance Indicator). Here is an example,

| Parameters | KPI |
| ------ | ------ | 
| **Germany** | 406323 |
| **United State** | 49737 | 
| **France** | 36745 |
-   #### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
ngxGaugeChartData = [
  {
    "name": "Germany",
    "value": 40632
  },
  {
    "name": "United States",
    "value": 49737
  },
  {
    "name": "France",
    "value": 36745
  }
]
```
-   #### Labels:
Here, the labels are automatically taken by from the dataset.
## Associated Attributes
-   **angleSpan (Number):** It is the angle provided to the gauge spans. The unit is in degrees and default value is 240 degree.
-   **startAngle (Number):** It is the angle that the chart is rotate by. It is measured in degree and default value is -120 degree. Usually, negative half of the spanning angle (angleSpan) is taken to centralize the chart. 
-   **units (String):** It is text given to display under the value of the chart data values.
-   **bigSegments (Number):** It is a number of big segments given on the axis collected from the given data set. 
-   **smallSegments (number):** It is a number of small segments that appears in between every big segments. 
-   **min (number):** It is the starting point of the scale on the chart from where every data set point starts getting plotted. 
-   **max (number):** It is the ending point of the scale in the gauge on which the data set values are plotted. 
-   **Key:** Key is used to provide user custom key point into the chart. It is like a user’s custom parameter provided to the chart section.
-   **Value:** It is a value of the key that the user provided manually.
-   **style:** Used to specify the inline style. It is applied to the specific element. For example 
    ```css
    text {
    	color: maroon;
    }
    ```
    Here in this examplee, the text we type will be in maroon color
-   **class:** It specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
-   **select (Events):** It takes a click event which is done on the bars of the chart. It display some result on click or hover of mouse. For example, displaying data point, label on click of individual bars.
-   **scheme:** It is a color scheme of the chart. For example,
    ```ts
    let colorSets = [
      {
        name: 'vivid',
        selectable: true,
        group: 'Ordinal',
        domain: ['#647c8a', '#3f51b5', '#2196f3', '#00b862', '#afdf0a', '#a7b61a', '#f3e562', '#ff9800', '#ff5722', '#ff4514'
        ]
      } ];
    ```
-   **Results (object[]):** It provide a data to the chart which is plotted on a graph using horizontal bars. For example,
    ```ts
    ngxGaugeChartData = [
      {
        "name": "Germany",
        "value": 40632
      },
      {
        "name": "United States",
        "value": 49737
      },
      {
        "name": "France",
        "value": 36745
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
### Devices : 
-   Android
-   iOS
### Dependencies Version
-   **Angular CLI Version**
    -   Version 5.0.0 +
-   **Cordova Version**
    -   Version 7.1.0 +

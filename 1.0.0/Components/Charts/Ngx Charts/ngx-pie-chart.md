## Overview
It is a circular chart which is divided into different slice which represents the corresponding data values.

## Usage
A pie chart is widely used in business world, mass media, product analysis, survey and experimental analysis etc. 
Consider a health center scenario where a particular hospital wants to plot a chart for the record of its patient admitted to different wards. The chart should indicate the overall hospital and divided into different section which represent the wards of the hospital. This can be achieved using  pie chart where a complete pie presents the hospital and divided slice of pie represent the wards of the hospital. 
Some of the other popular use cases of line chart are:
-   Pharmaceutical Industries (indicating the different section of drugs)
-   Industries (for providing information on different product and services )
-   Government offices (like revenue department)
-   Retails (for different types of product they provide)
### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the pie chart from Ngx Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the dataset. Sample is given below:- 
    * Dataset which consists of all other parameters like labels, and legends. For example, 
        ```ts
        ngxpieChartData = [
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
		[results] = ngxpieChartData
		```
5. X-axis and Y-axis label can be shown or hidden by providing,
    ``` [labels] = true ```  OR ```[labels] = false ```

6. Legends can be shown or hidden by providing,
    ``` [legend] = true ```  OR ```[legend] = false ```
7. Save the page and run the application 
### Example
Consider an IT industry which makes a survery on how many users use their product from different part of the world. The sample data can be recoded as follows:

| Country | Germany | USA | Spain | France | Nepal | India |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| **Users** | 730000 | 7870000 | 1569558 | 1645553 | 1058048 | 1546488 |
-   #### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
ngxpieChartData = [
  {
    "name": "Germany",
    "value": 730000
  },
  {
    "name": "USA",
    "value": 7870000
  },
  {
    "name": "Spain",
    "value": 1569558
  },
  {
    "name": "France",
    "value": 1645553
  },
  {
    "name": "Nepal",
    "value": 1058048
  },
  {
    "name": "India",
    "value": 1546488
  }
]
```
-   #### Labels:
Here, the labels are automatically taken by from the dataset.
-   #### Legend
Here is a sample of legend that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
 [legend] = true;
```
This legends is taken from the dataset, and displayed on the right side of the chart by default. Only the **name** parameter is taken into the legend section. 
## Associated Attributes
- **Legends (Boolean):** It display category of data that is used in plotting the stacked horizontal bar chart. If it is true, it shows the legends otherwise it does not show.
    ```typescript
    [legend] = true;
    ```
- **xAxisLabel (String):** It gives the name to the x-axis.  For example,
    ```typescript
    [xAxisLabel] = "Country"
    ```
- **Labels (True/false):** It gives the name to the x-axis and y-axis. These levels are selected from the dataset. If it is true, it shows the x-axis and y-axis levels otherwise it does not show. 
-   **explodeSlices (True/false) :** It gives the radius to the each slice. The radius of the slice will be proportional to its value. If it is true, it make the radius proportional to its values and if it is false, normal slice division is made. 
-   **Key:** Key is used to provide user custom key point into the chart. It is like a user’s custom parameter provided to the chart section.
-   **Doughnut (True / False):** This attribute provide a hollow space at the center of pie chart. If it is true, the hollow space will be inserted in to the chart otherwise not. 
-   **Value:** It is a value of the key that the user provided manually. For example,
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
        ngxpieChartData = [
      {
        "name": "Germany",
        "value": 730000
      },
      {
        "name": "USA",
        "value": 7870000
      },
      {
        "name": "Spain",
        "value": 1569558
      },
      {
        "name": "France",
        "value": 1645553
      },
      {
        "name": "Nepal",
        "value": 1058048
      },
      {
        "name": "India",
        "value": 1546488
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

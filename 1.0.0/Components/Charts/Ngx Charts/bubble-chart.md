## Overview
It plots the point using the bubble in three dimensions at the same time. The place to plot the data value is determined by the first two dimensions and the corresponding horizontal and vertical axes. The third dimension of the chart represents the size of the individual bubble which depends on the data values.

## Usage
A bubble chart is widely used in business world, mass media, product analysis, survey and experimental analysis etc. 
Consider a health center scenario where a particular hospital wants to plot a chart for the record of its patient admitted to different wards. The chart should indicate the overall hospital and divided into different section which represent the wards of the hospital. This can be achieved using  pie chart where a complete pie presents the hospital and divided slice of pie represent the wards of the hospital. 
Some of the other popular use cases of bubble chart are:
-   Pharmaceutical Industries (indicating the different section of drugs)
-   Industries (for providing information on different product and services )
-   Government offices (like revenue department)
-   Retails (for different types of product they provide)
### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the bubble chart from Ngx Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the dataset. Sample is given below:- 
    * Dataset which consists of all other parameters like labels, and legends. For example, 
        ```ts
        ngxbubbleChartData = [
          {
            "name": "USA",
            "series": [
              {
                "name": "2010",
                "x": 49737,
                "y": 78.8,
                "r": 310
              },
              {
                "name": "2000",
                "x": 45986,
                "y": 76.9,
                "r": 283
              },
              {
                "name": "1990",
                "x": 3706,
                "y": 75.4,
                "r": 253
              }
            ]
          },
          {
            "name": "France",
            "series": [
              {
                "name": "2010",
                "x": 36745,
                "y": 81.4,
                "r": 63
              },
              {
                "name": "2000",
                "x": 34774,
                "y": 79.1,
                "r": 59.4
              },
              {
                "name": "1990",
                "x": 29476,
                "y": 77.2,
                "r": 56.9
              }
            ]
          }
        ]
        ```
4. Now switch back to Html file of the page and provide the dataset array name in the [datasets] attribute. For example,
        ```
		[results] = ngxbubbleChartData
		```
5. X-axis label can be shown or hidden by providing,
    ``` [xAxis] = true ```  OR ```[xAxis] = false ```

6. Y-axis label can be shown or hidden by providing,
    ``` [yAxis] = true ```  OR ```[yAxis] = false ```

7. Legends can be shown or hidden by providing,
    ``` [legend] = true ```  OR ```[legend] = false ```
8. Save the page and run the application 
### Example
Consider a insurance company which made a survey on its client at different part of the country. The number of clietn in particular area need to be displayed on on a country map using a bubble. For example,

| Data/Area | X | Y | Radius of Circle |
| ------ | ------ | ------ | ------ |
| **Area 1** | 100 | 50 | 20 |
| **Area 2** | 60 | 30 | 10 |
| **Area 3** | 80 | 65 | 15 |
-   #### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
ngxbubbleChartData = [
  {
    "name": "USA",
    "series": [
      {
        "name": "2010",
        "x": 49737,
        "y": 78.8,
        "r": 310
      },
      {
        "name": "2000",
        "x": 45986,
        "y": 76.9,
        "r": 283
      },
      {
        "name": "1990",
        "x": 3706,
        "y": 75.4,
        "r": 253
      }
    ]
  },
  {
    "name": "France",
    "series": [
      {
        "name": "2010",
        "x": 36745,
        "y": 81.4,
        "r": 63
      },
      {
        "name": "2000",
        "x": 34774,
        "y": 79.1,
        "r": 59.4
      },
      {
        "name": "1990",
        "x": 29476,
        "y": 77.2,
        "r": 56.9
      }
    ]
  }
];
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
- **Legends (True/False):** It display category of data that is used in plotting the stacked horizontal bar chart. If it is true, it shows the legends otherwise it does not show.
-   **Legend Title (String):** It gives a title name for the legend which is displayed for the chart. 
-   **showGridLines (True/False):** It show or hide the grid lines in the chart. If it is true, it shows lines in the chart otherwise it does not. By default it is true.
-   **roundDomains (True/False):** It round the domain for aligned gridlines in the chart. By default it is false.
-   **minRadius (number):** It is a minimum bubble radius provided the chart. It is measured in px. 
-   **maxRadius (number):** It is a maximum bubble radius that is fixed to the chart. It is measured in px.
-   **[xAxis] (True/False):** This attribute diplays the level for the x-axis. If it is true, it will display otherwise it does not. For example,
    ```typescript
    [xAxis] = 'True' OR [xAxis] = 'False'
    ```
-  **[yAxis] (True/False):** This attribute diplays the level for the y-axis as like x-axis. If it is true, it will display otherwise it does not. For example,
    ```typescript
    [yAxis] = 'True' OR [yAxis] = 'False'
    ```
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
    ngxbubbleChartData = [
      {
        "name": "USA",
        "series": [
          {
            "name": "2010",
            "x": 49737,
            "y": 78.8,
            "r": 310
          },
          {
            "name": "2000",
            "x": 45986,
            "y": 76.9,
            "r": 283
          },
          {
            "name": "1990",
            "x": 3706,
            "y": 75.4,
            "r": 253
          }
        ]
      },
      {
        "name": "France",
        "series": [
          {
            "name": "2010",
            "x": 36745,
            "y": 81.4,
            "r": 63
          },
          {
            "name": "2000",
            "x": 34774,
            "y": 79.1,
            "r": 59.4
          },
          {
            "name": "1990",
            "x": 29476,
            "y": 77.2,
            "r": 56.9
          }
        ]
      }
    ];
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

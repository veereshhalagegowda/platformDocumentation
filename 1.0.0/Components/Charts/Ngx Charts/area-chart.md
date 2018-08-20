## Overview
An area chart is based on line chart. The area between the axis and line are colored with different colors, textures, and hatchings.

## Usage
An area chart is widely used in comparing the trending data such as stock market shares.
The use case for line chart depends on the scope where it is being used. For example, industries use area chart to display the report of product sales in different geographical regions, IT (Information Technology) companies use this chart for the analysis of the product and service used by their client. Similarly, in the health domain, this chart is used for the treatment analysis and new drugs research data analysis. In all these scopes of the domain, the main use of a line chart is for comparison of data categorized on different parameters. 
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
2. Drag and drop the line chart from Ngx Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the dataset. Sample is given below:- 
    * Dataset which consists of all other parameters like labels, and legends. 
        ```ts
        dataSet = [
      {
        "name": "Germany",
        "series": [
          {
            "Year": "2010",
            "value": 7300000
          },
          {
            "name": "2011",
            "value": 8940000
          }
        ]
      },
      {
        "name": "USA",
        "series": [
          {
            "name": "2010",
            "value": 7870000
          },
          {
            "name": "2011",
            "value": 8270000
          }
        ]
        }
        ];
        ```
4. Now switch back to Html file of the page and provide the dataset array name in the [datasets] attribute. For example,
        ```
		[results] = dataSet
		```
5. X-axis label can be shown or hidden by providing,
    ``` [xAxis] = true ```  OR ```[xAxis] = false ```

6. Y-axis label can be shown or hidden by providing,
    ``` [yAxis] = true ```  OR ```[yAxis] = false ```

7. Legends can be shown or hidden by providing,
    ``` [legend] = true ```  OR ```[legend] = false ```
8. Save the page and run the application 
### Example
Consider an industry which records the data of their product sales from different country. The company plot the data on the area chart to get the better comparison on variations on sales of products from different country. For example,

| Country | Germany | USA |
| ------ | ------ | ------ |
| **2010** | 7300000 | 7870000 |
| **2011** | 8940000 | 8270000 |
-   #### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
dataSet = [
  {
    "name": "Germany",
    "series": [
      {
        "name": "2010",
        "value": 7300000
      },
      {
        "name": "2011",
        "value": 8940000
      }
    ]
  },
  {
    "name": "USA",
    "series": [
      {
        "name": "2010",
        "value": 7870000
      },
      {
        "name": "2011",
        "value": 8270000
      }
    ]
  }
];
```
-   #### Labels:
Here, teh labels are automatically taken by from the dataset. The label will be **'name'** for the y-axis and **'values'** for the x-axis
-   #### Legend
Here is a sample of legend that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
 [legend] = true;
```
This legends is taken from the dataset, and displayed on the right side of the chart by default. Only the **name** parameter is taken into the legend section. 
## Associated Attributes
- **Gradient (Color/color hexadecimal code):** Gradient is a combination of different colors pattern and style which is used to fill the horizontal bars in the chart.  For example, 
    ```css
    background: linear-gradient(to bottom, #33ccff 0%, #ff99cc 100%)
    ```

-   **[xAxis] (True/False):** This attribute diplays the level for the x-axis. If it is true, it will display otherwise it does not. For example,
    ```typescript
    [xAxis] = 'True' OR [xAxis] = 'False'
    ```
-  **[yAxis] (True/False):** This attribute diplays the level for the y-axis as like x-axis. If it is true, it will display otherwise it does not. For example,
    ```typescript
    [yAxis] = 'True' OR [yAxis] = 'False'
    ```
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
    dataSet = [
      {
        "name": "Germany",
        "series": [
          {
            "name": "2010",
            "value": 7300000
          },
          {
            "name": "2011",
            "value": 8940000
          }
        ]
      },
      {
        "name": "USA",
        "series": [
          {
            "name": "2010",
            "value": 7870000
          },
          {
            "name": "2011",
            "value": 8270000
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

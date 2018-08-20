## Overview
A bar chart plots the data points using the vertical or horizontal bars providing the good comparison of multiple data points plotting them side by side. The bar chart includes additional properties over line chart i.e. barPercentage, categoryPercentage, barThickness, maxBarThickness.
 
## Usage
A bar chart is widely used in the scenario where there is a need of comparison of multiple data points plotting them side by side.
Let’s take a scenario of the banking where the bank generates a chart on the report of its performance. The report chart should consist of net profit margin, assets, Investors, and net bank credit to government (NBCG) of different years. The chart should hold self-explanation and comparison. This can be achieved using the bar chart which plots the data using vertical or horizontal bars. 
Some of the other popular use cases of line chart are:
-   Industry (product analysis)
-   Health centers (Disease and cure comparison)
-   Retails (Sales comparison)
-   Government Surveys (GDP (Gross Domestic Product), PCI (Per Capita Income) etc)
### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the bar chart from Ng Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the following in the component class :- 
    * A dataset array (contains y-axis values and labels of the legend). For example,
        ```typescript 
        public barChartData:Array<any> = [
        {data: [65, 59, 55, 81, 56, 55, 40], label: 'Series A'},
        {data: [28, 48, 40, 19, 86, 27, 90], label: 'Series B'}
         ];
        ```
    * A labels array (contains x-axis values). For example,
        ```typescript
        public barChartLabels:Array<any> = ['January', 'February', 'March','April', 'May', 'June', 'July'];
        ```
    * Legend value (either true or false). For example, 
        ```typescript
        public legend=false;
        ```
    * Options value. For example,
        ```typescript
        public barChartOptions:any = {
        responsive: true
        };
        ```
4. Now switch back to Html file of the page and 
5. Provide the dataset array name in the [datasets] attribute. For example,
        ```
		[datasets] = barChartData
		```
6. Provide the labels name in [labels] attribute. For example,
        ```
        [labels] = barChartLabels
        ```
7. Provide the options name in [options] attribute. For example,
        ```
        [legend] = legend
        ```
8. Provide the legend name in [legend] attributes. For example,
        ```
		[options] = barChartOptions
		```
9. Save the page and run the application 
### Example
Let's take an example from banking scope generating a report on different years which includes the performance parameter i.e. net profit margin, assets, Investors, and net bank credit to government (NBCG).

| Months (2017) | Net Profit Margin (%) | Assets (%) | Investors (%) | Net bank credit to govt. (%) |
| ------ | ------ | ------ | ------ | ------ |
| **2013** | 69 | 60 | 47 | 23 |
| **2014** | 72 | 64 | 59 | 47 |
| **2015** | 82 | 69 | 65 | 50 |
| **2016** | 79 | 79 | 69 | 55 |
| **2017** | 92 | 60 | 80 | 65 |

-   #### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
public barChartData:Array<any> = [
   {data: [69, 72, 82, 79, 92], label: 'Net Profit Margin (%)'},
   {data: [60, 64, 69, 79, 60], label: 'Assets (%)'},
   {data: [47, 59, 65, 69, 80], label: 'Investors (%)'},
   {data: [23, 47, 50, 55, 65], label: 'Net Bank Credit to Government(%)'} ];
```
-   #### Labels:
Here is a sample of labels that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
public barChartLabels:Array<any> = ['2013', '2014', '2015','2016','2017'];
```
-   #### Legend
Here is a sample of legend that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
  public legend=true;
```
-   #### Options:
Here is a sample of options that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
 public barChartOptions:any = {
   responsive: true };
```
## Associated Attributes
- **Label (String Array):** Labels are the identity of the data series in a chart. It appears in the legend and tooltips. For example, 
    ```typescript
    ChartLabels:Array<any> = ['January', ‘February’, 'March', 'April', 'May', 'June', 'July'];
    ```

-   **Datasets (JSON Objects Array):** It is a data of the chart which is framed on a a vertical or horizontal bars. For example,
    ```typescript
    {data: [69, 72, 82, 79, 92], label: 'Net Profit Margin (%)'} ];
    ```
- **chartHover/chartClick (mouse Events):** It is a event which appears when the mouse is taken or clicked over the line chart. For example, displaying label and point value when mouse is clicked on the chart or mouse is moved over the chart. 
- **Legends (Boolean):** It is a name given to the same category of data that is used in plotting the bar chart. If it is true, it shows the legends otherwise it does not show.
- **Color (Color/color hexadecimal code):** This property provides user desire color to the line chart. For example, 
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


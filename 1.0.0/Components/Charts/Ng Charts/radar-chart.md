## Overview
It is also know as web chart, cobweb chart or spider chart. It plots the data in irregular polygon. All the axis in this chart are connected from a common center point on which data values are plotted. This ploting method forms a spider web like structure which gives proper comparison between the data groups.

## Usage
A radar chart is widely used in hospitals, cricket world, industry, etc.
Let us consider a scenario from a particular industry where a human resource (HR) team want to prepare a chart on the performance of hiring candidates skills score obtained during the selection process. In this case, the HR should be able to take a glance of all the candidates performance score. This can be achieved using radar chart. It will plot all the candidates performance score in a spider web form and provide a better understandability from it. 
There are some other popular use cases where radar chart is used. Some of them are:
-   Industries
-   Government offices
-   Retails
-   Hospitals
-   Experimental surveys
### Prerequisites
1. New page.
2. Default route for the newly created page.
### How to use?
1. Open the newly created page.
2. Drag and drop the radar chart from Ng Charts category.
3. Switch to **Ts** file of the page and then declare the variable and provide values for the following in the component class :- 
    * A dataset array (contains y-axis values and labels of the legend). For example,
        ```typescript 
        public radarChartData:Array<any> = [
        {data: [7, 8, 6, 9, 7, 9], label: 'Dayashankar'},
        {data: [6, 7, 7, 8, 6, 8], label: 'Oliver'}
        ];
        ```
    * A labels array (contains x-axis values). For example,
        ```typescript
        public radarChartLabels:string[] = ['Communication Skills', 'Technical Knowledge', 'Team Work', 'Meeting Deadline', 'Problem Solving', 'Punctuality'];
        ```
    * Legend value (either true or false). For example, 
        ```typescript
        public legend=false;
        ```
    * Options value. For example,
        ```typescript
        public radarChartOptions:any = {
        responsive: true
        };
        ```
4. Now switch back to Html file of the page and 
5. Provide the dataset array name in the [datasets] attribute. For example,
        ```
		[datasets] = radarChartData
		```
6. Provide the labels name in [labels] attribute. For example,
        ```
        [labels] = radarChartLabels
        ```
7. Provide the options name in [options] attribute. For example,
        ```
        [legend] = legend
        ```
8. Provide the legend name in [legend] attributes. For example,
        ```
		[options] = radarChartOptions
		```
9. Save the page and run the application 
### Example
Consider an example of an industry where HR (Human Resource) Team hires some professional. They conduct different activities to monitor the following skills of the candidates, Communication skills, technical knowledge, teamwork, meeting deadline, problem-solving, and punctuality. The head HR should be able to glance at the candidates' performance through a graph or chart which reflects the good comparison with all candidates. This can be achieved using a radar chart. For example,

| Skills/Candidates | Communication Skills | Technical Knowledge | Team Work | Meeting Deadline | Problem Solving | Punctuality |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| **Dayashankar** | 7 | 8 | 6 | 9 | 7 | 9 |
| **Oliver** | 6 | 7 | 7 | 8 | 6 | 8 |

-   #### Datasets:
Here is a sample of dataset that is declaired and initialized in the component class **Ts** file of the project. 
```typescript
public radarChartData:Array<any> = [
    {data: [7, 8, 6, 9, 7, 9], label: 'Dayashankar'},
    {data: [6, 7, 7, 8, 6, 8], label: 'Oliver'}
  ];
```
-   #### Labels:
Here is a sample of labels that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
public radarChartLabels:string[] = ['Communication Skills', 'Technical Knowledge', 'Team Work', 'Meeting Deadline', 'Problem Solving', 'Punctuality'];
```
-   #### Legend
Here is a sample of legend that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
  public legend=true;
```
-   #### Options:
Here is a sample of options that is declaired and initialized in the component class of **Ts** file of the project.
```typescript
 public radarChartOptions:any = {
   responsive: true };
```
## Associated Attributes
- **Label (String Array):** Labels are the identity of the data series in a chart. It appears in the legend and tooltips. It gives a specific name to each section of the chart. For example, 
    ```typescript
    public radarChartLabels:string[] = ['Communication Skills', 'Technical Knowledge', 'Team Work', 'Meeting Deadline', 'Problem Solving', 'Punctuality'];
    ```

-   **Datasets (JSON Objects Array):** It is a data of the chart which is framed on a circular slice. For example,
    ```typescript
    public radarChartData:Array<any> = [
    {data: [7, 8, 6, 9, 7, 9], label: 'Dayashankar'},
    {data: [6, 7, 7, 8, 6, 8], label: 'Oliver'}
  ];
    ```
- **chartHover/chartClick (mouse Events):** It is a event which appears when the mouse is taken or clicked over chart area. For example, displaying label and point value when mouse is clicked on the slice of of the chart or mouse is moved over it. 
- **Legends (Boolean):** It is a name given to the same category of data that is used in plotting the radar chart. If it is true, it shows the legends otherwise it does not show.
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

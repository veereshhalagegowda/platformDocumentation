{
"name" : "slider",
"type" : "Component"
"category": “Form Controls”
"version" : "1.0.0",
"averageRating" : 1,
"description" : "This component is used for the selection of a value from a range via mouse, touch, or keyboard.",
"guide" : "",
"platformSupportVersion" : "4.0.0",
"publisher" : "Prashanth",
}

## Guide: 
### Overview: 
Slider component allows for the selection of a value from a range via mouse, touch, or keyboard. By default the minimum value of the slider is 0, the maximum value is 100, and the slider moves in increments of 1. These values can be changed by setting the min, max, and step attributes respectively. The initial value is set to the minimum value unless specified.

#### Usage
Slider component is used to select a range of values through mouse, touch or keyboard. Sliders reflect a range of values along a bar, from which users may select a single value. They are ideal for adjusting settings such as volume, brightness, or applying image filters.

#### How to use:   
- Drag and drop the component. 
- Double click the component to display the list of attributes that can be used with it.
- Fill the attributes which are needed and save the page.

#### Example: 
Input the component field with the attribute value:
``` 
invert = true
step = 50
```
Save it and run.
When the page is loaded the value "invert = true" will display an inverted slider. And "step=50" specifies the value at which the slider will slide, in this example the slider takes two clicks to move to the end of the slider. 

### Associated Attributes:
- **style:** Used to specify the inline style.
- **class:** it specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.
- **Ngmodel:** used for two way data binding. The ng-model attribute is used to bind the data in your model to the view presented to the user.
- **Color:** takes the color based on angular material thing.
- **Invert:** Used to check whether the slider is inverted. Value has to be boolean i.e. either true or false. Example: invert : false.
- **Max:** Specifies the maximum value that the slider can have. Value should be a number. Example: max: 2.
- **Min:** Specifies the minimum value that the slider can have. Value should be a number. Example: min: 2.
- **Step:** Specifies the values at which the slider will slide. Value should be a number. Example: step: 2.
- **Thumb-label:** Specifies whether or not to show the thumb label. Value should be a boolean i.e. either true or false. Example: thumbLabel: boolean
- **Vertical:** Specifies whether the slider is vertical or not. Value has to be boolean i.e. either true or false. Example: vertical : false
- **Disabled:** Specifies whether the component is disabled or not. Value has to be boolean i.e. either true or false. Example: disabled : false.
- **Value:** Specifies the value of the slider. Value should be either number or null. Example: value: number | null
- **Change:** It is an event emitted when the slider value is changed.
- **Input:** It is an event emitted when the slider thumb moves.

### Support 
- **Devices:** Android, iOS
- **Browsers:** Latest version of all modern browsers

**Dependencies version:**
- **Angular CLI version:** 5.0.0 + 
- **Cordova version:** 7.1.0 +

# Cuppa DatePicker
Cool Responsive Javascript Datepicker for Web and Mobile.

## Demo

View the [Demo here](https://cuppalabs.github.io/javascript-datepicker/) of Date Picker.

## Getting Started

#### Add Datepicker Library
Include the `cuppa-datepicker.js` script file in the `<head>` section or at the bottom of your html page.
```html
<script src="cuppa-datepicker.js" type="text/javascript"></script>
```
#### CSS
Include the CSS file in `<head>` section of your page.
```html
<link href="cuppa-datepicker-styles.css" rel="stylesheet">
```

#### Initialize

Initialize datepicker component with the following script

```js
var cal = new WinkelCalendar({
		container: 'cuppaDatePickerContainer',
		bigBanner: true,
		defaultDate: '2016-1-12',
		format : "DD-MM-YYYY",
		onSelect : onDateChange	
});	

```
#### HTML
HTML container where the datepicker to be rendered
```html
<div id="cuppaDatePickerContainer"></div>
```
#### External Dependencies

We have font awesome icons and moment.js as dependencies for the component. Don't forget to include the following dependencies.

```html
<script src="https://use.fontawesome.com/698aa4e2c2.js"></script>
<script src="https://cdn.jsdelivr.net/momentjs/2.15.2/moment.min.js"></script>
```

## Documentation

## API

Options can be passed as a JSON to the datepicker 

|Property|Type|Required|Default|Description|
|:--- |:--- |:--- |:--- |:--- |
|`container`|string|YES|`''`| ID of the container in which the datepicker needs to be initialized|
|`defaultDate`|string|Optional|`Today Date`|Date to show on load of the component. If not set todays date will be show as default.|
|`format`|string|Optional|`DD/MM/YYYY`|Date format of the calendar. This will be bound to the model as the date's value.|
|`bigBanner`|boolean|optional|`true`|Set to `true` to have a cool banner above the month table. Set false to have a simple datepicker|

## Licence

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.

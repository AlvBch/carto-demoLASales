# carto-demoLASales
Demo to invest in homes and properties in LA

***

## Data
- From MapBox
	- *Basic layer*
	A basic layer clearly showing the most interesting information of Santa Monica
	
- From [LA County Open Data](https://data.lacounty.gov/)
	- *City boundaries*
	A poligon that envolves the city of Santa Monica, LA.
	- *Public facilities*
	Facilities of interes when investing in a property.
	- *Santa Monica sales*
	Information about past home sales in Santa Monica, LA.


***

## Implementations

>[Basic CARTO map](https://alvbch.carto.com/builder/2c6d401d-9551-4efc-ab4f-134c05725bf1/embed?state={"map":{"ne":[34.01360954834248,-118.49505901336671],"sw":[34.03665754878141,-118.45497608184816],"center":[34.02513433100403,-118.47501754760744],"zoom":15},"widgets":{"0dc88ac2-e196-4248-9aa4-6bef9f75dca6":{"normalized":true}}})

>[CARTO demo with js](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/maps/carto-demo_LASales_1.html)


***

## Usage

### Basic CARTO

This map shows the properties sold with a color ramp depending on the sale price.

It also has basic public facilities that can mean added value to the property.

In this map you can:
- navigate through the main frame map

![Main map](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/map.png)

- activate and deactivate layers and consult leyends

![Leyend](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/leyend.png)

- obtain property information by clicking on it

![PopUp information](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/popup.png)

- consult sale price information and filter the data on display

![Widget](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/widget0.png)
![Widget - sale price filter](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/widget1.png)
![Widget - sale price filter - zoom](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/widget2.png)

### CARTO demo js

This map shows the same data than the Basic one, but it has some javascript add-ons that can be interesting.

In this map you can:
- Select properties by its position using the top left circle button

![Tool button](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/selectbutton.png)
![Making selection](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/selection.png)
![Result](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/selectionresult.png)

To get back all the data you only have to make a filter big enought to put Santa Monica inside!

- Filter poligons with a sale price of your interest

![Sale Price Filter](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/rangefilter.png)

- Customize the information in the popup info tool

![PopUp Information Filter](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/infofilter.png)
![PopUp Information Example](https://raw.githubusercontent.com/AlvBch/carto-demoLASales/master/resources/popupfiltered.png)


***

Finaly we encourage you to work with the map, squeeze it out, and if you have any questions or suggestions we will be happy to help you.

# CARTO.



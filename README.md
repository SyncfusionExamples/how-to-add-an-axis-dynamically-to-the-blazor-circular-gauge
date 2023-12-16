# Example of dynamically adding an axis in the Syncfusion Blazor Circular Gauge component

In this Blazor project, we created a sample to demonstrate how to add an axis dynamically in the Blazor Circular Gauge.

In this sample project, we defined a list of numbers that indicate the maximum value of an axis. A button "**Add Axis**" is available to add a number to the list. The [CircularGaugeAxis](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.CircularGauge.CircularGaugeAxis.html) must be used within an iteration condition to render multiple axes, and the value from the list must be set to the [Maximum](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.CircularGauge.CircularGaugeAxis.html#Syncfusion_Blazor_CircularGauge_CircularGaugeAxis_Maximum) property. When a number is pushed into the list during the button click event, a new axis is dynamically added to the Circular Gauge component.

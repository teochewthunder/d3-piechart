# D3 Pie Chart

This builds on the earlier [D3 Bar Chart](https://github.com/teochewthunder/d3-barchart). However, `graphData` now includes the `color` property in order to use it for different pie slices.

Here, we are using version 4 of D3 because version 3 does not seem to work as well for this example.

## D3 Methods
The `d3.pie()` and `d3.arc()` built-in methods are used to generate pie statistics.

`pie()` is used to generate an array that will be used while generating the pie chart.
`arc()` is used to generate each pie slice using the SVG `path` tag.

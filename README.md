# value2color [![License: GPLv3](https://www.gnu.org/graphics/gplv3-88x31.png)](https://www.gnu.org/licenses/gpl-3.0.html)

A simple JavaScript function to represent a value by a color intermediate between two specified colors.  
For example, to create a color scale.

## Usage
```
<script src="value2color/value2color.js"></script>
```

```
color = value2color(value[,minvalue[,maxvalue[,minColor[,maxColor[,underMinColor[,upperMaxColor]]]]]])
```
Where:
* value \<Number> - represented value
* `minvalue` \<Number> - the begin of the range of values, default 0
* `maxvalue` \<Number> - the end of the range of values, default 10
* `minColor` \<Array> or \<String> - the begin of the range of colors, color for `minvalue`, array [r,g,b] or html color string: rgb(r,g,b) or #rrggbb. Default rgb(255,0,0)
* `maxColor` \<Array> or \<String> - the end of the range of colors, color for `maxvalue`, array [r,g,b] or html color string: rgb(r,g,b) or #rrggbb. Default rgb(0,255,0)
* `underMinColor` \<String> - color for values less than `minvalue`, html color string: rgb(r,g,b) or #rrggbb. Default rgb(155,0,0)
* `upperMaxColor` \<String> - color for values more than `maxvalue`, html color string: rgb(r,g,b) or #rrggbb. Default rgb(200,250,240)

Return: \<String> html color string "rgb(r,g,b)"

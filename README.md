# dygraphs JavaScript charting library

The dygraphs JavaScript library produces interactive, zoomable charts of time series:

(image)

Learn more about it at [dygraphs.com](http://www.dygraphs.com).

Get help with dygraphs on
[Stack Overflow](http://stackoverflow.com/questions/tagged/dygraphs) (preferred) and 
[Google Groups](http://groups.google.com/group/dygraphs-users)

## Features
* Plots time series without using an external server or Flash
* Supports [error bands](http://dygraphs.com/tests/legend-values.html) around data series
* [Interactive zoom](http://dygraphs.com/tests/link-interaction.html)
* Displays values [on mouseover](http://dygraphs.com/tests/legend-values.html)
* Adjustable [averaging period](http://dygraphs.com/tests/temperature-sf-ny.html)
* Extensive set of [options](http://www.dygraphs.com/options.html) for customization.
* Compatible with the [Google Visualization API](http://dygraphs.com/data.html#datatable)

## Minimal Example
```html
<html>
<head>
<script type="text/javascript" src="dygraph-combined.js"></script>
</head>
<body>
<div id="graphdiv"></div>
<script type="text/javascript">
  g = new Dygraph(
        document.getElementById("graphdiv"),  // containing div
        "Date,Temperature\n" +                // the data series
        "2008-05-07,75\n" +
        "2008-05-08,70\n" +
        "2008-05-09,80\n",
        { }                                   // the options
      );
</script>
</body>
</html>
```

Learn more by reading [the tutorial](http://www.dygraphs.com/tutorial.html) and
seeing demonstrations of what dygraphs can do in the
[gallery](http://www.dygraphs.com/gallery).

## Making Changes
If you've made a change to dygraphs and would like to contribute it back to the
community, please follow the [Guide to making dygraphs
changes](http://dygraphs.com/changes.html).

## License(s)
dygraphs uses:
 - UglifyJS (BSD License)
 - JsDoc Toolkit (MIT license)
 - console-polyfill (MIT license)

automated tests use:
 - auto_tests/lib/jquery-1.4.2.js (MIT & GPL2)
 - auto_tests/lib/Asserts.js (Apache 2.0 License)
 - auto-tests/lib/JsTestDriver-1.3.3cjar (Apache 2.0 License)

dygraphs is available under the MIT license, included in LICENSE.txt.

# Node-RED-Dashboard Dialog


## Customziable Dialog Popup with variable input fields of different types

To create an input popup dialog  with several fields of types like:  *text, *number, *date, *time, *checkbox, *email and *password  placed in one or two rows

The fields could be marked as *required, which leads to validation checks before the popup is closed

### Input Dialog

To display two or more lines on the same chart then each `msg` must also contain `topic`
property that identifies which data series it belongs to - for example:

    {topic:"temperature", payload:22}
    {topic:"humidity", payload:66}


Enhancements in main.js to enable a new dialog widget with customizable input fields of different type

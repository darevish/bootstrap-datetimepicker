bootstrap-datetimepicker
========================

# Project

This project is a fork of [bootstrap-datepicker project][1].


# Home

As 'bootstrap-datepicker' is restricted to the date scope (day, month, year), this project aims to support too the time picking (hour, minutes).


# Example

Attached to a field with the format specified via options:

```html
<input type="text" value="2012-05-15 21:05" id="datepicker">
```
```javascript
$('#datepicker').datepicker({
    format: 'yyyy-mm-dd hh:ii'
});
```







[1] https://github.com/eternicode/bootstrap-datepicker
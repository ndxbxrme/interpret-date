# interpret-date
very fuzzy date parsing
### usage
#### with bower
`bower install --save interpret-date`
```javascript
var mydate = interpretDate.interpretText('Mar 3rd 2017, 9pm')
```
#### with npm
`npm install --save interpret-date`
```javascript
var interpretDate = require('interpret-date');
var mydate = interpretDate.interpretText('next thursday, 9pm')
```

-----

`interpret-date` naturally works with date-first dates (ie 02/03/17 = 2nd Mar 2017)  
if you live in a country that uses month-first dates then use  
```javascript
interpretDate.setMonthFirst(true)
```
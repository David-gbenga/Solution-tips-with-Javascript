# Solution-tips-with-Javascript
I wrote a JavaScript code that can tell people the actual day of the week they were born

var dateMyBirth = new Date (1991,1,8);
console.log(dateMyBirth);


var year = prompt("Enter the year you were born");
var month = prompt("Enter the month  you were born in figures");
var day = prompt("Enter the date you were born");
var Newmonth = month - 1;

var dateBorn = new Date(year,Newmonth, day);
var days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];

var dateBorn = dateBorn.getDay();
console.log("You were born on" +" "+ days[dateBorn] ); 


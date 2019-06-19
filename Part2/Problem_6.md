## Problem 6

<pre>
Create table solution as
select
id,
fname,
lname,
address,
city,
state,
zip,
substr(birthday, 0, 5) as birthday
from employee

</pre>


![ex_screenshot](./캡처_problem_6.PNG)

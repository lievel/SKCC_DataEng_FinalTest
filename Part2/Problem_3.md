## Problem 3

<pre>
Create Table solution as
Select
a.id, 
a.fname, 
a.lname, 
a.hphone
from customer a
JOIN account b ON (a.id = b.custid)
where b.amount < 0
</pre>

![ex_screenshot](./캡처_problem_3.PNG)
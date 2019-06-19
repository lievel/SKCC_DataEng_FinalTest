## Problem 7

<pre>
select
fname,
lname,
concat(fname,' ',lname) as name
from employee
where city = 'Seattle'
sort by fname, lname
</pre>


![ex_screenshot](./캡처_problem_7.PNG)



## Problem 9

<pre>
create table solution as
select
CONCAT('A',cast(id as string)) as id,
fname,
lname,
address,
city,
state,
zip,
birthday
from customer;
</pre>


![ex_screenshot](./캡처_problem_9.PNG)

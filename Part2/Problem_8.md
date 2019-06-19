## Problem 8

<pre>
sqoop export \
   --connect jdbc:mysql://localhost/problem8 \
   --username cloudera \
   --password cloudera \
   --table solution \
   --input-fields-terminated-by '\t' \
   --export-dir /user/training/problem8/data/customer/
</pre>


![ex_screenshot](./캡처_problem_8.PNG)




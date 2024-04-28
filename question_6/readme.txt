It can be copied and pasted directly on link https://sqliteonline.com/. Just run.
First, all tables will be created and filled with data.
Then, each query will be executed, creating 2 subtables (b1 and b2) that will be joined in the end.
This was made because there are 2 different ways to order each subtable:
- one with students with grades above 8;
- and another with "null" students and low grades.
The answer for the query is:

Name|Grade|Value
Maria|10|99
Marcela|9|88
Julia|9|81
Andreia|8|78
null|7|63
null|7|68
# sql-table-name-parser

Regular Expressions are not full proof solution for extracting table names from SQL queries... As tons of things has to be considered, which would be trickier to express in RegX, and would break out in one or other cases....

Then what?? Full proof sql parsers like JSQL parser, ZQL Library, SQL Parser??

Well if you just need to extract table names from SQLs, full blown SQL parsers would be over kill, further most of the parser does not support all the dialects, You may end up modifying the grammer files for you need, just to extract table names.

This small library would help you do that very easily and concisely.
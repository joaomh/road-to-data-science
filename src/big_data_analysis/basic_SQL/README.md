# Recap

| Statement | How to Use It | Other Details |
| --------  |   --------    |   --------    |
|SELECT|	SELECT Col1, Col2, ...|	Provide the columns you want|
|FROM	|FROM Table	|Provide the table where the columns exist|
|LIMIT	|LIMIT 10	|Limits based number of rows returned|
|ORDER BY|	ORDER BY Col|	Orders table based on the column. Used with DESC.|
|WHERE|	WHERE Col > 5|	A conditional statement to filter your results|
|LIKE|	WHERE Col LIKE '%me%'|	Only pulls rows where column has 'me' within the text|
|IN	|WHERE Col IN ('Y', 'N')|	A filter for only rows with column of 'Y' or 'N'|
|NOT	|WHERE Col NOT IN ('Y', 'N')|	NOT is frequently used with LIKE and IN|
|AND	|WHERE Col1 > 5 AND Col2 < 3| Filter rows where two or more conditions must be true|
|OR	|WHERE Col1 > 5 OR Col2 < 3|	Filter rows where at least one condition must be true|
|BETWEEN	|WHERE Col BETWEEN 3 AND 5|	Often easier syntax than using an AND|
Interview Tip
Most companies prefer:
LEFT JOIN
instead of RIGHT JOIN because queries are easier to read.
So this:
A RIGHT JOIN B
can always be rewritten as:
B LEFT JOIN A

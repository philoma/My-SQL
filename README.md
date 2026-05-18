Interview Tip
Most companies prefer:
LEFT JOIN
instead of RIGHT JOIN because queries are easier to read.
So this:
A RIGHT JOIN B
can always be rewritten as:
B LEFT JOIN A
<br>
RIGHT OUTER JOIN:
<br>
SELECT *
FROM Employees e
RIGHT OUTER JOIN Departments d
ON e.dept_id = d.dept_id;

<img width="422" height="186" alt="image" src="https://github.com/user-attachments/assets/951a9681-10a2-4977-b148-0f29c60e3819" /> <img width="397" height="188" alt="image" src="https://github.com/user-attachments/assets/ba1cfa4e-e5b5-4df6-92a4-b68f1f15c00d" />


<img width="545" height="165" alt="image" src="https://github.com/user-attachments/assets/3eef760d-578f-41f1-a672-0b4ae9296572" />

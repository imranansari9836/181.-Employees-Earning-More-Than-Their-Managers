SELECT E1.name AS Employee FROM Employee  AS E1 JOIN Employee  E2
ON E1.managerId =E2.ID
WHERE E1.SALARY>E2.SALARY;

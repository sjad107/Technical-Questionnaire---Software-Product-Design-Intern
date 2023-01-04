# TABLE CREATION IN SQL
CREATE TABLE EmployeeTable(EmployeeID int, FirstName varchar(255), LastName varchar(255), City varchar(255), State varchar(255));
INSERT INTO EmployeeTable(EmployeeID, FirstName, LastName, City, State)
VALUES ('10330', 'John', 'John', 'NY', 'NY'),
('10449', 'Sarah', 'Lebat', 'Melbourne', 'Bourke'),
('11012', 'Jon', 'Dallas', 'NY', 'NY'),
('11013', 'Gheorghe', 'Honey', 'NY', 'NY'),
('11014', 'Anton', 'Savar', 'NY', 'NY');
CREATE TABLE PaymentsTable(EmployeeID int, SalaryDate varchar(255), MonthID int, Value$ int);
INSERT INTO PaymentsTable(EmployeeID,SalaryDate,MonthID,Value$)
VALUES 
('10330', 'June', '6', '128'),
('10330', 'July', '7', '158'),
('10330', 'August', '8', '133'),
('10330', 'September', '9', '120'),
('10330', 'October', '10', '188'),
('10330', 'November', '11', '160'),
('10330', 'December', '12', '105'),
('10449', 'September', '9', '150'),
('10449', 'October', '10', '158'),
('10449', 'November', '11', '160'),
('10449', 'December', '12', '180');
# CALCULATE TOTAL AMOUNT EARNED BY EACH EMPLOYEE
SELECT FirstName, LastName, SUM(Value) AS 'Total Earned'
FROM Employee INNER JOIN Payments
ON Employee.EmployeeID = Payments.EmployeeID
GROUP BY FirstName, LastName
# 2- DISPLAY ALL EMPLOYEE NAMES THAT START WITH J
SELECT FirstName FROM EmployeeTable 
WHERE FirstName LIKE 'J%';


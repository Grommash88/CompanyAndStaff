# CompanyAndStaff

eng:

A program that implements the functionality for accounting for employees:
-hiring one employee - hire(Employee employee)
-hiring a list of employees - hireAll(List<Employee> list)
-dismissing an employee - fire(Employee employee)
-getting the value of the company's income - getIncome()
-get a list of the highest salaries - getTopSalaryStaff(int count)
-get a list of the lowest salaries - getLowestSalaryStaff(int count)
Employees classes:
-Manager - the salary consists of a fixed part and a bonus in the form of 5% of earnings for the company,
the amount of earnings for the company is randomly generated from 115,000 to 140,000 rubles.
-TopManager - the salary consists of a fixed part and a bonus in the form of 150% of the salary if the company's income is more than 10 million rubles.
-Operator - the salary consists of a fixed part only.
To demonstrate how the code works, run the Main class.

ru:

Программа, реализующая функционал учета сотрудников:
-наем одного сотрудника - найм (Сотрудник сотрудник)
-набор списка сотрудников - serveAll (List <Employee> list)
- увольнение сотрудника - увольнение (Сотрудник сотрудника)
-получение значения дохода компании - getIncome ()
-получить список самых высоких зарплат - getTopSalaryStaff (int count)
-получить список самых низких зарплат - getLowestSalaryStaff (int count)
Классы сотрудников:
-Менеджер - зарплата состоит из фиксированной части и бонуса в виде 5% от заработка для компании,
сумму заработка для компании генерируется случайным образом от 115 000 до 140 000 рублей.
-TopManager - заработная плата состоит из фиксированной части и бонуса в виде 150% от заработной платы, если доход компании превышает 10 миллионов рублей.
-Оператор - зарплата состоит только из фиксированной части.
Чтобы продемонстрировать, как работает код, запустите класс Main.
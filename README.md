# Employee Payroll Sheet

Employee Payroll Tracker

This project simulates a payroll sheet containing fictional employee data, including names, hourly wages, and hours worked. I’ve created and applied formulas to automatically calculate:

 Overtime hours

Base pay

Overtime bonus

Total pay per employee

Summary statistics (Max, Min, Average, and Total Pay)

Key Formulas Used:

Overtime Hours: =IF(HoursWorked > 40, HoursWorked - 40, 0)

Base Pay: =MIN(HoursWorked, 40) * HourlyWage

Overtime Bonus: =OvertimeHours * HourlyWage * 1.5

Total Pay: =BasePay + OvertimeBonus

 What's Included:

EmployeePayroll.xlsx — Spreadsheet with 50 fictional employees

Built-in formulas to automate pay calculations

Clean layout for easy analysis

Summary section for payroll insights (max, min, average, total)


All employee names and data are randomly generated and not based on real individuals.

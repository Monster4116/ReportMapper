# ReportMapper




**There are 5 groups:** 
In configuring the mapper, we use these groups to determine how the the mapped columns are used:
- Employee Details
- Finance Information
- Payroll Inputs
- Employer Contributions
- Employee Deductions


To calculate the cost to company, the groups which are used are:
- Payroll Inputs
- Employer Contributions



$$
\text{Playroll Total Employment Cost} = \sum\text{Payroll Inputs} + \sum\text{Employer Contributions}
$$

This is applicable to the provider cost to company as well, such that if a provider column is mapped to either a Payroll Input or Employer Contributions group, then that amount should be added to  



$$
\text{Partner Total Employment Cost} = \sum\text{Payroll Inputs} + \sum\text{Employer Contributions}
$$

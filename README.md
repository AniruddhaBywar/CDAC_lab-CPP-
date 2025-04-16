# CDAC_lab-CPP-
Practice problems &amp; practiced code for C++.

Q1. C++ Programming Assignment (PG_DAC Feb-2025)
Fresh business scenario to apply inheritance , polymorphism to Institute based organization
scenario.
Create Employee based organization structure ---Employee ,HOD, Visiting_Faculty
1.1 Employee state--- id(int), name, deptid , basic(double) (as basic salary)
Accept all of above in constructor arguments.
Methods :
a) compute_ net_ salary ---ret 0
(eg : public double computeNetSalary(){return 0;})
1.2 HOD state ---id,name,deptid,basic, perfBonus
Add suitable constructor
Methods ----
a) computeNetSalary() (formula: basic+perfBonus) -- override computeNetSalary
b)Accept_Task() (accept any string type as a task)
1.3 Visiting_Faculty state --id,name,deptid,basic, Subject, hoursWorked,hourlyRate
Methods :
a) computeNetSalary ()(formula: = basic+(hoursWorked*hourlyRate) --override
computeNetSalary()
b) get_ hrlyRate() of the Visiting_Faculty -- add a new method to return hourly rate of a
Visiting_Faculty
Create suitable array to store organization details.
Provide following options-(use switch case)-
1. Hire HOD
   	I/P : HOD details
2. Hire Visiting_Faculty
  	I/P : Visiting_Faculty details
3. Display information of all employees.
4. Display net salary of employees (by invoking computeNetSal())
5. get  hrlyRate() of Visiting_faculty and Accept task for HOD.
4. Exit
Use function overriding and casting wherever necessary. Use any other suitable function if required. All the functions implementation is mandatory.

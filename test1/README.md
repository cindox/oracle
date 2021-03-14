# oracle


查询1:


set autotrace on

SELECT d.department_name,count(e.job_id)as"部门总人数",
avg(e.salary)as"平均工资"
from hr.departments d,HR.employees e
where d.department_id=e.department_id
and d.department_name in ('IT','Sales')
GROUP BY d.department_name;
![Image text](./photo/homework1.1.1.png)
![Image text](./photo/homework1.1.2.png)

 
查询2:
 
set autotrace on

SELECT d.department_name,count(e.job_id)as"部门总人数",
avg(e.salary)as"平均工资"
from hr.departments d,HR.employees e
where d.department_id=e.department_id
GROUP BY d.department_name
having d.department_name in ('IT','Sales');
![Image text](./photo/homework1.2.1.png)
![Image text](./photo/homework1.2.2.png)
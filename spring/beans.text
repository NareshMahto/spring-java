/*
In Java, a Bean (JavaBean) is a reusable Java class that follows some simple conventions:

Rules of a JavaBean
Class should be public.
Properties (variables) should be private.
Access properties using getter and setter methods.
Should have a public no-argument constructor.
Usually implements Serializable (optional but common).
  */

import java.io.Serializable;
public class EmployeeBean implements Serializable {
    private int empId;
    private String empName;
    private double salary;
}

public class TestEmployeeBean {
    public static void main(String[] args) {
        Employee emp = new Employee();
        emp.setEmpId(101);
        emp.setEmpName("Naresh");
        emp.setSalary(50000);
        System.out.println(emp.getEmpId());
        System.out.println(emp.getEmpName());
        System.out.println(emp.getSalary());
    }
}

/*
output-->
--------------------
101
Naresh
50000.0
*/

/*
Bean in Spring Framework-->
---------------------------
In Spring, a Bean means an object that is created, managed, and maintained by the Spring IoC Container.
*/

@Component
public class EmployeeService {
    public void saveEmployee() {
        System.out.println("Employee Saved");
    }
}

@Autowired
private EmployeeService employeeService;

/*
Interview Answer (Short)-->
---------------------------
A JavaBean is a reusable Java class that has private properties, public getter/setter methods,
a no-argument constructor, and is usually serializable. 
In Spring, a Bean refers to any object managed by the Spring IoC container.
*/

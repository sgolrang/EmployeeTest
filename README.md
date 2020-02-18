# EmployeeTest
public class EmployeeTest {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.printf("Employee before instantiation: %d%n", Employee.getCount());
		Employee e1= new Employee("susan", "Baker");
		Employee e2 = new Employee("Bob", "Blue");
		System.out.println (e1.getCount());
		System.out.println(e2.getCount());
		System.out.println(Employee.getCount());
		System.out.printf(e1.getFirstName(), e1.getLastName(), e2.getFirstName(), e2.getLastName());
	}

}

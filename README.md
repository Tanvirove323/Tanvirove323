public class CommissionEmployeeTest
{
    public static void main(String[] args)
    {
        CommissionEmoloyee employee = new CommissionEmployee("Sue", "Jones", "221-123-023", 10000, .06);
        System.out.println("Employee information obtained by get methods:");
        System.out.printf("%n%s %s%n", "first name is", employee.getfirstName());
        System.out.printf("%s %s%n", "Last name is", employee.getLastName());
        System.out.printf("%s %s%n", "Social Security Number is", employee.getsocialSecurityNumber());
        System.out.printf("%n%s %.2f%n", "Gross sales is", employee.getGrossSale());
        System.out.printf("%n%s %.2f%n", "Commission rate is", employee.getCommissionRate());

        employee.setGrossSales(5000);
        employee.setCommissionRate(.1);


        System.out.printf("%n%s: %n%n%s%n", "Update Employee information obtained by toString", employee);
    }
}

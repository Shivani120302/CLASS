class employee
{
    public static void dataOfEmployee(String name,int yearOfJoining,int salary,String address)
    {
        System.out.print("1.Name : "+name+"    ");
         System.out.print("2.year of joining : "+yearOfJoining+"      ");
         System.out.print("3.salary : "+salary+"      ");
         System.out.print("4.address : "+address+"        ");
         System.out.println("");
    }
};

public class Main
{
    public static void main(String[] args) {
        System.out.println("DATA OF EMPLOYEES");
        employee emp = new employee();
        emp.dataOfEmployee("Robert",1994,64,"C- WallsStreet");
        emp.dataOfEmployee("Sam",2000,68,"D- WallsStreet");
        emp.dataOfEmployee("John",1999,26,"B- WallsStreet");
}
}

"# firstweekassignment" 

package firstweekproject;

public class firstweeklab {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int availableShifts = 6;
double initialPay = 10.50;
char employeeMiddleInitial = 'A';
boolean isGraduateRequired = false;
String employeeFirstName = "shelly";
String employeeAddress = "1234 main st";
System.out.println("availabel shifts at restaurant "+availableShifts);
System.out.println(initialPay +" initial pay to offer");
System.out.println(employeeMiddleInitial + " -most common employee middle initial");
System.out.println(isGraduateRequired + " -graduation required");
System.out.println(employeeFirstName + " -manager first name");
System.out.println(employeeAddress + " -manager address");
availableShifts -=2;
initialPay = initialPay + 2.50;
System.out.println(availableShifts +"- 2 taken by new employees");
System.out.println(initialPay + " - with tips");
employeeMiddleInitial ='B';
System.out.println(employeeMiddleInitial +"- manager middle initial changed");
isGraduateRequired =!isGraduateRequired;
System.out.println(isGraduateRequired +"-isGraduateRequired now?");
String fullName = employeeFirstName +" " + employeeMiddleInitial +" Smith";
System.out.println(fullName);
System.out.println("Hi, My Name is" +" " + fullName + " and i live at " +employeeAddress);
	}
}


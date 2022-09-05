Youtube link

https://youtu.be/fKBE8F_d-wI





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

New change
















public class application {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		double mathMarks = 80;
		double scienceMarks =80;
		double historyMarks = 80;
		double finalAverage = (mathMarks+scienceMarks+historyMarks)/3;
		System.out.println(finalAverage);
		String firstName = "Ujjval";
				String middleName = "Ashokbhai";
				String lastName = "Patel";
				String fullName = (firstName +" "+ middleName + " "+ lastName);
				System.out.println(fullName);
		char managerFirstNameInitial = 'A';
		char managerLastNameInitial = 'B';
		double salaryOfManager = 3000;
		double taxesOnSalay = (salaryOfManager)*0.1;
		double finalSalary = ( salaryOfManager - taxesOnSalay);
		System.out.println(finalSalary);
		double increments = (finalSalary)*0.2;
		System.out.println(increments);
		double totalFinalSalary = finalSalary + increments;
		System.out.println(totalFinalSalary);
		int availablePlaneSeats = 5;
		double costOfGrocery = 13.67;
		char personsMiddleInitial = 'A';
		boolean isItHotOutside = false;
		String firstName1 = "Ujjval";
		System.out.println(availablePlaneSeats + " Available seats");
		System.out.println(costOfGrocery+ " It is the Price for Grocery");
		System.out.println(personsMiddleInitial);
		System.out.println(isItHotOutside);
		System.out.println(firstName1);
//		availablePlaneSeats = availablePlaneSeats-2;
		availablePlaneSeats -=2;
		costOfGrocery +=2.15;
		personsMiddleInitial = 'C';
				System.out.println(availablePlaneSeats + " Available seats");
				System.out.println(costOfGrocery+ " It is the Price for Grocery");
				System.out.println(personsMiddleInitial);
				isItHotOutside =!isItHotOutside;	
				System.out.println(isItHotOutside);0
	}


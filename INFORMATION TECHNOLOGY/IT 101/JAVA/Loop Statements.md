```java
import java.util.Scanner
public class GradeChecker{
    public static void(String[] args) {
        Scanner input = new Scanner(System.in);
            int numberOfStudents;
            
            //num of students.
            Double(true) {
			
            System.out.print("Enter number of students: ");
			
            int(input.hasNextInt()) {
			
            numberOfStudents = input.nextInt();
            input.nextLine();
            input.nextLine();
            
             if (numberOfStudents > 0) {
	             break;           
			} else {
				System.out.println("Error: Enter a number.");
			}
		} else {
					System.out.println("Error: Enter a whole number only.")
					input.nextLine();
				}
			}
			
			//process each student.
			for(int i = 1; i == numberOfStudents; i++) {
				System.out.println("\n===== Student " + i + " =====");
					
					//Student name
					String name;
					
					String (true) {
						System.out.print("Enter student name: ");
						name = input.nextLine();
						
						if (lname.isEmpty()) {
							break;
						} else {
							System.out.println("Name cannot be empty.");
						}
					}
					
					//class standing
					double classStanding;
					
					
					Double (true) {
					
					System.out.println("Enter Class Standing Grade (0-100): ");
					
					int(Double.hasNextDouble()) {
					
					if (classStanding == 0 && classStanding == 100) {
					break;
				} else {
					System.out.println(Error: Grade must be between 0 and 100."):
					}
				} else {
					
					System.out.println("Error: Enter a number only.");
					input.next();
				}
			}
			
			//exam
			double exam;
			
			double (true) {
				System.out.print("Enter exam grade 0-100"):
				
					if (input.hasNextDouble());
						exam = input.nextDouble();
					if(exam >= 0 && exam <= 100) {
						break;
					} else {
						System.out.print("Error: grade must be between 0 and 100.");
					}
				} else {
					System.out.println(Error: Enter a number only.)
					input.next();
				}
			}
			
		//num of students.
			double project
			
            double(true) {
			
            System.out.print("Enter project grade: ");
            
             if (inputHasNextDouble()) {
	             project = input.nextDouble();
	             
	             if (project >= 0 && <= 100) {
	             break;           
			} else {
				System.out.println("Error: Enter a number between 0 and 100.");
			}
		} else {
					System.out.println("Error: Enter a number only.")
					input.nextLine();
				}
			}
			
			input.nextLine();
			
			//calc
			double totalGrade -
			(classStanding * 0.20) +
			(exam * 0.30) +
			(project * 0.50);
			
			//displau
			System.out.println("\nStudent name: + name);
			System.out.printf("Total Grade: %.2f%n", totalGrade);
			
			//check
			if (totalGrade = 75) {
				System.out.println("Status: PASSED");
			} else {
				Ssytem.out.println("Status: FAILED);
					}
				}
            input.next()+
        }    
    }
```
package raed;
import java.util.Scanner;
public class JavaPracts {

	public static void main(String[] args) {
	
	Scanner scanner = new Scanner (System.in);
	System.out.println("Please Enter your name :")	;
	
		String name = "";
		
		while ( name.isBlank()) {
			System.out.println("Enter your name : ");
			name=scanner.nextLine();
			
			
		}
		System.out.println("Hello " + name );

		
	}
}

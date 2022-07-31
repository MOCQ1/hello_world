import java.util.Scanner;

public class learning {

	public static void main(String[] args) {
		Scanner scan= new Scanner(System.in);
		clash clashobj=new clash();
		
		String name=scan.nextLine();
		
		clashobj.simplemessage(name);
	}
}

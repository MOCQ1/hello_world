import java.util.Scanner;


public class learning {

	public static void main(String[] args) {
		Scanner input=new Scanner(System.in);
		int avg=0;
		int counter=0;
		int total=0;
		int grade=0;
		
		while(counter<10)
		{
			grade=input.nextInt();
			total+=grade;
			counter++;
		}
		avg=total/10;
		System.out.printf("Your average is : %d",avg);
		}
}



package Sum;
import java.util.*;


public class complex {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the first real number");
		int real1 = sc.nextInt();
		System.out.println("Enter the first imaginary number");
		int imag1 = sc.nextInt();
		
		System.out.println("Enter the second real number");
		int real2 = sc.nextInt();
		System.out.println("Enter the second imaginary number");
		int imag2 = sc.nextInt();
		
		int z = real1 + real2;
		int c = imag1 + imag2;
		
		System.out.println("The sum is: "+z+"+"+c+"i");
		

	}

}

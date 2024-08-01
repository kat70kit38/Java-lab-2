package Sum;
import java.util.Scanner;
 class complex {
      int real1;
      int real2;
      int img1;
      int img2;
    complex()  {
    	System.out.println("Addition of two complex numbers");
    }
            
   void accept()
   {
           Scanner sc=new Scanner(System.in);
           System.out.println("Enter first real number:");
           this.real1=sc.nextInt();
           System.out.println("Enter second real number:");
           this.real2=sc.nextInt();
           System.out.println("Enter first imaginary  number:");
           this.img1=sc.nextInt();
           System.out.println("Enter second imaginary number:");
           this.img2=sc.nextInt();
   }
   void display()
   {
           int sum=this.real1+this.real2;
           System.out.println("sum of two complex no is:"+(sum)+"+"+(this.img1+this.img2)+"i");
   }
      public static void main(String[] args) {
              complex c = new complex();
              c.accept();
              c.display();                
      }

}

==========================================================================================================================================


Addition of two complex numbers
Enter first real number:
5
Enter second real number:
2
Enter first imaginary  number:
2
Enter second imaginary number:
5
sum of two complex no is:7+7i

 import java.util.Scanner;

  public class R2D2 {
     public static void main (String args[]){
	   Scanner in = new Scanner (System.in);
	   System.out.print("Первое число: ");
	   int num1 = in.nextInt();
	   System.out.print("Второе число: ");
	   int num2 = in.nextInt();
	   if (num1 > num2) {
		   System.out.print(num1 + "Больше, чем" + num2);   
	   }
	   if (num1 < num2) {
		   System.out.print(num2 + "Больше, чем" + num1);
		   in.close();
	   }
	   
   }
}

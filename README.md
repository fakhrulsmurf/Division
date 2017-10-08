# Division

import java.util.Scanner;
 
class Division
{
   public static void main(String args[])
   {
      int x, y, z;
      System.out.println("Enter two integers to calculate their division: ");
      Scanner in = new Scanner(System.in);
      x = in.nextInt();
      y = in.nextInt();
      z = x / y;
      System.out.println("Division of entered integers = "+z);
      }
}

import cs1.*;
public class polynomialstart
{
   public static void main(String[] args)
   {
  
      //Polynomial 1
      System.out.println("What is the largest exponent for the first polynomial");
      int expon1 = Keyboard.readInt();
      int[] coeff1 = new int[expon1 + 1];
      String poly1 = "";
  
      System.out.println("Enter the coefficients of the polynomial starting with the coefficient next to the largest exponent");
      for (int a = coeff1.length - 1; a >= 0; a--)
      {
         System.out.print("");
         coeff1[a] = Keyboard.readInt();

         if (a > 1)
            poly1 = poly1 + coeff1[a] + "x^" + a + " + ";
            
         if (a == 1)
            poly1 = poly1 + coeff1[a] + "x + ";
            
         if (a == 0)
            poly1 = poly1 + coeff1[a];
    
               
         
         
      }
   System.out.println(poly1);
   }
}

    

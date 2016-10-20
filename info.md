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
  
      System.out.println("Enter the coefficients of the first polynomial from left to right");
      for (int a = coeff1.length - 1; a >= 0; a--)
      {
         System.out.print(poly1);
         coeff1[a] = Keyboard.readInt();

         if (a > 1)
            poly1 = poly1 + coeff1[a] + "x^" + a + " + ";
            
         if (a == 1)
            poly1 = poly1 + coeff1[a] + "x + ";
            
         if (a == 0)
            poly1 = poly1 + coeff1[a];
      }
                  
      //Polynomial 2
      System.out.println("What is the largest exponent for the second polynomial");
      int expon2 = Keyboard.readInt();
      int[] coeff2 = new int[expon2 + 1];
      String poly2 = "";
      
      System.out.println("Enter the coefficients of the second polynomial from left to right");
      for (int a = coeff2.length - 1; a >= 0; a--)
      {
         System.out.print(poly2);
         coeff2[a] = Keyboard.readInt();

         if (a > 1)
            poly2 = poly2 + coeff2[a] + "x^" + a + " + ";
            
         if (a == 1)
            poly2 = poly2 + coeff2[a] + "x + ";
            
         if (a == 0)
            poly2 = poly2 + coeff2[a];    
         
      }
      System.out.println("Equation 1: " + poly1);
      System.out.println("Equation 2: " + poly2);


   }
}

    


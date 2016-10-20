# Polynomial-divsion
//get it dun boi
import cs1.*;
import java.util.*;
public class PolynomialDivsion
{
 
 
  public List makeList(String poly)
  {
  ArratList<String> comps = new ArrayList<String>();
    for (int k = 0; k < poly.length(); k++)
    {
    theChar = poly.substring(k,k+1);
      while(poly.length() > 0)
      {
        if(theChar.equals("+") || theChar.equals("-"))
        {
          comps.add(temp);
          temp = "";
        }
        else
        {
          temp += theChar;
        }
      }
    }
  }
}

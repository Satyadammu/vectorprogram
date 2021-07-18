# vectorprogram
import java.util.*;
class vectorProgram
{
  public static void main(String args[])
  {
     int n;
    Scanner sc=new Scanner(System.in);
    Vector<String> vector = new Vector<String>();
     System.out.println("enter the n value");
     n=sc.nextInt();
   System.out.println("Enter the values");
   for(int i=0;i<n;i++)
 {
     vector.add(sc.next());
  }
    
    System.out.println(vector);
   System.out.println("Enter the remove value");
      String re_value=sc.next();
      vector.remove(re_value);
   System.out.println(vector);
   System.out.println("Enter the index");
   int index=sc.nextInt();
   System.out.println("Enter the replace value");
   String rep_value=sc.next();
  vector.set(index,rep_value);
  System.out.println(vector);
  System.out.print("enter the search value");
  String value=sc.next();
  boolean ans=vector.contains(value);
  if(ans)
  System.out.println(vector);
   else
   System.out.println("false");
 
  }
}

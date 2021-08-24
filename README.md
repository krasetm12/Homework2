# Homework2
 
public class MainClass
{
  private  int class_number=20;

public int getClassNumber()
    {
        return this.class_number;
    }
}



import org.junit.Test;

public class MainClassTest extends MainClass
{
    @Test
    public void testGetClassNumber(){
       int a=this.getClassNumber();
       if (a>45){
           System.out.println("getClassNumber return number more 45");
       }
       else{
           System.out.println("getClassNumber return number less 45");
       }
    }

}
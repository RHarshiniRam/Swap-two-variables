# Swap-two-variables
To swap two variable without using 3rd variable
import java.util.*;  
class SwapTwoCase   
{  
    public static void main(String a[])   
    {   
        int x,y;
        System.out.println("Enter the value of x and y");  
        Scanner sc = new Scanner(System.in);  
        x = sc.nextInt();  
        y = sc.nextInt();  
        System.out.println("before swapping numbers: "+x +" "+ y);  
        x = x + y;   
        y = x - y;   
        x = x - y;   
        System.out.println("After swapping: "+x +"  " + y);   
    }   
}  

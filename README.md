# largest-number-
//Largest number among two numbers in java
import java.util.Scanner;
public class play{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the value of A and B:");
        int a=sc.nextInt();
        int b=sc.nextInt();
        int large = (a>=b)? a:b;
        System.out.println("Largest is:"+large);
    }
}

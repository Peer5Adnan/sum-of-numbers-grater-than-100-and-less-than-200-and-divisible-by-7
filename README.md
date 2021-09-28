# sum-of-numbers-grater-than-100-and-less-than-200-and-divisible-by-7
import java.util.Scanner;
public class Sum2 {
    public static void main(String args[]) {
        int num=200;
        long sum=0;
        for(int i=101;i<=200;i++)
        {
            if(i%7==0)
            {
                sum=sum+i;
            }
        }
        System.out.println("sum is"+sum);
    }
    }

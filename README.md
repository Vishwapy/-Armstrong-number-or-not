# -Armstrong-number-or-not
import java.util.Scanner;
public class ams {
    public static void main(String[] args) {
	   Scanner sc = new Scanner(System.in);
	   int n=sc.nextInt();
           int result=0;
           for(int j = n; j>0 ; j = j/10){
            result = result + ((j%10)*(j%10)*(j%10));
        }
        if(result == n){
            System.out.print("1");}
        else{
            System.out.print("0");}
        }
     }

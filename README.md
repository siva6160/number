# number
package polindreme;
import java.util.*;
public class numbers {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int num;
		int sum=0;
		int r=0;
		int temp;
		Scanner sc=new Scanner(System.in);
		num=sc.nextInt();
		temp=num;
		while(num>0){
			r=num%10;
			sum=(sum*10)+r;
			num=num/10;
			//123System.out.println(r);
		}
		if(sum==temp){
			System.out.print("polindrame");
		}
		else{
			System.out.println("not a polindrame");
		}
	}

}

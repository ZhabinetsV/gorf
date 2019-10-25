# gorf
import java.util.*;

public class Main {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Введи пятизначное число");
		int a = sc.nextInt();
		System.out.println(a/10000);
		System.out.println(a%10000/1000);
		System.out.println(a%1000/100);
		System.out.println(a%100/10);
		System.out.println(a%10);
		
		
	}

}

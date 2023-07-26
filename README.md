# odd-and-even-number-java
basic odd and even number code java for beginners
package demo;

import java.util.Scanner;

public class Solution {
	public void numbers() {
		 Scanner sc = new Scanner(System.in);

		int a;
		System.out.println("enter a number ");
	    a = sc.nextInt();
	    
	    if(a%2==0)
	    {
	    	System.out.println("it is a odd number");
	    }
	    else
	    {
	    	System.out.println("it is a even number");
	    }
	 	System.out.println("do you want to chek another number??");
	   	System.out.println("press 1 for Yes /n press other key for exit!");
	   	int option = sc.nextInt();
	   	if(option==1)
	   	{
	   		this.numbers();
	   	}
	   	else {
	   		System.out.println("Happy coding!!");
	   	}
	
	}
	public static void main(String[] args) {
		Solution obj = new Solution();
		obj.numbers();
	}
}

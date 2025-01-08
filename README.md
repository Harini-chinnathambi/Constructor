# Constructor
import java.io.*; 
class account { 
	private int balance = 50; 
             public int  account  ()  { 
		 
	} 
	// accessor method (getter) 
	public int getBalance()  { 
		return balance; 
	} 
	
	// Mutator method (setter) 
	public void setBalance(int a) { 
	// return balance + a; 
		balance += a; 
	} 
} 
class balalceCalculate { 
    public static void main(String[] args) { 
	account obj = new account(); 
	obj.setBalance(50); 
	// calling the Mutator (accessor) 
System.out.println("Your Balance : "+ obj.getBalance()); 
   } 
}
 output: your balance is 100
 

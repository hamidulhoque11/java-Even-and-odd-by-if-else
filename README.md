# java-Even-and-odd-by-if-else

import java.util.Scanner;

class Main {

    public static void main(String[] args) {
    
        Scanner sc= new Scanner(System.in);
     int number;
     System.out.println("----Chack Even and odd value ---------");
     System.out.print("Enter any number:");
     number=sc.nextInt();
     if(number % 2==0){
         System.out.println("Even number");
     
     }else {
          System.out.println("odd value"); //we can use another way like "number%2 !=0"
     }
        
        
    }
}

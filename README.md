# methods-and-packages
code 

package assignment3;

import java.util.Scanner;

/**
 * java program to convert minutes into a number of years and day

 */
public class Assignment3 {

    
    public static void main(String[] args) {
        
        Scanner sc = new Scanner (System.in);
        System.out.println("Enter number of minutes");
        double min = sc.nextDouble();
        
        long years= (long) (min/(60*24*365));
        long days = (long) (min /60/24)%365;
        
        System.out.println(min + " is approx "+ years + " years & "+ days + " days");
        
        
    }
    
}

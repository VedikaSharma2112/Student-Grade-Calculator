# Student-Grade-Calculator

import java.util.*;
class Result
{ 
     public static void main(String arr[])
	 {   
	     Scanner sc = new Scanner(System.in);
		 System.out.println("Enter the number of subjects:");
		 int n = sc.nextInt();
		 
		 int totalMarks = 0;
		 int marks;
		 
		 for(i=1;i<=n;i++)
		 {
		      System.out.println("Enter marks of the subject " + i + " out of 100 :");
			  marks = sc.nextInt();
			  totalMarks += marks;
		 }
		 
		 int average = int totalMarks/n;
		 
		 char grade;
		 if(average>=90)
		 {
		     grade = 'A';
		 }
		 else if(average>=80)
		 {
		     grade = 'B';
		 }
		 else if(average>=70)
		 {
		     grade = 'C';
		 }
		 else if(average>=60)
		 {
		     grade = 'D';
		 }
		 else
		 {
		     grade = 'F';
		 }
		 
		 System.out.println(" RESULT ");
		 System.out.println("Total Marks:" +totalMarks);
		 System.out.println("Average Percentage:" + average + "%");
		 System.out.println("Grade:" +grade);
      }
}
		 
		 
		 
	
		 
		 
		 
    

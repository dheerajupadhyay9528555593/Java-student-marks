# Java-student-marks
import java.util.*;
public class Student
{
public static void main(String[]args)
{System.out.println("Made by Dheeraj Upadhyay");
double total=0.0;
double per;
string sub[]=new int[];
double marks[]=new double[];
Scanner sc=new Scanner(System.in);
System.out.println("Enter the student name");
string name=sc.nextLine();
System.out.println("Enter the number of subjects");
int n=sc.nextInt();
System.out.println("Enter the subject as well as marks");
for(int i=0;i<n;i++)
{sub[i]=sc.nextLine();
marks[i]=sc.nextDouble();}
for(int j=0;j<n;j++)
{total=total+marks[j];
}
per=total/n;




}
}

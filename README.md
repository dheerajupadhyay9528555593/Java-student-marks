# Java-student-marks
import java.util.*;
public class Student
{
public static void main(String[]args)
{System.out.println("Made by Dheeraj Upadhyay");
double total=0.0;
double per;
string sub[]=new string[];
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
System.out.println("Student name : ");
System.out.println("Subjects : ");


for(int k=0;k<n;k++)
{System.out.println(sub[k]+"\t");}
System.out.println("Marks    : ");
for(int l=0;l<n;l++)
{System.out.println(marks[l]);}
System.out.println("Total percentage gained : "+per);



}
}

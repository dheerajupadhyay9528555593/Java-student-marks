
import java.util.*;
public class Student
{
public static void main(String[]args)
{

Scanner sc=new Scanner(System.in);
System.out.println("Made by Dheeraj Upadhyay");
int total=0;
double per;


System.out.println("Enter the student name");
String name=sc.next();

System.out.println("Enter the number of subjects");
int n=sc.nextInt();

String sub[]=new String[n];
int marks[]=new int[n];
System.out.println("Enter the subjects as well as marks");
for(int i=0;i<n;i++)
{sub[i]=sc.next();

marks[i]=sc.nextInt();
}
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

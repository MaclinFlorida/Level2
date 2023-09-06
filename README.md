import java.util.*;
class todo
{
public static void main()
{
Scanner sc=new Scanner(System.in);
System.out.println("To do list");
System.out.println("Menu");
System.out.println("_____");
System.out.println(1.Assignments \n2.Spanish lessons \n3.Complete your record \n4.Workout);
System.out.println("Enter your choice from 1-4");
int choice=sc.nextInt();
todo obj=new todo();
switch(choice)
{
case 1:
obj.assign();
break;
case 2:
System.out.println("Spanish lessons");
System.out.println("If done press 1, if not press 0");
int n=sc.nextInt();
if(n==1)
System.out.println("Good job");
else
System.out.println("Put on hold");
break;
case 3:
System.out.println("Complete your record");
break;
case 4:
System.out.println("Workout time");
System.out.println("How long did you soend (in minutes)");
double t=sc.nextDouble();
if(t<45.00)
System.out.println("You can do better");
else if(t==45.00)
System.out.println("Almost there");
else if(t>45.00)
System.out.println("Ambitious");
break;
default:
System.out.println("Wrong input");
}
}
void assign()
{
Scanner sc=new Scanner(System.in);
System.out.println("1.Chemistry assignment");
System.out.println("Press 1 if done");
int n=sc.nextInt();
if(n==1)
{
System.out.println("Completed");
System.out.println("2. C++");
System.out.println("Enter 1 if Completed");
int n1=sc.nextInt();
if(n1==1)
System.out.println("Completed");
System.out.println("Up to date");
}
else
System.out.println("Incomplete work");
}
}


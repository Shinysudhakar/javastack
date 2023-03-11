ASSIGNMENT 1

### 1.WRITE A JAVA PROGRAM TO PRINT THE SUM,MULTIPLY,SUBTRACT,DIVIDE AND REMAINDER.
  ```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        int a,b,add,sub,div,mul,rem;
        Scanner in = new Scanner(System.in);
        a = in.nextInt();
        b = in.nextInt();
        add=a+b;
        sub=a-b;
        mul=a*b;
        div=a/b;
        rem=a%b;
        System.out.println("Addition = "+add);
        System.out.println("Subtraction = "+sub);
        System.out.println("Multiply = "+mul);
        System.out.println("Divide = "+div);
        System.out.println("Remainder = "+rem);
    }
}
  ```
OUTPUT:
![Screenshot 2023-03-11 105317](https://user-images.githubusercontent.com/127575325/224466653-f4ac95af-1c0f-4568-b6c4-dfc1c6b0973c.png)


### 2. WRITE A JAVA PROGRAM TO COMPARRE TWO NUMBERS
  ```
public class CompareTwoNumbers {
 
 public static void main(String[] args) {
 
 //declare two numbers to compare
 int num1 = 324;
 int num2 = 234;
 
 if(num1 > num2){
 System.out.println(num1 + " is greater than " + num2);
 }
 else if(num1 < num2){
 System.out.println(num1 + " is less than " + num2);
 }
 else{
 System.out.println(num1 + " is equal to " + num2);
 }
 }
}
   ```
OUTPUT:
![Screenshot 2023-03-11 093721](https://user-images.githubusercontent.com/127575325/224464045-8b584d36-f6d4-438e-b8ed-bba1db2de68c.png)

### 3. WRITE A JAVA PROGRAM TO CONVERT A STRING TO AN INTEGER
   ```
public class Main 
{
    public static void main(String[] args)
    {
        String a="50";
        int b=Integer.parseInt(a);
        System.out.println("Convert a string to an integer "+b);
    }
}
   ```
OUTPUT:
![Screenshot 2023-03-11 095143](https://user-images.githubusercontent.com/127575325/224464614-5e3a638c-ce26-40f0-a0f8-9dbf310d7f54.png)

### 4.JAVA PROGRAM TO FIND AREA OF RHOMBUS 
   ```
public class Main
{
    public static void main(String args[])
    {
        float a=10,b=20;
        float Area_of_rhombus;
        Area_of_rhombus=(a*b)/2;
        System.out.println("Area of Rhombus is "+Area_of_rhombus);
    }
}
   ```
OUTPUT:
![photo_2023-03-11_11-02-05](https://user-images.githubusercontent.com/127575325/224466934-5a59c241-cd8a-40b2-b5df-ab17c1dbc41f.jpg)


### 5.WRITE A JAVA PROGRAM TO FIND THE NUMBER OF DAYS IN A MONTH

   ```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {

        Scanner input = new Scanner(System.in);

        int Days=0;
        String Name = " ";

        System.out.print("Enter the month number: ");
        int month = input.nextInt();

        System.out.print("Enter the year: ");
        int year = input.nextInt();

        switch (month) {
            case 1:
                Name = "January";
                Days = 31;
                break;
            case 2:
                Name = "February";
                if ((year % 400 == 0)||((year % 4 == 0)&&(year % 100 != 0))) {
                    Days= 29;
                } else {
                    Days = 28;
                }
                break;
            case 3:
                Name = "March";
                Days = 31;
                break;
            case 4:
                Name = "April";
                Days = 30;
                break;
            case 5:
                Name = "May";
                Days = 31;
                break;
            case 6:
                Name = "June";
                Days = 30;
                break;
            case 7:
                Name = "July";
                Days = 31;
                break;
            case 8:
                Name = "August";
                Days = 31;
                break;
            case 9:
                Name = "September";
                Days = 30;
                break;
            case 10:
                Name = "October";
                Days = 31;
                break;
            case 11:
                Name = "November";
                Days = 30;
                break;
            case 12:
                Name = "December";
                Days = 31;
        }
        System.out.println(Name + " " + year + " has " + Days + " days");
    }
}
  ```
OUTPUT:
![Screenshot 2023-03-11 105802](https://user-images.githubusercontent.com/127575325/224466849-862361d6-86c1-4442-a3d6-59f572ca6b0f.png)




### 6. WRITE A JAVA PROGRAM TO PRINT THE EVEN NUMBERS FROM 1 TO 20 
  ```
public class Javaexcercise {
     public static void main(String[] args){
    for (int i = 1; i < 20; i++) {
            if (i % 2 != 1) {
                System.out.println(i);
            }
        }
    }
}
   ```
OUTPUT:
![1 TO 20](https://user-images.githubusercontent.com/127575325/224463887-56f28403-0918-42d7-a89d-a507b30678d8.png)

### 7.WRITE A JAVA PROGRAM TO CREATE A SIMPLE CALCULATOR

  ```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        char operator;
        double num1, num2, result;
        Scanner input = new Scanner(System.in);
        System.out.println("Choose an operator: +, -, *, or /");
        operator = input.next().charAt(0);
        System.out.println("Enter first number");
        num1 = input.nextDouble();
        System.out.println("Enter second number");
        num2 = input.nextDouble();

        switch (operator) {

            case '+':
                result = num1 + num2;
                System.out.println(num1 + " + " + num2 + " = " + result);
                break;

            case '-':
                result = num1 - num2;
                System.out.println(num1 + " - " + num2 + " = " + result);
                break;

            case '*':
                result = num1 * num2;
                System.out.println(num1 + " * " + num2 + " = " + result);
                break;

            case '/':
                result = num1 / num2;
                System.out.println(num1 + " / " + num2 + " = " + result);
                break;

            default:
                System.out.println("Invalid operator!");
                break;
        }
    }
}
  ```
OUTPUT:
![Screenshot 2023-03-11 111329](https://user-images.githubusercontent.com/127575325/224467333-0ac59276-2542-437a-b798-5362da2d9c7a.png)





### 8.WRITE A PROGRAM TO PRINT MULTIPLICATION TABLE OF GIVEN NUMBER
  ```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter number: ");
        int n=s.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(n+" * "+i+" = "+n*i);
        }
    }
}
  ```
OUTPUT:
![Screenshot 2023-03-11 110851](https://user-images.githubusercontent.com/127575325/224467166-4c32ab71-0482-412c-9c9f-fce194c1398f.png)




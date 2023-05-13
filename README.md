### compare
EXP-2 Java program to compare two numbers
### AIM:
To compare two numbers using java programming language.

### PROCEDURE:
1)Import required packages.
2)Declare main method with the signature "public static void main(String[] args)".
3)Get two numbers as input.
4)Compare two numbers using else-if ladder.
5)Dispaly the output accordingly.
### PROGRAM:
~~~
import java.util.Scanner;
public class compare {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        if(a==b)
        {
            System.out.println(a+"=="+b);
        }
        else if(a>b)
        {
            System.out.println(a+">"+b);
        }
        else if(a<b)
        {
            System.out.println(a+"<"+b);
        }
        else {
            System.out.println(a+"!="+b);
        }
    }
}
~~~
### OUTPUT:
EXP-2 Java program to compare two numbers
AIM:
To compare two numbers using java programming language.

PROCEDURE:
Import required packages.
Declare main method with the signature "public static void main(String[] args)".
Get two numbers as input.
Compare two numbers using else-if ladder.
Dispaly the output accordingly.
PROGRAM:
import java.util.Scanner;
public class compare {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        if(a==b)
        {
            System.out.println(a+"=="+b);
        }
        else if(a>b)
        {
            System.out.println(a+">"+b);
        }
        else if(a<b)
        {
            System.out.println(a+"<"+b);
        }
        else {
            System.out.println(a+"!="+b);
        }
    }
}
OUTPUT:
![image](https://github.com/SdMdZahi7/compare/assets/94187572/e66408b6-5d95-4b8a-8311-7dbf6fc9e5b6)

### RESULT:
To compare two numbers using java programming language was successfully done.

# Day2-Hw2
import java.util.Scanner;


public class Main {
    public static void main(String[] args) {
//solve first exercies 
        int fnum = 125;
        int snum = 24;
        int plus = fnum + snum;
        int sub = fnum / snum;
        int div = fnum - snum;
        int mul = fnum * snum;
        int mode = fnum % snum;
        System.out.printf("the ruselt is plus=%d\n sub=%d\ndiv=%d\nmul=%d\nmod=%d\n", plus, sub, div, mul, mode);

//solve second exercies2

        String s1 = "THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG.";
        System.out.println(s1.toLowerCase());

//solve third exercise3
        
        Scanner s = new Scanner(System.in);
        System.out.println("Enter number");
        int num = s.nextInt();
        System.out.println("Enter a string");
        String s2 = s.next();
        System.out.println(s2.charAt(1));

//solve 4 Exercies
        System.out.println("Enter number");
        int numFromuser = s.nextInt();
        if (numFromuser % 2 == 0) {
            System.out.println("it is Even number");
        } 
        else {
            System.out.println("it is Odd number");

        }
//solve 5 Exercies
        System.out.println("enter your role");
        String role = s.next();
        if (role.equals("Admin")) {
            System.out.println("welcome admin");
        } else if (role.equals("superAdmin")) {
            System.out.println("welcome superAdmin");
        } else {
            System.out.println("welcome user");
        }

        //solve 6 Exersice
        int n1 = 5;
        int n2 = 10;
        int n3 = 15;
        int sum = n1 + n2;
        if (sum == n3) {
            System.out.println("True");
        } else {
            System.out.println("false");
        }
        //solve exercise 7
        System.out.println("Enter number 1");
        int num1 = s.nextInt();
        System.out.println("Enter number 2");
        int num2 = s.nextInt();
        System.out.println("Enter number 3");
        int num3 = s.nextInt();
        if (num1 > num2 && num1 > num3)
            System.out.println(num1);
        else if (num2 > num3 && num2 > num3) {
            System.out.println(num2);
        } else {
            System.out.println(num3);
        }

        //solve exersice num 8

        System.out.print("Enter number: ");
        int day = s.nextInt();
        switch (day) {
            case 1:
                System.out.println("Sunday");
                break;
            case 2:
                System.out.println("Monday");
                break;
            case 3:
                System.out.println(" Tuesday");
                break;
            case 4:
                System.out.println("Wednesday");
                break;
            case 5:
                System.out.println(" Thursday");
                break;
            case 6:
                System.out.println("Friday");
                break;
            case 7:
                System.out.println("Saturday");
                break;
            default:
                System.out.println("Invalid day range");
        }

    }
}

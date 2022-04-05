# Write-a-program-that-allows-input-to-a-string-check-if-this-string-contains-numbers-or-not.
Write a program that allows input to a string, check if this string contains numbers or not.
import java.util.Scanner;
public class BaiTapJavaCoBan18
{
    public static void main(String[] args)
    {
       String String;
       Scanner sc = new Scanner(System.in);

       System.out.println("Enter a string: ");
       string = sc.nextLine();

       if (chuoi.matches(".*\\d.*"))
          System.out.println("Yes");
       else
          System.out.println("No");
    }
}

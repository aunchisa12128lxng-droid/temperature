# temperature
import java.util.Scanner;
public class Main{
   public static void main(String[] args){
       Scanner kb = new Scanner(System.in);
       double F,C;
       System.out.println("=== Program check weather ===");
       System.out.print("Input temperature (fahrenheit): ");
       F = kb.nextDouble();
       C = (F-32) * 5/9;
       System.out.println("=== processing ===");
       System.out.println("Temperature (celsius): " +C);
       if (C<23){
           System.out.println("Weather: อากาศหนาวเย็น (cold)");
       }else if(C>= 23 && C < 28){
           System.out.println("Weather: อากาศกำลังดี (cool)");
       }else if(C >= 28 && C <33){
           System.out.println("Weather: อากาศอบอุ่น (warm)");
       }else if(C>33){
           System.out.println("Weather: อากาศร้อน (hot)");
       }
   }
}

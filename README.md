import java.util.Scanner;
public class vsekursi {
  public static void main(String[] args) {
    System.out.println("Select the currency to convert:");
    System.out.println("1. Dollar");
    System.out.println("2. Evro");
    System.out.println("3. Sterlinq");
    Scanner s = new Scanner(System.in);
    int z = s.nextInt();

    if (z == 2) {

      float x = 1.84 F;
      Scanner sc = new Scanner(System.in);
      System.out.println("Enter the conversion amount:");
      int a = sc.nextInt();

      double c = a * x;

      if (c > 0) {
        System.out.println(c);
      } else if (c < 0) {
        System.out.println("Error:can't be less than 0");
      } else {
        System.out.println("Error: can't be  0");
      }
    }
    if (z == 1) {

      float b = 1.70 F;
      Scanner sc = new Scanner(System.in);
      System.out.println("Сonversion amount:");
      int a = s.nextInt();

      double c = a * b;

      if (c > 0) {
        System.out.println(c);
      } else if (c < 0) {
        System.out.println("Error: Ne mojet bit menshe 0");
      } else {
        System.out.println("Error: Ne mojet bit raven 0");
      }
    }

    if (z == 3) {

      float x = 2.04 F;
      Scanner sc = new Scanner(System.in);
      System.out.println("Sterlinq:");
      int a = sc.nextInt();

      double c = a * x;

      if (c > 0) {
        System.out.println(c);
      } else if (c < 0) {
        System.out.println("Error:can't be less than 0");
      } else {
        System.out.println("Error:can't be 0");
      }

    }
  }
}
# exchance-valut

import java.util.Scanner;
public class vsekursi {
  public static void main(String[] args) {
    System.out.println("Vibrat valyutu dlya konvertasiyi:");
    System.out.println("1. Dollar");
    System.out.println("2. Evro");
    System.out.println("3. Sterlinq");
    Scanner s = new Scanner(System.in);
    int z = s.nextInt();

    if (z == 2) {

      float x = 1.84 F;
      Scanner sc = new Scanner(System.in);
      System.out.println("vvedite summu konvertasiyi:");
      int a = sc.nextInt();

      double c = a * x;

      if (c > 0) {
        System.out.println(c);
      } else if (c < 0) {
        System.out.println("Error:ne mojet bit denqi v minuse");
      } else {
        System.out.println("Error: ne mojet bit raven 0");
      }
    }
    if (z == 1) {

      float b = 1.70 F;
      Scanner sc = new Scanner(System.in);
      System.out.println("Summa konvertasiyi:");
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
        System.out.println("Error:Ne mojet bit v minuse");
      } else {
        System.out.println("Error:Ne mojet bit raven 0");
      }

    }
  }
}
# exchance-valut

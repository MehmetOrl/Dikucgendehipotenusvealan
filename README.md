```java  import  java.util.Scanner;
public class DikUcgen {
    public static void main(String[] args) {
        Scanner Input=new Scanner(System.in);
       // Üç kenar uzunluğunu kullanıcıdan aldığınız üçgenin alanını hesaplayan programı yazınız.
        double a,b,c,d,alan;
        System.out.print("a uzunluğunu giriniz.:");
        a= Input.nextInt();
        System.out.print("b uzunluğunu giriniz.:");
        b= Input.nextInt();
        System.out.print("c uzunluğunu giriniz.:");
        c= Input.nextInt();
        double cevre=a+b+c;
        d=(a+b+c)/2;
        alan=Math.sqrt(d*(d-a)*(d-b)*(d-c));
        System.out.println("çevresi.:"+cevre);
        System.out.println("alanı.:"+alan);







    }
}

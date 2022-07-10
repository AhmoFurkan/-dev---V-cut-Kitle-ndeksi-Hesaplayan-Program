# Vücut Kitle İndeksi Hesaplayan Program
Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın. Aşağıdaki formüle göre kullanıcının "Vücut Kitle İndeks" değerini hesaplayıp ekrana yazdırın.


Formül
Kilo (kg) / Boy(m) * Boy(m)


Lütfen boyunuzu (metre cinsinde) giriniz : 1,72

Lütfen kilonuzu giriniz : 105

Vücut Kitle İndeksiniz : 35.49215792320173

      import java.util.Scanner;

       public class Main {
      public static void main(String[] args) {

       double  m,kg;
       Scanner gir =new Scanner(System.in);

       System.out.print("Lütfen Boyunuzu (metre cinsinde) giriniz:");
       m = gir.nextDouble();

       System.out.print("Lütfen Kilonuzu Girin :");
       kg = gir.nextDouble();

       double Vki = kg/(m*m);
       System.out.println("Vücut Kitle İndeksiniz :" + Vki);


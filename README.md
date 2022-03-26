# Uslu-Sayi-Hesaplayan-Program
Patika.dev > Java101 > Döngüler > Pratik5 - Üslü Sayı Hesaplayan Program

Java ile kullanıcının girdiği değerler ile üslü sayı hesaplayan programı yazıyoruz.

### Ödev

Java ile kullanıcının girdiği değerler ile üslü sayı hesaplayan programı "For Döngüsü" kullanarak yapınız.


    import java.util.*;

    public class exponential_number {

      public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        // n^k
        System.out.print("Enter the n: ");
        int n = sc.nextInt();

        System.out.print("Enter the k: ");
        int k = sc.nextInt();

        int total = 1;
        for(int i=1; i<=k; i++) {
          total *= n;
        }

        System.out.println("Answer : " + total);
      }
    }

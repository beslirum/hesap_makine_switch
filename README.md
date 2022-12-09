# hesap_makine_switch
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int a, b;
        int select;
        Scanner input = new Scanner(System.in);
        System.out.println("Birinci sayiyi girin:");
        a = input.nextInt();
        System.out.println("İkinci sayiyi giriniz:");
        b= input.nextInt();

        System.out.println("1-Toplama\n2-Cikarma\n3-Bolme\n4-Carpma");
        System.out.println("Yapmak istediginiz islemi seciniz:");
        select=input.nextInt();

        switch (select){
            case 1:
                System.out.println(a+b);
                break;
            case 2:
                System.out.println(a-b);
                break;
            case 3:
                System.out.println(a/b);
                break;
            case 4:
                System.out.println(a*b);
                break;
            default:
                System.out.println("Gecersiz islem sectiniz!");
        }
    }
}

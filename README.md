# ortalamaHesaplama

import java.util.Scanner;
public class ilkProje {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int n1,n2,n3,n4,n5,snc;
        boolean gecis;

        System.out.print("Birinci notu giriniz: ");
        n1=input.nextInt();

        System.out.print("İkinci notu giriniz: ");
        n2=input.nextInt();

        System.out.print("Üçüncü notu giriniz: ");
        n3=input.nextInt();

        System.out.print("Dördüncü notu giriniz: ");
        n4=input.nextInt();

        System.out.print("Beşinci notu giriniz: ");
        n5=input.nextInt();
        snc=(n1+n2+n3+n4+n5)/5;

        System.out.println("Notlarınızın ortalaması" + snc);

        
    }
}

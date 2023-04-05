# nereye-gitmeliyim
patika.dev hava durumuna göre gitmemiz gereken yeri öneren program

import java.util.Scanner;
public class main {
    public static void main(String[]args){
        int heat;
        Scanner inp= new Scanner(System.in);
        System.out.print("Hava sıcaklığını giriniz:");
        heat = inp.nextInt();
        if (heat <5){
            System.out.print("Kayağa gidebilirsin");
        } else if (heat <= 15) {
            System.out.print("Sinemaya gidebilirsin");
        }else if (heat <= 25){
            System.out.print("Pikniğe gidebilirsin");
        }else {
            System.out.print("Yüzmeye gidebilirsin");
        }
    }
    
}

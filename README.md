# Przykladowa-petla-Wojtka
package Pętla2;
public class Pętla2 {
    public static void main(String[] args) {
        int start = 10;                         //dodaje od 10 i biegnie do 20
        int stop = 20;
        int number = 10;

        while (stop>=start) {
            number++;
            System.out.println(number);
            if(number == 20) {
                break;
            }
        }
    }
}

package javaapplication17;

import java.util.Scanner;

/**
 *
 * @author LENOVO
 */
public class JavaApplication17 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
         Scanner sc = new Scanner(System.in);
         int sum=0;
        System.out.println("Введите кол-во элементов в массиве: ");
        int kol=sc.nextInt();
        int[]numbers=new int[kol];
        
         System.out.println("Введите элементы массива:");
        for(int i=0; i<kol; i++){
            numbers[i]=sc.nextInt();
        }
        for(int i=0; i<=kol; i++){
            sum=sum+i;
        }
        int srednee = sum/kol;
        System.out.println("Среднее значение - "+ srednee);
    }
    
}

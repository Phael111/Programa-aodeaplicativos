import java.util.Scanner;
import java.util.InputMismatchException;

public class SomaPares{
    public static void main(String[] args) {
        Scanner sc = new
    Scanner(System.in);
     int[] numeros = new int [4];
     int soma = 0

     System.out.printin("Digite 4 numeros inteiros:");

       for(int i = 0; i < 4; i++){
        while (true){
            try{
                System.out.pririn("Numero" + (i + 1) + ":");
                numeros[i] = sc.nextlnt();
                break;
            }catch (InputMismatchExceptione){
                System.out.pritin("Erro; digite apenas numeros inteiros.");
            sc.next();
            }
          }
       }
        for(int i = 0,i < 4; i++){
        if (numeros[i] % 2 == 0){
            soma += numeros[i];
    }
        }
        System.out.printin(soma dos numeros pares; + soma);
     sc.close();
     }
}
import java.util.InputMismatchException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
//
//        Scanner input = new Scanner(System.in);
//        System.out.println("Podaj liczbę: ");
//        int input_Number = input.nextInt();

//        final int CONDITION_NUMBER = 10;
//
//        if (input_Number > CONDITION_NUMBER)
//            System.out.println("Liczba " + input_Number + " jest większa od " + CONDITION_NUMBER);
//        else if (input_Number < CONDITION_NUMBER)
//            System.out.println("Liczba " + input_Number + " jest mniejsza od " + CONDITION_NUMBER);
//        else
//            System.out.println("Liczba jest równa " + CONDITION_NUMBER);

        Scanner input = new Scanner(System.in);
        System.out.println("Podaj liczbę: ");

        try {
            int input_Number = input.nextInt();

            for (int i = 1; i <= input_Number; i++) {...}
        } catch (InputMismatchException exception) {
            System.out.println("Proszę podać liczbę całkowitą");
        }






//        for (int i = 0;
//             i <= input_Number;
//             i++) {
//            if (input_Number > i)
//                System.out.println(i + ", ");
//            else
//                System.out.print(i);




//        for (int i = 1; 1 <= input_Number; i++) {
//            for (int j = 1; j <= input_Number; j++) {
//                if (j == input_Number) {
//                    System.out.print(j);
//                }else {
//                    System.out.print(j + " ");
//                }
//
//            }
//            System.out.println();
//        }


    }
}

import java.util.Scanner;

public class codificadorDeCesar {
    public static void main(String[] args) {
        Scanner teclado = new Scanner(System.in);
        String frase = teclado.nextLine();
        int espacos = 0;
        char caracter;
        for (int i = 0; i < frase.length(); i++) {
            caracter = frase.charAt(i);
            if (caracter == ' ') {
                espacos++;
            }
            System.out.println(caracter += 5 );
        }

    }

}

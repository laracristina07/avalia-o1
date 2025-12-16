# avalia-o1
import java.util.Scanner;

public class MediaAluno {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        double[] notas = new double[8];

        // Leitura das 8 notas
        for (int i = 0; i < 8; i++) {
            System.out.print("Digite a nota " + (i + 1) + ": ");
            notas[i] = sc.nextDouble();
        }

        // Médias bimestrais
        double bimestre1 = (notas[0] + notas[1]) / 2;
        double bimestre2 = (notas[2] + notas[3]) / 2;
        double bimestre3 = (notas[4] + notas[5]) / 2;
        double bimestre4 = (notas[6] + notas[7]) / 2;

        // Médias semestrais
        double semestre1 = (bimestre1 + bimestre2) / 2;
        double semestre2 = (bimestre3 + bimestre4) / 2;

        // Média final
        double mediaFinal = (semestre1 + semestre2) / 2;

        // Exibição dos resultados
        System.out.println("\nMédias Bimestrais:");
        System.out.println("1º Bimestre: " + bimestre1);
        System.out.println("2º Bimestre: " + bimestre2);
        System.out.println("3º Bimestre: " + bimestre3);
        System.out.println("4º Bimestre: " + bimestre4);

        System.out.println("\nMédias Semestrais:");
        System.out.println("1º Semestre: " + semestre1);
        System.out.println("2º Semestre: " + semestre2);

        System.out.println("\nMédia Final do Aluno: " + mediaFinal);

        sc.close();
    }
}

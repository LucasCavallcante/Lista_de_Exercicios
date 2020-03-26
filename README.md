# Lista_de_Exercicios

package QUEST1;
import java.util.Scanner;
public class LP {
	

	public static void main(String[] args) {
	Scanner Leitor = new Scanner (System.in);
  
	int N1, N2, soma;
	
	System.out.println("Digite um numero: ");
	N1 = Leitor.nextInt();
	
	System.out.println("Digite outro numero: ")
	;N2 = Leitor.nextInt();

	
	soma = N1 + N2;
	
	System.out.println("A soma de "+ N1 + " e " + N2 + " é igual a: \n"+ soma);
	
	}

}


public class Quet03 {

	public static void main(String[] args) {
		Scanner leitor = new Scanner (System.in);
		
		double N1, N2, N3, N4, media;
		 
		System.out.println("Digite o valor de Nota 1: ");
		N1 = leitor.nextDouble();
		System.out.println("Digite o valor de Nota 2: ");
		N2 = leitor.nextDouble();
		System.out.println("Digite o valor de Nota 3: ");
		N3 = leitor.nextDouble();
		System.out.println("Digite o valor de Nota 4: ");
		N4 = leitor.nextDouble();
		
		media = (N1+N2+N3+N4)/4;
	
		System.out.println("Media das notas: "+ media);
		
	}

}

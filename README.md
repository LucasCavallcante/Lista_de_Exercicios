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

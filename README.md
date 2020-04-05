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


public class Quest02 {

	public static void main(String[] args) {
		Scanner leitor = new Scanner (System.in);
		
		double Altura, Base;
		double Area, Perimetro;
		 
		System.out.println("Digite a altura do retangulo: ");
		Altura = leitor.nextDouble();
		System.out.println("Digite a base do retangulo: ");
		Base = leitor.nextDouble();
		
		Perimetro = (Altura + Base)*2;
		
		System.out.println("Perimetro do Retangulo é: "+ Perimetro);
		
		Area = Altura * Base;
		
		System.out.println("Área do retangulo é: "+ Area);
		
	}

}


public class Quest03 {

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


public class Quest04 {

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
		
		if(media>=6) {
		System.out.println("Aprovado");
	}
		else {
			System.out.println("reprovado");
		}
		
	 }
	}


public class Quest05 {

	public static void main(String[] args) {
		Scanner leitor = new Scanner (System.in);
		
		int N1;
		 
		System.out.println("Digite o valor 1: ");
		N1 = leitor.nextInt();
		
		if(N1%2==0) {
		System.out.println("par");
	}
		else {
			System.out.println("impar");
		}
		
	 }
	}
	
	
public class Quest06 {

		public static void main(String[] args) {
		Scanner leitor = new Scanner (System.in);
		
		double N1,N2;
	
		System.out.println("Digite o valor 1: ");
		N1 = leitor.nextDouble();
		
		System.out.println("Digite o valor 2: ");
		N2 = leitor.nextDouble();
		
		if(N1<N2) {
		System.out.println("\n"+N1+"\n" +N2);
	}
		else {
			System.out.println("\n"+N2+"\n"+N1);
		}
		
	
	}
                }
	
public class Quest06 {	
		
		public static void main(String[] args) {
		Scanner leitor = new Scanner (System.in);
		
		
		double x, a, b;
		
		System.out.println("Digite o valor a: ");
		a = leitor.nextDouble();
		
		System.out.println("Digite o valor b: ");
		b = leitor.nextDouble();
		
		System.out.println("Digite o valor x: ");
		x = leitor.nextDouble();
		  
		while(a>b){
		System.out.println("A tem que ser menor que B, digite A: ");
		a = leitor.nextDouble();
		}
		
		if(x>=a && x<=b) {
			System.out.println(x+" esta no intervalo fechado de "+a+" e "+b);
			}
		
		else {
			System.out.println(x+" não esta no intervalo fechado de "+a+" e "+b);
		}
			
		}
		}
	 
	 
public class Quest08 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int A;
		int B;
		

		System.out.printf("Digite o valor de A: ");
		A = sc.nextInt();
		System.out.printf("Digite o valor de B: ");
		B = sc.nextInt();
			
		
        if (A>B) {
        	System.out.println("Maior valor "+A);
        	System.out.println("Menor valor "+B);
		}	
        else {
        	System.out.println("Maior valor "+B);
        	System.out.println("Menor valor "+A);
        }	
		
	}
	}
	
	
public class Quest09 {

	
		public static void main(String[] args) {
			Scanner leitor = new Scanner (System.in);
			
			double a, b, c;
			
			System.out.println("Digite o valor 1: ");
			a = leitor.nextDouble();
			
			System.out.println("Digite o valor 2: ");
			b = leitor.nextDouble();
			
			System.out.println("Digite o valor 3: ");
			c = leitor.nextDouble();
			
			if(a<=b && a<=c && b<=c) {
			System.out.println(a+"\n"+b+"\n"+c);

		}else {
			if(a<=b && a<=c && c<=b ) {
			System.out.println(a+"\n"+c+"\n"+b);
		}else {
				
		        if(b<=a && b<=c && a<=c) {
			System.out.println(b+"\n"+a+"\n"+c);
		}else {

		    	if(b<=a && b<=c && c<=a) {
		   	System.out.println(b+"\n"+c+"\n"+a);
		     
		}else {
		   
		   	if(c<=b && c<=a && b<=a) {
		 	System.out.println(c+"\n"+b+"\n"+a);
			   
		}else {
		      
		      if(c<=b && c<=a && a<=b) {
		        System.out.println(c+"\n"+a+"\n"+b);
			   
		}
		}
		}
		}	 
		}
		}
		}
		}
	

public class Quest10 {
	
	public static void main(String[] args) {
		Scanner leitor = new Scanner (System.in);
		
		int Idade;
		
		System.out.println("Digite sua idade: ");
		Idade = leitor.nextInt();
		
		if (Idade<=17) {
			System.out.println("Menor de idade");
			
		}else { 
			
			if(Idade<=64) {
			System.out.println("Maior de idade");
		
		}else {
		
			if (Idade>=65) {
			System.out.println("idoso");	
			
	}
	}
	}
	}
	}


	
	

	

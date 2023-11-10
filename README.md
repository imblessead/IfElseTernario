# IfElseTernario
IfElseTernario

package exemplos;

import java.util.Scanner;

public class IfElseTernario {
public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	System.out.println("Digite um valor : ");
	int valor=sc.nextInt();
	
	String saida=(valor%2==0)?"Valor par":"Valor impar";
	System.out.println(saida);
	
	
	
	sc.close();
}
}

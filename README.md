import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
  Scanner sc = new Scanner(System.in);
  
  System.out.println("Escreva a temperatura em Celsius: ");
  
  Double celsius = sc.nextDouble();
  
  Double Fahrenheit = (celsius * 9/5) * 32;
  
  System.out.println(celsius + " graus Celsius é igual a " + Fahrenheit + " graus Fahrenheit.");

  
  sc.close();

	}

}

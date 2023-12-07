# VERSION 1
import java.util.Scanner;
public class JuegoAdivinarOprecion1{
    public static void main(String[ ] args){
	Scanner entrada=new Scanner(System.in);
	int numero_1, numero_2, resultado;
	System.out.println("Ingresa un numero");
	numero_1=entrada.nextInt( );
	System.out.println("Ingresa un numero");
	numero_2=entrada.nextInt( );
 	System.out.println(numero_1 + "*"+numero_2 + "=");
	resultado=entrada.nextInt( );
	System.out.print("Resultado correcto" + (numero_1*numero_2 == resultado));


  }	

}



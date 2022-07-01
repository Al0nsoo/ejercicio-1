# ejercicio-1
package prueba;
import java.util.Scanner;

public class primero {

	public static void main(String[] args) {
		Scanner scan = new Scanner (System.in);  
		float num;
		float num2;
		
	 int opc;       
	    do {  
	           System.out.println("1. Pasar de Kg a Lb");
	           System.out.println("2. Pasar de Lb a Kg");
	           System.out.println("3. Salir");
	           opc= scan.nextInt();
	       }while (opc<1 || opc>=4);
	    
	    switch(opc) {
	    case 1:
	    	System.out.println("Introduce el peso");
	    	num=scan.nextInt();
	    	num2=(num*2.2f);
	    	System.out.println(num+" Kg equivalen a "+num2+" Lb");
	    break;
	    case 2:
	    	System.out.println("Introduce el peso");
	    	num=scan.nextInt();
	    	num2=(num/2.2f);
	    	System.out.println(num+" Lb equivalen a "+num2+" Kg");	    	
	    break;	    	
	    }
	}
	
}

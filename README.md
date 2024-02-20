# Hola-mundo-en-Java

```java

//Este es un código de prueba

public class MiPrimerCodigo{
	public static void main(String[] args){
		System.out.print("Hola mundo...");

	} 


} 

```

Ahora el Scanner

```java
import java.util.Scanner;

/**
 *
 * @author Harold Jiménez, práctica de IDE
 */
public class Practica1 {


    public static void main(String[] args) {
       
        System.out.println("Hola mundo...");
        //Instancia, clase, objeto, REFERENCIA
        Scanner lector;
        Estudiantes obj1 = new Estudiantes();
        lector = new Scanner(System.in);
        System.out.println("Ingrese un número entero");
        int val = lector.nextInt();
        
        
        
        
        
        System.out.println("Su número es " + val + " y su tamaño en memoria es "  );
        
    }
    
}
```

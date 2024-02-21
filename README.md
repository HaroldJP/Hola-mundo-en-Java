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

Practica 1

```java
import java.util.Scanner;

public class Practica1 {

    public static void main(String[] args) {
        Scanner lector = new Scanner(System.in);
        
        System.out.println("Ingrese un número entero (dato tipo int)");
        int val = lector.nextInt();

        System.out.println("Ingrese un caracter (dato tipo char)");
        char val2 = lector.next().charAt(0);

        System.out.println("Ingrese un entero (dato tipo byte)");
        byte val3 = lector.nextByte();

        System.out.println("Ingrese un entero (dato tipo short)");
        short val4 = lector.nextShort();

        System.out.println("Ingrese un entero (dato tipo long)");
        long val5 = lector.nextLong();

        System.out.println("Ingrese un dato booleano (true o false)");
        boolean val6 = lector.nextBoolean();

        System.out.println("Ingrese un real (dato tipo float)");
        float val7 = lector.nextFloat();

        System.out.println("Su número es " + val + " y su tamaño en memoria es " + Long.BYTES);
        System.out.println("Su carácter es " + val2 + " y su tamaño en memoria es " + Character.BYTES);
        System.out.println("Su byte es " + val3 + " y su tamaño en memoria es " + Byte.BYTES);
        System.out.println("Su short es " + val4 + " y su tamaño en memoria es " + Short.BYTES);
        System.out.println("Su long es " + val5 + " y su tamaño en memoria es " + Long.BYTES);
        System.out.println("Su booleano es " + val6 );
        System.out.println("Su float es " + val7 + " y su tamaño en memoria es " + Float.BYTES);
    }
}
```

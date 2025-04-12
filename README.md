# Java.Ejercicios
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
    double numero1;
    double numero2;

  // Definimos varibales
          
        Scanner sc = new Scanner (System.in);
        
      System.out.print(" Pedir el primer numero: ");
        numero1 = sc.nextDouble();

      System.out.print("pedri el segundo numero: ");    
        numero2 = sc.nextDouble(); 
    
      //Muestra el proceso de texto
      
        System.out.print("el resultado de la suma es: " + (numero1 + numero2));
        System.out.print("el resultado de la resta es "  + (numero1 - numero2));
        System.out.print("el resultado de la multiplicación es: " + (numero1 * numero2));    
        System.out.print("el resultadp de la división es: " + (numero1 / numero2));
        System.out.print("el resultado del modulo es: " + (numero1 % numero2));

        // Resultado
        
    }
}  




Ejercicio 2





import java.util.Scanner;

class DatosUser {
    public static void main(String[] args) {
     
       
       Scanner sc = new Scanner (System.in);
       String nombre, edad, correo;
        
       System.out.print("Ingrese su nombre: ");    
       nombre = sc.nextLine();
       System.out.print("Ingrese su edad: ");
       edad = sc.nextLine();
       System.out.print("Ingrese su correo: ");
        correo = sc.nextLine(); 
        
        
        
        
        System.out.println(" Su nombre es: " + nombre);
        
        System.out.println(" Su edad es: " + edad);
        
        System.out.println(" Su correo es: " + correo);





        Ejercicio 3:







        

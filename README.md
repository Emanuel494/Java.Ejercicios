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






import java.util.Scanner;


class CalcularareFiguras {
    public static int  areaTriguanlo(int base, int altura) {
        return (base * altura)/2;
    }
    
    public static double areaCirculo(double radio) {
         double pi = 3.141592;
         return pi * radio * radio;
        
    }

    public static void  main (String[] args) {
       Scanner sc = new Scanner(System.in);
       int opcion;
       
       
       System.out.println("Seleccione la figura a la que que quiere sacar el area: ");
       System.out.println("1. Triangulo");
       System.out.println("2. Rectangulo");
       System.out.println("3. Circulo");
       opcion = sc.nextInt();
       
       switch(opcion) {
           case 1:
               int base, altura;
               System.out.print("ingrese la base :");
               base = sc.nextInt();
               System.out.print("Ingrese la altura. ");
               altura = sc.nextInt();
               double resultado = areaTriangulo(base, altura);
               System.out.print("El area del triangulo sera: " + resultado);
               break;
               
            case 2:  
              
               System.out.print("Ingrese la base: ");
               base = sc.nextInt();
               System.out.print("ingrese la altura: ");
               altura = sc.nextInt();
               resultado = areaRectangulo(base, altura);
               System.out.print("El area del rectangulo sera: "  + resultado);
               break;
               
               
               
            case 3:
             
               int radio; 
               System.out.print("Ingrese el radio: ");
               radio = sc.nextInt();
               resultado = areaCirculo(radio);
               System.out.println("El area del circulo sera: " + resultado);
               break; 
               
       
                
       }
        
            
            
       
      
    
}    
}




        

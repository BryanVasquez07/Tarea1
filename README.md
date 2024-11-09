# Tarea1
tarea modulo 1
public class Modulo1 {

    public static void main(String[] args) {
     
        System.out.println("Hola soy Bryan Vaquez !");
        System . console().readLine();
        System.out.println("Hola Bryan Vasquez");
        
        
    }
   
}
import static java.time.Clock.system;
import static java.time.InstantSource.system;


public class Modulo1Impl{

    
    public static  void main(String[]args) {
   
        int num1=2;
        int num2=5;
        
 
System.out.println("El resultado al sumar es"+(num1+num2));
System.out.println("El resultado al restar es"+(num1-num2));
        System.out.println("El resultado al multiplicar es"+(num1*num2));
        System.out.println("El resultado al dividir es"+(num1/num2));
    }
}
public class EvaluacionesExpresiones {
    public static void main(String[] args){
        int M = 6;
        int T = 1;
        int K = -10;
        
        boolean expr1 = M > T;
        boolean expr2 = (T/K)==-5;
        boolean expr3 = (M+ T==7)||(M-T==5);
        
        System.out.println("M > T :"+ expr1);
        System.out.println("T / K==-5:"+expr2);
        System.out.println("(M + T== 7)||(M -T== 5):"+expr3);
    }
            
        
        
    }package com.mycompany.tare1;

import java.util.Scanner;

public class DatosCompaneros {
    public static void main(String[] args) {
        
        String[] nombres = new String[10];
                try (Scanner scanner = new Scanner(System.in)) {
            System.out.println("Ingrese 10 nombres de los compañeros:");
            for (int i = 0; i < 10; i++) {
                System.out.print("Nombre " + (i + 1) + ": ");
                nombres[i] = scanner.nextLine();
            }
            
            System.out.println("\nNombres de compañeros:");
            for (String nombre : nombres) {
                System.out.println(nombre);
            }
            
            
            String[][] datosPersonales = new String[5][4];
            
            System.out.println("\nIngrese datos personales de 5 compañeros (nombre, apellido, carrera, lugar de trabajo):");
            for (int i = 0; i < 5; i++) {
                System.out.print("Nombre: ");
                datosPersonales[i][0] = scanner.nextLine();
                System.out.print("Apellido: ");
                datosPersonales[i][1] = scanner.nextLine();
                System.out.print("Carrera: ");
                datosPersonales[i][2] = scanner.nextLine();
                System.out.print("Lugar de trabajo: ");
                datosPersonales[i][3] = scanner.nextLine();
            }
            
            
            System.out.println("\nDatos personales de compañeros:");
            for (int i = 0; i < datosPersonales.length; i++) {
                System.out.println("Nombre: " + datosPersonales[i][0]);
                System.out.println("Apellido: " + datosPersonales[i][1]);
                System.out.println("Carrera: " + datosPersonales[i][2]);
                System.out.println("Lugar de trabajo: " + datosPersonales[i][3]);
                System.out.println();
            }
        }
    }
}
    package com.mycompany.tare1;

import java.util.Scanner;

public class EstudianteNotas {
    public static void main(String[] args) {
        try (Scanner scanner = new Scanner(System.in)) {
            System.out.print("Ingrese el nombre del estudiante: ");
            String nombre = scanner.nextLine();
            
            System.out.print("Ingrese la nota: ");
            int nota = scanner.nextInt();
           
            String resultado = (nota >= 60) ? "Aprobado" : "Reprobado";
            
            System.out.println(nombre);
            System.out.println(nota);
            System.out.println(resultado);
        }
    }
}
    
    
package com.mycompany.tare1;
public class NumerosPares {
    public static void main(String[] args) {
        System.out.println("Números pares del 2 al 100:");
        for (int i = 2; i <= 100; i += 2) {
            System.out.println(i);
        }
    }
}
    

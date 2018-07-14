# Tareas-Totales
Ejercicio#1 
public class Hola{ 
 
    public static void main(String[] args) { 
        // Imprimimos en consola 
 
        System.out.println( 
            "Hola, " + 
            "Soy Belky Soriano "  
        ); 
    } 
} 
 
Ejercicio#2 
public class SumaNumeros{ 
    // Método principal 
    public static void main(String args[]){ 
        //Declaramos las variables 
        int numero1= 10; 
         
        int numero2= 10; 
         
        int suma= 0; 
         
        int resta= 0; 
         
        int multiplicacion= 0; 
         
        float division= 0; 
         
        float mod=0; 
         

 
 
        String mensaje1 = "La Suma es: ";     
        String mensaje2 = "La Resta es: "; 
               String mensaje3 = "La Multiplicacion es: "; 
                      String mensaje4 = "La Division es: "; 
                        String mensaje5="El mod es: "; 
        // Realizamos la Suma 
         
        suma= numero1 + numero2; 
        
       // Realizamos la Resta 
        
       resta= numero1 - numero2; 
        
       // Realizamos la Multiplicación 
        
       multiplicacion= numero1 * numero2; 
        
       // Realizamos la División 
        
       division= numero1 / numero2; 
        
       mod=numero1%numero2; 
         
        // Imprimimos en consola 
    System.out.println(mensaje1 + suma); 
    System.out.println(mensaje2 + resta); 
        System.out.println(mensaje3 + multiplicacion); 
        System.out.println(mensaje4 + division); 
        System.out.println(mensaje5 + mod); 
         
    } 
} 

 
 
Ejercicio#3 
public class Decision{ 
     
    public static void main( String[] args){ 
     
    // Declarar Variables 
     
    int M= 6; 
     
    int T= 1; 
     
    int K= -10; 
     
boolean a = (M>T)? true: false; 
System.out.println(a); 
 
boolean b= (T / K == -5)? true:false; 
System.out.println(b); 
 
boolean c= ((M+T == 7) || (M-T == 5))? true:false; 
System.out.println(c); 
 
    } 
} 
 
Ejercicio#4 
public class arreglo_nombres{ 
//Programa de un arreglo qupublic public class arreglo_nombres{ 
//Programa de un arreglo qupublic class arreglo_nombres{ 
//Programa de un arreglo que guarda e imprime 10 nombres de los compañeros 
     
    public static void main( String[] args){ 

 
 
        //Declaracion del Arreglo 
        String[] nombres= new String[10]; 
         
        nombres[0]= "ALBERTO VALDEZ OLIVA"; 
         
        nombres[1]= "DARWINS GILBERTO MARADIAGA"; 
         
        nombres[2]= "LUIS ERNESTO BROONFIELD"; 
         
        nombres[3]= "GERMAN GABRIEL MEDINA"; 
         
        nombres[4]= "SAUL FERNANDO MORENO "; 
         
        nombres[5]= "CARMEN NOEMI AVILA"; 
         
        nombres[6]= "LIZZIE MARIA POSAS"; 
         
        nombres[7]= "ROCIO VANESSA CASTELLANOS"; 
         
        nombres[8]= "MARIO ALEJANDRO FLORES"; 
         
        nombres[9]= "ELIZABETH MILLA MARTINEZ"; 
         
        //Imprimimos en Consola 
         
        System.out.println("Diez Nombres de Companeros:"); 
        System.out.println(nombres[0]); 
        System.out.println(nombres[1]); 
        System.out.println(nombres[2]); 
        System.out.println(nombres[3]); 
        System.out.println(nombres[4]); 
        System.out.println(nombres[5]); 

 
 
        System.out.println(nombres[6]); 
        System.out.println(nombres[7]); 
        System.out.println(nombres[8]); 
        System.out.println(nombres[9]); 
    } 
         
} 
 
Ejercicio#5 
public class Nota{ 
    // Método principal 
    public static void main(String args[]){ 
        //Declaramos las variables 
         
        String nombre="Carlos"; 
         
        int numero1= 68; 
         
        int numero2= 10; 
         
        int suma= 0; 
         
        int resta= 0; 
         
        // Decision 
         
        if(numero1>70){ 
        System.out.println(nombre  +  numero1  + "  Aprobado"); 
        } 
         
        else 
        { 

 
 
            System.out.println(nombre + numero1 + "Reprobado"); 
        } 
         
    } 
} 
 
Ejercicio#6 
public class fornumpares{ 
    // Método principal 
    public static void main(String args[]){ 
        //Imprime los datos del 1 al 100 de dos en dos 
  
    for(int i = 2; i<=100; i= i + 2){ 
     
    System.out.println("Los Numeros Pares son : " + i); 
        } 
         
    } 
} 
 
 
 
#Tarea 2
public class Program{ 
    public static void main(String arg[]){ 
      
  Operaciones operaciones = new Operaciones();//Instancia de la clase Operaciones 
   
  operaciones.saludo();    //Llamar los métodos en esa clase por medio de objeto operaciones 
  
  operaciones.dibujar(100); //Llamar el segundo método 
   
  operaciones.operar(10 + 10); //Llamar el tercer método 
 
  operaciones.crear(20); //Llamar el cuarto método 
   
  operaciones.calcular(10.2 - 2.1 - 1.3); //Llamar el quinto método 
   
  operaciones.producto(10.2 * 2.1 * 1.3);  
    } 
     
  public static class Operaciones { 
        //Método que no recibe parámetro de entrada ni retorna valor 
       
      public void saludo(){ 
          System.out.println("Soy el mejor programador"); 
                            } 
                             
                             
      public void dibujar(int nota){ 
          if (nota>=70){ 
              System.out.println("Aprobado"); 
                       } 
          else{ 
              System.out.println("Reprobado"); 

 
 
          } 
      } 
           
           
       public void operar(int sumar){ 
           System.out.println("La Suma es " + sumar); 
                          }      
            //Método que  recibe parámetro entero para imprimir un valor                 
                           
       public void crear(int lista){ 
         for(int i=1; i<=lista; i++){ 
             System.out.println("Lista " + i); 
         } 
       }   //Método que  recibe parámetro entero para imprimir un valor 
        
       public void calcular(double restar){ 
           System.out.println("La Resta es: " + restar); 
       } 
        
       public void producto(double multiplicar){ 
           System.out.println("La Multiplicacion es: " + multiplicar); 
       } 
 
     }   // Fin de la Clase Operaciones           
    } // Fin del Programa 
    Explicación 
Primero planteo el problema, el cual me dice que tengo que crear una clase, la cual luego tengo que instanciar, y después de eso dentro de la clase he creado varios métodos quienes tienen como función hacer distintas operaciones, en algunas he incluido el uso de ciclos y condiciones. He utilizado variables de tipo entero para trabajar con las operaciones: Suma, Resta y Multiplicación  
 
 
 #Tarea 3
 Encapsulamiento y Abstracción 

 
 
 
 
public class Abstraccion { 
 
    public static void main(String arg[]) { 
 
        /* 
        Declaración de la instancia 
        CalculadoraEnko. 
        */ 
      System.out.println("Calculadoras"); 
      System.out.println("=============="); 
      System.out.println("\n"); 
       
        CalculadoraEnko ce = new CalculadoraEnko(); 
 
        /* 
         Imprimir fabricante, tamaño, color, modelo abstrayendo 
        desde la clase Computadora. 
        */ 
   
         
         
        System.out.println("Fabricante:" + ce.getFabricante()); 
        System.out.println("Tamano:" + ce.getTamaño()); 
        System.out.println("Color:" + ce.getColor()); 
        System.out.println("Modelo:" + ce.getModelo()); 
        System.out.println("\n"); 
 
        /* 
        Declaración de la instancia 
        CalculadoraCasio. 

 
 
        */ 
 
            CalculadoraCasio cc = new CalculadoraCasio(); 
  
        /* 
        Imprimir fabricante,tamaño, color, modelo abstrayendo 
        desde la clase Computadora. 
        */ 
 
        System.out.println("Fabricante:" + cc.getFabricante()); 
        System.out.println("Tamano:" + cc.getTamaño()); 
        System.out.println("Color:" + cc.getColor()); 
        System.out.println("Modelo:" + cc.getModelo()); 
        System.out.println("\n"); 
 
        /* 
        Declaración de la instancia 
        CalculadoraDelta. 
        */ 
 
        CalculadoraDelta cd = new  CalculadoraDelta(); 
 
        /* 
        Imprimir fabricante,tamaño, color, modelo abstrayendo 
        desde la clase Computadora. 
        */ 
        System.out.println("Fabricante:" + cd.getFabricante()); 
        System.out.println("Tamano:" + cd.getTamaño()); 
        System.out.println("Color:" + cd.getColor()); 
        System.out.println("Modelo:" + cd.getModelo()); 
 
    } 

 
 
 
 
    /* 
    Declaración de la clase 
    abstracta Computadora 
 
    La clases abstractas se declaran de igual 
    forma que una clase, con la diferencia que 
    incluye abstract en su declaración. 
 
    Es importante saber que una clase abstracta 
    no puede instanciarse, solamente 
    extenderse (heredar) a otras. 
 
    Los métodos abstractos se declaran sin 
    implementación, únicamente con 
    su prototipo de función. 
 
    Por defecto, los métodos abstractos 
    son públicos. 
    */ 
 
    public static abstract class Computadora { 
 
        /* 
        Declaración del método abstracto 
        getcomputadora, donde en su extensión a subclases 
        requerirá su implementación al 
        objeto que pertenecen. 
        */ 
        abstract String getFabricante(); 
        abstract String getTamaño(); 

 
 
        abstract String getColor(); 
        abstract String getModelo(); 
 
    } 
 
 
    /* 
    Declaración de la clase CalculadoraEnko 
    que se extiende de la clase abstracta Computadora. 
    */ 
 
    public static class CalculadoraEnko extends Computadora { 
 
        /* 
        Implementación del método abstracto 
        getFabricante() que se extiende 
        desde la clase Computadora. 
        */ 
         
         
        public String getFabricante() { 
            return "ENKO"; 
        } 
         
        public String getTamaño(){ 
            return "4.5 x 6 cm"; 
        } 
         
        public String getColor(){ 
            return "Gris"; 
        } 
         

 
 
        public String getModelo(){ 
            return "KK8905A"; 
        } 
    } 
     
    /* 
    Declaración de la clase CalculadoraCasio 
    que se extiende de la clase abstracta Computadora. 
    */ 
 
    public static class CalculadoraCasio extends Computadora { 
 
        /* 
        Implementación del método abstracto 
        getFabricante() que se extiende 
        desde la clase Computadora. 
        */ 
       
        public String getFabricante() { 
            return "CASIO"; 
        } 
         
        public String getTamaño(){ 
            return "5 x 17 cm"; 
        } 
         
         public String getColor(){ 
            return "Azul"; 
        } 
         
        public String getModelo(){ 
            return "FX-82MS"; 

 
 
        } 
 
    } 
 
 
    /* 
    Declaración de la clase CalculadoaraDelta 
    que se extiende de la clase abstracta Computadora. 
    */ 
 
    public static class CalculadoraDelta extends Computadora { 
 
        /* 
        Implementación del método abstracto 
        getFabricante() que se extiende 
        desde la clase Computadora. 
        */ 
         
        public String getFabricante() { 
            return "DELTA"; 
        } 
         
        public String getTamaño(){ 
            return "5 x 8 cm"; 
        } 
         
         public String getColor(){ 
            return "Negro y Gris"; 
        } 
         
        public String getModelo(){ 
            return "DC1410"; 

 
 
        } 
 
    } 
}
#tarea4
public class Herencia { 
 
    public static void main(String arg[]) { 
        // Persona 1 heredada desde la super clase Persona. 
 
        System.out.println("-> Persona 1"); 
 
        // Instancia de la persona Empleado 
 
        Empleado e = new Empleado(); 
 
        // Imprimir la información de la persona empleado. 
 
        e.imprimirInformacion(); 
 
 
        // Persona 2 heredada desde la super clase Persona. 
 
        System.out.println("-> Persona 2"); 
 
        // Instancia de la persona estudiante. 
 
       Estudiante estd = new Estudiante(); 
 
        // Imprimir la información de la persona Estudiante. 
 
        estd.imprimirInformacion(); 
 
 
        // persona 3 heredada desde la super clase Persona. 
 
        System.out.println("-> Persona 3"); 

 
 
 
        // Instancia de la persona cliente. 
 
        Cliente c = new Cliente(); 
 
        // Imprimir la información de la persona Cliente 
        c.imprimirInformacion(); 
 
 
    } 
 
 
    /* 
    Declaracion de la super clase Persona, donde se definen 
    los atributos de una persona en general y heredaran las subclases 
    de otras personas. 
    */ 
 
    public static class Persona { 
 
        // Nombre de la persona. 
 
        private String nombre; 
 
        // apellido de la persona. 
 
        private String apellido; 
 
        // cedula de la persona. 
 
        private String cedula; 
 

 
 
        // telefono de la asignatura. 
 
        private int telefono; 
 
         
 
        // Constructor predeterminado de la clase. 
 
        public Persona() { 
            /* 
            Este constructor por defecto esta vacio, puede utilizarse 
            para la inicializacion de componentes de la clase, se demostrara 
            su uso en las subclases que hereden a esta clase. 
            */ 
        } 
 
        /* 
        Constructor con sobrecarga para la 
        inicializacion de la persona. 
        */ 
 
        public Persona(String nombre, 
                          String apellido, 
                         String cedula, 
                          int telefono) { 
            this.nombre = nombre; 
 
            this.apellido = apellido; 
 
            this.cedula = cedula; 
 
            this.telefono = telefono; 

 
 
 
        } 
 
 
        /* 
        Declaracion de los getters y setters 
        de cada variable miembro de la clase. 
        */ 
 
        public String getNombre() { 
            return this.nombre; 
        } 
 
        public void setNombre(String nombre) { 
            this.nombre = nombre; 
        } 
 
 
        public String getApellido() { 
            return this.apellido; 
        } 
 
        public void setApellido(String apellido) { 
            this.apellido = apellido; 
        } 
 
 
        public String getCedula() { 
            return this.cedula; 
        } 
 
        public void setCedula(String cedula) { 

 
 
            this.cedula = cedula; 
        } 
 
 
        public int getTelefono() { 
            return this.telefono; 
        } 
 
        public void setTelefono(int telefono) { 
            this.telefono = telefono; 
        } 
 
 
 
        /* 
        Metodo para imprimir la informacion 
        de la persona. 
        */ 
 
        public void imprimirInformacion() { 
            System.out.println(""); 
 
            System.out.println("Nombres: " + nombre); 
 
            System.out.println("apellidos: " + apellido); 
 
            System.out.println("Cedula: " + cedula); 
 
            System.out.println("Telefono: " + telefono); 
             
            System.out.println(""); 
        } 

 
 
 
    } 
 
     
    /* 
    Declaracion de la clase empleado que hereda todos los 
    atributos de la superclase persona mediante: extends Persona 
    en su declaración. 
    */ 
 
    public static class Empleado extends Persona { 
 
        public Empleado() { 
            /* 
            Inicializacion de la clase Empleado mediante 
            los setters definidos en la superclase persona, con 
            los valores de la persona:Empleado. 
            */ 
 
            setNombre("Carlos Manuel"); 
 
            setApellido("Alvarado Lopez"); 
 
            setCedula("0502199102694"); 
 
            setTelefono(96895623); 
 
             
        } 
 
 
    } 

 
 
 
 
     
 
    public static class Estudiante extends Persona { 
 
        public Estudiante() { 
          
 
            super("David Josue", "Rodriguez Romero","0502199600236",96245680); 
        } 
 
    } 
 
 
     
 
    public static class Cliente extends Persona { 
 
        public Cliente() { 
         
 
            setNombre("Isaac Alejandro"); 
 
            setApellido("Fernandez Aparicio"); 
 
            setCedula("0502198803981"); 
 
            setTelefono(99367854); 
 
        } 
 

 
 
    } 
 
} 
 
 #tarea5
 La Programación Orientada a Objetos Es un paradigma de la Programación actualmente más utilizada por los desarrolladores, creadores de sistemas e innovadores de la tecnología. Como su nombre lo dice, es un nuevo modelo para programar, ya que ésta consta de Objetos que se relacionan a los objetos reales, de esta maneara se puede apreciar que es un paradigma que tiene muchas ventajas a diferencia de la programación Estructurada y la Programación Procedural. Se caracteriza por tener un modelo de programación bien estructurado y que está compuesto por estos y otros fundamentos importantes: 
 
Encapsulamiento: El encapsulamiento nos sirve para ocultar o proteger códigos de clases que no queremos usarlos en ninguna otra parte, los podemos usar a nuestra preferencia. Esto es un fundamento bien importante, por estas y otras características es que este paradigma es muy seguro. 
 
Herencia: Esta nos sirve para reutilizar códigos y así no tener que estar documentando las mismas cosas. 
 
Polimorfismo: Es una relación entre la herencia, es cuando queremos que una clase padre pueda relacionarse con sus Subclases. 
 
Es recomendable manejar el tema de la programación orientado a objetos, permite conocer como está evolucionando la tecnología, aprender a crear a soluciones que se nos presentan de vez en cuando, la POO nos ayuda a nosotros como programadores tener un contacto más directo con las maquinas, y relacionar los dichos objetos, cabe mencionar que todo sitio web y la mayoría de aplicaciones son creadas con el Paradigma de POO, por la razón que brinda mejor desarrollo, la rapidez de un software es notable, la manera de dar resultados es muy buena, las Empresas Grandes han dado a mostrar al mundo lo poderosa en que se está convirtiendo, porque por ahora solo está en un proceso de transformación, cada día muchos desarrolladores se inventan algo nuevo para su mejor aplicación. 
 
 Al momento de querer comenzar con el desarrollo de un Sistema, con orientación a Objetos, primero se tiene que plantear un análisis que facilitará las siguientes fases de creación, por el motivo que ya se tendrá definido como es que funcionará el Sistema luego de eso se tiene que crear un algoritmo, luego diseñar y documentar el código. Para crear un software se tiene que pasar por muchos procesos lo cuales concluyen con la implementación, es donde el desarrollador verifica si éste funciona, aparte 
de eso, hay que tener claro, cuando ya está listo, bueno eso pensamos en ese momento, soy consciente que se tienen que hacer todas las pruebas posibles, las muchas funciones y manera de resolver, porque se han dado casos, que mínimas equivocaciones pueden ocasionar grandes problemas, por lo que, luego esto genera problemas tanto como para el desarrollador como para dicho usuario o empresa, pero el que más sale afectado es el programador. 
 
El paradigma de Programación Orientado a Objetos se popularizó en los principios de la década de los noventa, desde ese entonces se ha conocido como la mejor forma de programar, tiene muchas ventajas ya antes mencionadas, pero aparte ésta se divide en muchas partes, al inicio para quienes venimos comenzando con la programación es algo difícil entender estos conceptos, pero a medida los usamos de manera gráfica nos va aclarando las dudas que tenemos, tiene varias ventajas porque es un paradigma que poco a poco podemos ir relacionando los conceptos. Queda claro que nos es fácil, es algo complejo, por el motivo que es muy potente. 
 
La programación en sus inicios fue creada de forma secuencial o lineal, este tipo de codificación en un principio presentó muchas ventajas, pero con la evolución de los sistemas y la nueva tecnología más su complejidad tan extensa con capacidades aun de mayor demanda por las empresas por lo tanto estos sistemas no ofrecían flexibilidad e identificar un problema se convertiría en toda una aventura. Por eso ahora en día la programación estructurada y la programación lineal no basta y nos de tanta competencia, por lo cual nació la programación orientada a objetos.  
 
La POO viene de la evolución de la programación estructurada, básicamente simplifica la programación con la nueva filosofía y nuevos conceptos y funciones que tiene, las cuales le permiten un complejo desarrollo de softwares, por lo que, esta tecnología es capaz de satisfacer las necesidades, en la programación con mi criterio pienso que siempre se trata de hacer las cosas mejor, y la evolución de la poo nos ha beneficiado en eso, porque en la actualidad existen sistemas inteligentes, también conocida como la inteligencia artificial, son tan perfectos estos sistemas que ayudan mucho a la humanidad, hay tecnologías que se pueden usar en distintas áreas como un beneficio, por ejemplo; hospitales, centros educativos, para investigación de múltiples incógnitas. En conclusión, la programación Orientada a Objetos es la herramienta que los programadores han desarrollado ante la evolución y complejidad de los sistemas de información. Cabe volver a mencionar que cuenta con funciones que dan facilidad para el mantenimiento de estos sistemas, como los es la reutilización de código, a través de la herencia, la seguridad a través del 
encapsulamiento, en realidad esto es lo que necesitamos de un sistema que contiene y procesa bastante información, como lo son los sistemas bancarios y otros. 
 
 
 

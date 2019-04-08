## Tipos de datos: 

// Byte. Hasta 255 

Byte variable00 = 255 ; 


//Char. Solo un carácter 

Char variable01 =  ‘W` ; 


//Int. Entero. Un número negativo o positivo sin decimales. 

Int variable02 =  2004 ; 


//Double. Con decimales. 

Double variable03 = 2004.7009 ; 
 

// Bool. Booleano. Verdadero (0) o Falso (1). 

Bool variable04 = True ; 


//Enum. Enumeración listada. 

Enum variable05 = { Lunes, Martes, Miercoles, Jueves, Viernes} 


//String. Tipo de texto. 

String variable06 = “Cadena de Texto” 


Concatenar variables y texto: 

 

// Se usa el símbolo + 

Console.WriteLine( “Una frase” + variable03 + “ otra frase”) ; 


## Operadores de asignación: 
 

// Dar valor a una variable = 

Byte variable01 = 24 ; 


//Sumar a una variable. Método clásico. Convertirlo. 

Byte variable01 = 24 ; 

Variable01 = Convert.ToByte( edad + 10) ; 
 

//Sumar a una variable. Método 2. operadores.  

Byte variable01 = 24 ; 

Variable01 += 10 ; 
 

//Restar, multiplicar, dividir... 

 

## Operadores aritméticos: 

 

Es lo mismo: 

Int num = 5 ; 

Int otronum = 65 ; 

Que: 

Int num=5, otronum=65 ; 

 

//Operaciones Sencillas 

Int num=5, otronum=65 ; 

Console.WriteLine(“El resultado suma es “+ (num + otronum)) ; 

Console.WriteLine(“El resultado resta es “+ (num - otronum)) ; 

 

 

//Operaciones avanzadas con Math. Y comvertidas para decimales 

Doble numero, potencia, resultado ; 

Console.WriteLine(“Escribe el numero a elevar”); 

Convert.ToDoble(Console.ReadLine(numero)); 

Console.WriteLine(“Escribe a lo que elevar”); 

Convert.ToDoble(Console.ReadLine(potencia)); 

Console.WriteLine(“El resultado de elevar es “+ resultado ; 

 

Math.Pow(numero,potencia) = resultado ; 

Console.WriteLine(resultado); 

 

Operadores relacionales y lógicos: 

 

//Operadores relaciones. Para comparar. 

//Mayor 

> 

//Menor 

< 

//Mayor o igual 

>= 

//Menor o igual 

<= 

//Diferencia 

!= 

//Igualdad 

== 

 

//Operadores lógicos. Para comparar varias cosas. 

//AND. Ambas cosas se tienen que cumplir. 

&& 

//OR. Si una cosa se cumple llega. 

|| 

 

Estructuras de control (condicionales): 

 

//If simple 

If () {} 

Else {} 

 

If ( edad < 19) { Console.WriteLine(“Tiene menos de 19);} 

Else { Console.WriteLine(“Tiene más de 19);} 

 

//Try … catch. Para errores. 

Try {} 

Catch () {} 

 

Try {} 

Catch ( Exception error) {Console.WriteLine(Error.Message);} 

 

//Switch.  

Switch (){} 

 

Switch (dia){ 

case 1: Console.WriteLine(“Ha elegido Lunes”); break; 

case 2: Console.WriteLine(“Ha elegido Martes”); break; 

case “Miercoles”: Console.WriteLine(“Ha elegido Miercoles”); break; 

default :Console.WriteLine (“No reconocido”); break; 

} 

 

Ciclos: 

 

//For simple. Repetir acciones. 

For (){} 

 

For ( int x; x<=5; x++){ 

Console.writeline (x); 

} 

 

//foreach 

String nombre = “Luis” 

Foreach (char letra in nombre) { 

Console.Write( “ “ + letra + “ “); 

} 

 

Expresiones break, continue, goto: 

 

//break 

For ( int id; id <=5; id++) { 

Console.WriteLine(id); 

If (id==2) { 

Break; 

} 

} 

 

//Contiue 

For ( int id; id <=5; id++) { 

If (id==2) { 

Continue; 

} 

Console.WriteLine(id); 

} 

 

//Goto 

 

For ( int id; id <=5; id++) { 

If (id==2) { 

Goto liquidacion; 

} 

Console.WriteLine(id); 

} 

 

Liquidacion: 

Console.WriteLine(“Se envio”); 

 

// While. Repetir instrucción mientras sea verdadera. Validar antes. 

 

 

//DoWhile 

 

 


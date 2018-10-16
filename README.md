﻿#  Informe Python --------------------##Que es Python ?Python es un lenguaje de programación,  creado por Guido van Rossuma principios de los años 90. Es un lenguaje **interpretado o de script**, con **tipado dinámico**, **multiplataforma** y orientado a objetos.La característica de tipado dinámico se refiere a que no es necesariodeclarar el tipo de dato que va a contener una determinada variable, sino que su tipo se determinará en tiempo de ejecución según el tipodel valor al que se asigne, y el tipo de esta variable puede cambiar si sele asigna un valor de otro tipo.Es multiplataforma ya que esta disponible tanto como para Linux, Windows y Mac Os, etc.##Impresión por pantalla:En Python para imprimir mensajes por pantalla se utiliza la palabra **print** de la siguiente manera:	print ("hola,mundo")Para dar un salto de linea escribimos los mismo sin comillas ni texto dentro. 	print()También podemos imprimir variables:	nombre=Lucas	Edad= 24	print ("escribe tu nombre" , nombre, "y tengo", edad, "años.")----------## Tipos Básicos:En Python existen varios tipos de datos uno de ellos son los números, que pueden ser **enteros**(1,2,3..).También pueden ser con coma o **decimales** (14.8) y los llamados **complejos** (5+6j).También existen las cadenas de textos llamadas **string**, que como su nombre lo dice puedes escribir palabras u oraciones como por ejemplo el famoso "hola mundo".Para determinar si un valor es verdadero (true) o falso (false), existen el tipo booleanos.Estos son los distintos tipos de operadores con los que podemos trabajar con valores booleanos,llamados operadores lógicos o condicionales: **Operadores**:- **and**: Que significa "y" ,en español, el resultado es verdadero si ambas expresiones son verdaderas-  **or**: Que significa "o", en español, el resultado es verdadero si alguna de las expresiones es  verdadera - **not**:  Es la negación de una expresión- **==**: Nos dice si un valor es igual a otro.(5==3 = false)- **=!** : Nos dice si un valor es distinto de otro(2=!4 = true)- **<** : Nos dice si un valor es menor que otro (4<3 = false)- **>** : Nos dice si un valor es mayor que otro (5>2 = true)- **<=** : Nos dice si un valor es menor o igual que otro (4<=4 =  true)- **>=** : Nos dice si un valor es mayor o igual que otro (7>=9 = false)Y también están los operadores aritméticos que son la suma (+) , resta (-), multiplicación, división, modulo  y división entera, estos dos últimos nos devolvería el resto y el resultado de la división exacta respectivamente. --------------------##ListasPython también cuenta con lo que se conoce como **Listas** que son lo que nosotros conocemos como arrays o arreglos.Las mismas pueden contener cualquier tipo de dato (números, cadenas, booleanos, etc. ). Para crear una lista escribimos:	*nombre de la lista* =[*elementos de la lista*] ----------Las listas nos ofrecen mecanismos mas cómodos para ser modificadas a través de las funciones de la clase correspondiente.----------##TuplasLas tuplas son secuencias al igual que las listas, pero su diferencias con las listas es que las tuplas son estáticas y inmutables, es decir, que no se pueden modificar sus valores y tienen un tamaño fijo, lo que nos permite darle un uso mas básico por ejemplo en una colección, podemos utilizarlas en vez de una lista y de esta manera ahorrar memoria.Esta es la manera de crear una tupla:	t = (1, 2, True, “python”)----------##Diccionarios o matrices Los diccionarios o matrices son colecciones que relacionan una clave y un valor, el primer valor se trata de la clave y el segundo del valor asociado a la clave. El valor de la clave puede ser cualquier valor inmutable, un número, cadena ,booleano, tupla, pero no listas o diccionario ya que son mutables.La diferencia principal entre los diccionarios y las listas o las tuplas esque a los valores almacenados en un diccionario se les accede no por suíndice, porque no tienen orden, sino por su clave utilizando el nuevo operador [].--------------------
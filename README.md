# Introducción

1. [Introducción ](#schema1)
2. [Instalacción](#schema2)
3. [Variables](#schema3)
<hr>

<a name="schema1"></a>

# 1. Introducción
`Scala` es un lenguaje multi-paradigma y compilado. Soporta los paradigmas más importantes.
**Paradigma funcional:** Programación basada en funciones
**Paradigma POO:** Programación basada en programación orientada a objetos.

Es  lenguaje más potente para el tratamiento de datos masivos o Big Data.
<hr>

<a name="schema2"></a>

# 2. Instalacción
1º Instalar Java:
Comprobamos que no tenemos ninguna versión de java instalada
~~~
java -version
~~~
Si tenemos instalada alguna versión perfecto, seguimos al siguente paso, sino:
~~~
sudo apt-get update
sudo apt-get install default-jdk
~~~
2º Instalar Scala
~~~
sudo apt-get install scala
~~~
Comprobamos que se ha instalado correctamente
~~~
scala
scala>println("Hello World")
~~~
![Scala](./image/001.png)
Para salir del modo Scala REPL 
~~~
:q
~~~
3º Insalar Spark

4º Instalar Apache Zeppelin

  - Ir a http://zeppelin.apache.org/download.html y descargar la versio que ponga `all`
  - Descomprimir el archivo.
  -  Naverga en la terminal hasta donde se descomprimió el archivo.
  - y ejecutar  para comprobar que está funcionando
   ~~~
   bin/zeppelin-daemon.sh start
   ~~~
  

   ![zeppelin](./image/002.png)
  - Comprobamos que el servidor web esta funcionando vamos a `localhost:8080` puerto por defecto.
  ![zeppelin](./image/003.png)
  - Crear nuevo nota, ir a `Create new note` y ponerle el nombre que quieras. Y se nos abre un notebook nuevo
   ![zeppelin](./image/004.png)


   - Para parar el servidor web
   ~~~
   bin/zeppelin-daemon.sh stop
   ~~~

<hr>

<a name="schema3"></a>

# 3. Variables
**val nombre_variable : tipo_datos = valor**

~~~scala
val hola : String = "Hola"
~~~
![scala](./image/008.png)
**Concatenar**

~~~scala
val saludos : String = hola + " hello"
~~~
**Tipos de datos**
![scala](./image/005.png)
~~~scala
val edad : Int = 35
~~~
![scala](./image/006.png)
~~~scala
val casado: Boolean = true
~~~
![scala](./image/007.png)


En el caso del tipo de datos `Float` por defecto ponene `Double` que es el hermano mayor de los floats
Si los queremos `Float` al valor hay que añadirle una `f`
~~~scala
val altura : Float = 1.75
~~~

![scala](./image/011.png)
**Comentarios**

Para poner comentarios en `Scala` se usan las barras `//`
~~~scala
// otros tipos de variables : Float, Long, Char, Byte
~~~

**val nombre_variable : tipo_datos = expresión**

~~~scala
val esMayorQue : Boolean = 1 > 2
~~~
![scala](./image/009.png)

~~~scala
val esMayorQue : Boolean = 1 < 2
~~~

![scala](./image/010.png)



















Enlaces 
Insatalación
(https://medium.com/@josemarcialportilla/installing-scala-and-spark-on-ubuntu-5665ee4b62b1)
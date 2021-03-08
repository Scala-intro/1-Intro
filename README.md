# Introducción

1. [Introducción ](#schema1)
2. [Instalacción](#schema2)

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





Enlaces 
Insatalación
(https://medium.com/@josemarcialportilla/installing-scala-and-spark-on-ubuntu-5665ee4b62b1)
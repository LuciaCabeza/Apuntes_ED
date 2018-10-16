#INTRODUCCIÓN

**1. ¿Para que sirve un compilador? ¿Qué tipo de archivo obtenemos tras compilar?**
Un compilador es un programa informático que traduce un programa escrito en un lenguaje de programación a otro lenguaje de programación, generando un programa equivalente que la máquina será capaz de interpretar. Usualmente el segundo lenguaje es lenguaje de máquina, pero también puede ser un código intermedio (bytecode), o simplemente texto. Este proceso de traducción se conoce como compilación.
Tras compilar obtenemos un archivo ejecutable.

**2. ¿Para que sirve un enlazador? ¿Qué tipo de archivo obtenemos tras enlazar?**
Es un programa que toma los objetos generados en los primeros pasos del proceso de compilación, la información de todos los recursos necesarios (biblioteca), quita aquellos recursos que no necesita, y enlaza el código objeto con su(s) biblioteca(s) con lo que finalmente produce un fichero ejecutable o una biblioteca. En el caso de los programas enlazados dinámicamente, el enlace entre el programa ejecutable y las bibliotecas se realiza en tiempo de carga o ejecución del programa.
Obtenemos un programa ejecutable.

 **3. ¿Para que sirve un interprete? ¿Obtenemos algún archivo tras interpretar?**
 Un intérprete es un programa que ejecuta línea a línea las instrucciones de un programa de alto nivel. El intérprete carga el código fuente y traduce las instrucciones a un lenguaje intermedio que puede luego ser ejecutado.

Los intérpretes generan un código binario que se interpreta cada vez que se ejecuta el programa a diferencia del compilador que crea un archivo ejecutable.
 
**4. Explica cada uno de los siguientes conceptos e indica la relación entre ellos.**
- **código fuente**:
El código fuente de un programa está escrito por un programador en algún lenguaje de programación, pero en este primer estado no es directamente ejecutable por la computadora, sino que debe ser traducido a otro lenguaje o código binario; así será más fácil para la máquina interpretarlo
- **código objeto**
Se llama código objeto al código que resulta de la compilación del código fuente. Puede ser en lenguaje máquina o bytecode, y puede distribuirse en varios archivos que corresponden a cada código fuente compilado. Luego un enlazador se encarga de juntar todos los archivos de código objeto para obtener el programa ejecutable.
- **código binario**
El código binario es un método de representación de números a la base 2, en el que cada lugar de un número corresponde a una potencia de 2. El código binario usa sólo los dígitos 1 y 0 (conocidos como dígitos binarios, o "bits") y combina esos dígitos para producir diferentes números binarios Casi todas las computadoras usan el código binario porque es fácil de implementar usando la electrónica digital y el álgebra Booleana, en las que las variables sólo tienen los valores 1 y 0.

**5. ¿Qué tipo de código es el bytecode generado por el compilador de Java?**
El bytecode Java es el tipo de instrucciones que la máquina virtual Java espera recibir, para posteriormente ser compiladas a lenguaje de máquina, mediante un compilador JIT a la hora de su ejecución. Usualmente es el resultado de utilizar un compilador del lenguaje de programación Java (como javac), pero puede ser generado desde otros compiladores. 

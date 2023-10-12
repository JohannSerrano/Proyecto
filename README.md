
 ![Logo Java](https://seeklogo.com/images/J/java-logo-7833D1D21A-seeklogo.com.png)

<!-- Se realizo un cambio en el titulo del proyecto -->
**# REGISTRO DE MATERIAS Y NOTAS**

Este proyecto consiste en hacer un registro de notas en diferentes asignaturas por medio de Java script.

<!-- se modifico la parte de empezando -->

_## Empezando_

Estas instrucciones te permitiran llevar un registro de las notas en las materias deseadas esto con el fin de llevar un buen orden academico

<!-- cambios en requisitos previos -->

_### Requisitos previos_

Tener el lenguaje de programacion "eclipse" en el computador que vayas a trabajar; adjunto el link del software 

<!-- Se inserto el logo -->

![Logo Eclipse](https://branditechture.agency/brand-logos/wp-content/uploads/2023/05/Eclipse-IDE.png)

<!-- enlace de eclipse -->

https://www.eclipse.org/downloads/packages/release/indigo/sr2/eclipse-ide-javascript-web-developers

<!-- Cambios en instalacion -->

_### Instalación_

Estos son los codigos que vamos a utilizar en cada caso:


##Para imprimir un mensaje: 

JOptionPane.showMessageDialog(null, "-Mensaje", "Titulo", -1;)

<!-- Segundo cambio en instalacion -->

##Para Crear una contendora:

La Estructura es:
Tipo de variable la variable []=new String["Cantidad de datos a almacenar"];
String asignatura[]=new String[5];

<!-- Tercer cambio en instalacion -->

##Condicional for:

La estructura es:
for(Inicializacion;Expresion Booleana;Actualizacion){
}
for (int i=1; i<=12; i++) { 
}

_## Ejecutando las pruebas_

Explicar cómo ejecutar las pruebas automatizadas para este sistema.

<!-- Se realizo un cambio en la division de pruebas -->

_### Dividir en pruebas de principio a fin_

A continuacion se muestra el paso a paso de las pruebas ejecutadas: 

*Paso 1: Crear un menu a modo de contenedora para que reciba la información que el usuario le de:
   
	String asignatura[]=new String [5];
	        asignatura[0]="Sociales";
		    asignatura[1]="Español";
	        asignatura[2]="Matematicas";
	        asignatura[3]="Ingles";
            asignatura[4]="Religion";
		
*Paso 2: Mostrarle al usuario la lista de las asignaturas que tiene la contenedora:

    JOptionPane.showMessageDialog(null, "Las notas de las asignaturas son:\n"+asignatura[0]+"\n"+asignatura[1]+"\n"+asignatura[2]+"\n"+asignatura[3]+"\n"+asignatura[4]);

*Paso 3: Se crea una condición para guardar los datos que el usuario ingrese, también se le pide el ingreso de la nota correspondiente a cada asignatura:

		float notas[]=new float [5];
		for (int i=0;i<5;i++) {
		notas[i]=Float.parseFloat(JOptionPane.showInputDialog(null,"Pon las notas de las asignaturas\n"+asignatura[i]));
			}


*Paso 4: Se muestra a manera de mensaje el nombre de las asignaturas y las notas agregadas por el usuario en forma de lista:

    JOptionPane.showMessageDialog(null, "Las notas de las asignaturas son:\n"+asignatura[0]+"="+notas[0]+"\n"+asignatura[1]+"="+notas[1]+"\n"+asignatura[2]+"="+notas[2]+"\n"+asignatura[3]+"="+notas[3]+"\n"+asignatura[4]+"="+notas[4]+"\n");

<!-- Cambios en la descripcion del programa utilizado -->
_## Construido con_
    ![Logo Java](https://media.imgcdn.org/repo/2023/03/eclipse-ide-for-java-developers/eclipse-logo.png)     Eclipse IDE for Java Script

<!-- Cambio en la version del programa utilizado -->
_## Versionado_
Se utilizo la version de Eclipse IDE for Java Developers-2023-06

<!-- Se realizaron cambios en autores y expresiones de gratitud -->
_## Autores_
* *Johan Serrano*
* *Karen Erazo*

_## Expresiones de gratitud_
* Aprovechar las herramientas que tenemos a nuestro alcance.
* Este proyecto fue realizado con el acompañamiento del Docente Mauricio Lopez.


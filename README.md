
 ![Logo Java](https://seeklogo.com/images/J/java-logo-7833D1D21A-seeklogo.com.png)

<!-- Se realizo un cambio en el titulo del proyecto -->
**# REGISTRO DE MATERIAS Y NOTAS**

Este proyecto consiste en hacer un registro de notas en diferentes asignaturas por medio de Java script.

_## Empezando_

Estas instrucciones le permitirán obtener una copia del proyecto en funcionamiento en su máquina local para fines de desarrollo y prueba. Consulte implementación para obtener notas sobre cómo implementar el proyecto en un sistema en vivo.

_### Requisitos previos_

Qué cosas necesitas para instalar el software y cómo instalarlas


Give examples


### Instalación

Una serie de ejemplos paso a paso que le indican cómo ejecutar un entorno de desarrollo.

Di cuál será el paso.


Give the example


Y repetir


until finished


Termine con un ejemplo de cómo sacar algunos datos del sistema o usarlos para una pequeña demostración.

## Ejecutando las pruebas

Explicar cómo ejecutar las pruebas automatizadas para este sistema.

<!-- Se realizo un cambio en la division de pruebas -->

### Dividir en pruebas de principio a fin

A continuacion se muestra el paso a paso de las pruebas ejecutadas: 

Paso 1: Crear un menu a modo de contenedora para que reciba la información que el usuario le de:

	String asignatura[]=new String [5];
	        asignatura[0]="Sociales";
		    asignatura[1]="Español";
	        asignatura[2]="Matematicas";
	        asignatura[3]="Ingles";
            asignatura[4]="Religion";
		
Paso 2: Mostrarle al usuario la lista de las asignaturas que tiene la contenedora:

    JOptionPane.showMessageDialog(null, "Las notas de las asignaturas son:\n"+asignatura[0]+"\n"+asignatura[1]+"\n"+asignatura[2]+"\n"+asignatura[3]+"\n"+asignatura[4]);

Paso 3: Se crea una condición para guardar los datos que el usuario ingrese, también se le pide el ingreso de la nota correspondiente a cada asignatura:

		float notas[]=new float [5];
		for (int i=0;i<5;i++) {
		notas[i]=Float.parseFloat(JOptionPane.showInputDialog(null,"Pon las notas de las asignaturas\n"+asignatura[i]));
			}


Paso 4: Se muestra a manera de mensaje el nombre de las asignaturas y las notas agregadas por el usuario en forma de lista:

    JOptionPane.showMessageDialog(null, "Las notas de las asignaturas son:\n"+asignatura[0]+"="+notas[0]+"\n"+asignatura[1]+"="+notas[1]+"\n"+asignatura[2]+"="+notas[2]+"\n"+asignatura[3]+"="+notas[3]+"\n"+asignatura[4]+"="+notas[4]+"\n");

<!-- Cambios en la descripcion del programa utilizado -->
## Construido con

Eclipse IDE for Java Script
<!-- Cambio en la version del programa utilizado -->
## Versionado

Se utilizo la version de Eclipse IDE for Java Developers-2023-06

<!-- Se realizaron cambios en autores y expresiones de gratitud -->
## Autores

* *Johan Serrano*
* *Karen Erazo*


## Expresiones de gratitud

* Aprovechar las herramientas que tenemos a nuestro alcance.
* Este proyecto fue realizado con el acompañamiento del Docente Mauricio Lopez.


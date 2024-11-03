# Tarea 1: inicialización en Git

### **Descripción:**

Esta tarea consistio en darnos una introduccion a Git, Git  es un Sistema de Control de Versiones Centralizados (CVCS), para que nosotros podamos crear y subir repositorios de proyectos y familiarizarnos con este tipo de herramientas que nos facilitan el crear software.

Cree mi mi programa **"HolaMundo.java" y lo que hacia era impriir *"Hola mundo"* y depues lo modifique para que imprimiera *"Hola Git"*, estos cambios estan comentados y declarados en los commits de mi repositorio *"Tarea 1"*.

### **Instrucciones de uso:**

Para ejecutar el código debes de:

 *i)* descargar ó compiarel código(si lo copiaste nombrar el archivo fuente com *"HolaMundo.java"*).
 
 *ii)* importante tener l copilador JDK para que pueda ejecutarse.

 *iii)* ir a la terminal del sistema y abrir la carpeta donde se este guardando el archivo con el código fuente ("*HolaMundo.java"*)

 *iv)* escribir **"JAVAC HolaMundo.java"** para que se compile el progrma.

 *v)* para ejecutar escribe **"Java HolaMundo"**.

 ### **Comandos utilizados:**

 1. *cd "Directorio del proyecto"*
 2. *git init*
 3. *ls -al*
 4. *touch .gitignore*
 5. *git add -A* y *git add "Nombre del archivo"*
 6. *git commint -m "mensaje del commit*
 7. *git push "Alias" = **origin** NOMBRE-RAMA*
 8. *git status*

 ### **Notas sobre el archivo *.gitignore*:**

 Este archivo se crea para ignorar el archivo *"debug.log"*, porque no es necesario subirlo al repositorio puesto que no afecta el funcionamiento de nuestro código fuente. En este caso el archivo *".gitignore"* ignora todos los archivos *".log"* como se ve e el repositorio.

 ##### **Al ejecutar el programa *"HolaMundo.java"* Nos aparecerá en la terminal un *"Hola Git".***


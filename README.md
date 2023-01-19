# CONFLICTOS EN GITHUB

## Ejemplo de funcionamiento de Git

 * Crear un proyecto en IntellIJ IDEA
 * Crear archivo README
 * Crear archivo '.gitignore' para no subir metadatos. 

## Conflictos en github
  Antes de subir cambios actualizar proyecto con Update Project ( Ctrl+T)
   ![[Update.png]]  Update Project = flecha azul

  Una vez tengamos una parte del proyecto modificado hacer:
  Hacer Commit
  Seleccionar archivos a subir
  Introducir una breve descripción de los cambios para que se entiendan
  * Commit and Push
  ![[commit.png]]
* Hacemos Push 
![[Push.png]]

* La siguiente pantalla nos indica que se ha detectado un conflicto

![[Push Rejected.png]]

El boton Merge (fusionar) intentará fusionar los conflictos y autocorregirlos

Si no puede saltará la siguiente pantalla
![[conflicts.png]]
Nos muestra el conflicto, puede que haya conflictos en más de archivo, ls resolveríamos de uno en uno, y nos da la opción de:
   * Aceptar nuestros cambios
   * Aceptar sus cambios (los del equipo)
   * Merge (fusionar)

Vamos a fusionar

![[revision.png]]

Desde esta pantalla dividida en tres podemos aceptar el código de la izquierda, el de la derecha, o usar la pantalla central para corregir el código a subir.
Si no queremos el código de alguno de los lados se descartan con la X.
Si los queremos se agregan con >> o <<
Nos aseguramos que el código central esta correcto.
Quedaría así:
![[solucion.png]]

Entonces ya podemos dar a Apply
![[apply.png]]

Hacemos Push y el código quedará subido a github con el conflicto resuelto.

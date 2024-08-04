¡Bienvenida a la introducción a Git y GitHub!

Este material ha sido creado por Juan Camilo Rodríguez Portilla, Monitor de APO 2, bajo la supervisión del profesor Loaiza.


-------------------------------------------------------------/* SECCION I */-----------------------------------------------------------------

--INTRODUCCIÓN A GIT:

Git es una herramienta de control de versiones distribuido que permite a los desarrolladores gestionar y seguir los cambios en el código de un
proyecto. Es como un historial para tu código, ayudándote a regresar a versiones anteriores si es necesario.

Fue creado por Linus Torvalds en 2005, y su diseño se enfoca en la velocidad, la integridad de los datos y la compatibilidad con flujos de trabajo 
distribuidos.



--¿QUE ES GIT? (Explicado de forma didactica):


Digamos que un proyecto en Git es como tener nuestro propio "árbol" donde la raiz principal va a ser la base de tu codigo de tu proyecto, esa raiz 
se llamara "Main" o "Master", esto quiere decir que va a ser la rama principal de nuestro "árbol". 

Esta rama puede seguir creciendo y creciendo... eso quiere decir que puede ir cambiando de version en tu proyecto mediante "cambios" o "changes" 
y preparando esos cambios a la rama principal o tambien llamado "add changes". 

Finalmente podras llevar esos cambios a la rama principal "main" a este proceso se le llama "commit" y asi poder crecer tu árbol o proyecto y tener
un historial de tu árbol o tambien llamado "versiones" anteriores de tus cambios agragados o tambien llamado "log".


--ILUSTRACION:
(Árbol horizontal)

---
--------
"RAMA MAIN" --> add changes ---> commits ---> "MAIN VERSION 1" add changes  ----> commits ---> "MAIN VERSION 2"-------->
--------
---


--USO DE RAMAS EN EQUIPO

Recordemos que los arboles tienen "ramas" no solo es una rama en concreto, estas ramas son copia de tu rama principal o "main" donde podras hacer 
tambien hacer cambios pero que no afecten a tu rama "main" de tu proyecto ya que es la version final y estable del proyecto.

NOTA: Las ramas adicionales son útiles para el trabajo en equipo, ya que permiten dividir tareas y realizar cambios de manera independiente. De
este modo, puedes hacer modificaciones y probarlas sin afectar la rama principal "main"

Nadie quiere que corte o dañe tu rama 'main' por que es la raiz de nuestro proyecto entonces es mejor hacer copias de esa rama principal y ir 
haciendo las pruebas para cuando se verifique que todo esta correcto pueda que esa rama se "una" o haga "merge" y asi implementarla a
la rama "Main" y que sea un nuevo cambio o version del proyecto.


--ILUSTRACION 2:
(Árbol horizontal)

---             /*Create Rama Secundaria* --> *add changes* --> *commits* \ 
--------       /                                                           \*Merge*
"RAMA MAIN" --------------------------------------------------------------> "MAIN VERSION 2"------>
--------
---


Con esta introducción, ahora estás listo para implementarlo. Por favor, dirígete a la sección 2: INSTALACIÓN Y USO DE GIT en este repositorio.
 
-------------------------------------------------------------------------------------------------------------------------------------------------------


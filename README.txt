## Reglas para el correcto uso de git.
A). Se debe trabajar la tarea seleccionada en una nueva rama, nunca sobre la rama main
    - para esto se puede user el comando
        git branch -M <nombre de la nueva rama>

B). Se debe trabajar solo en la tarea que le toque y evitar subir muchos cambios en su request

## pasos para subir los cambios echos sobre la nueva rama creada
    1.  git status  <-- motrara la lista de los cambios realizados
    2.  git add * <-- trakea los cambios realizados en la nueva rama
    3.  git status <-- para revisar si los cambios fueron trakeados correctamente
    4.  git commit  -m '< mensaje sobre los cambio hechos >' <-- el mensaje debe ser brebe y explisito
    5.a  git push -u origin < nombre de la rama > <-- Esto por si es la primera vez que subes cambios /n 
    al repositorio principal desde esta rama
    5.b git push 

en vista de cualquier duda con los comandos de git preguntar al admistrador del repositorio 
Administrador del repositorio
nombre: Johan Ferreira
telefono: +584121076254


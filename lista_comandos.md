# Lista de los comandos utilizados

* Sire para duplicar/clonar repositorios en remoto
    >git clone X
* en caso de que clonemos un repositorio remoto y queramos borrar la direccion original que conecta el directorio local y remoto usamos el comando
    > git remote remove origin

* verifica los cambios hechos en el repositorio
    > git status
* para añadir cambios realizados en todos lados del fichero
    > git add .
* para añadir un comentario sobre la modificacion hecha anteriormente.
    > git commit -m "mensaje"(el mensaje sobre la modificación)

* para moverse a la rama que quieras 
    > git checkout X (nombre de la rama)
* para ver el listado de ramas que tenemos
    > git branch
  * para ver las ramas en remoto
     >git branch -a
  * para ver las ramas en local
    > git branch -r
* en caso de que hayamos creado 2 ramas o mas y queramos unirlas dejando un commit sobre los cambios tenemos que usar el comando
    > git merge (comando general) --no-ff X(nombre de la rama con la queremos unir) -m "mensaje"


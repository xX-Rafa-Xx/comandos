#comandos utiles de github

1. git init   ----> inicializa el repositorio
2. git add .  ----> prepara los últimos cambios para tomarle una fotografía
3. git reset . ---> restablece los preparativos para la fotografía revierte git add . 
4. git commit ----> fotografía tomada       
5. git checkout -- . ----> restaura lo eliminado hasta el útimo commit
6. git log    -----> muestra el listado de todos los commit
7. git commit --amend -----> servirá para editar el último commit hecho
#no es recomendable trabajar en la rama principal principalmente en el trabajo colaborativo
8. git checkout -b rama-heroes --> Crea una rama secundaria, usual para no trabajar en la rama principal
9. git checkout master --> oculta la rama secundaria
10. git merge rama-secundaria --> trae de vuelta la rama ocultada
11. git branch -d rama-secundaria --> borrará la rama creada (especificada despues de -d)
12. git push --> sirve para mandar los cambios
13. git commit -am --> sirve para hacer el add . y el commit en un solo comando
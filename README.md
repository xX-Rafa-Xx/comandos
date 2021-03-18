#comandos utiles de github

1. git init   ----> inicializa el repositorio (lo hará en la carpeta donde estes ubicado)
2. git add .  ----> prepara los últimos cambios para tomarle una fotografía
3. git reset . ---> restablece los preparativos para la fotografía - revierte git add . 
4. git commit -m "nombre del comit" ----> fotografía tomada/cambios guardados       
5. git checkout --. ----> restaura lo eliminado hasta el útimo commit (debe llevar --. despues del checkout)
6. git log    -----> muestra el listado de todos los commit
7. git commit --amend -----> servirá para editar el último commit hecho 
8. git checkout -b rama-secundaria --> Crea una rama secundaria, usual para no trabajar en la rama principal (#no es recomendable trabajar en la rama principal principalmente en el trabajo colaborativo)
9. git checkout master --> Te moverás a la rama master dejando la rama secundaria atras
10. git merge rama-secundaria --> fusionará la rama secundaria con la rama master
11. git branch -d rama-secundaria --> borrará la rama creada (especificada despues de -d debes especificar el nombre de la rama)
12. git commit -am "mensaje de tu comit" --> sirve para hacer el add . y el commit en un solo comando con el nombre de tu commit
13. :wq! --> Presiona ESC y escribe w para escribir, q para salir y ! signo de exclamación para que lo haga inmediatamente
14. git remote add origin htttps://github.com/repositorio.git --> agregará tu proyecto a liga del repositorio remoto que hayas especificado (lo mandarás a la web)
15. git branch -M main --> Renombrará la rama master a main
16. git push --> sirve para mandar los cambios (subir los cambios al repositorio en la red)
17. git pull --> sirve para descargar los cambios en el repositorio (cuando sea trabajo colaborativo y otro programador agregué código al proyecto)
18. git remote remove origin --> eliminará el repositorio remoto que hayas agregado
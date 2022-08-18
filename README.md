# comandos básicos git

1. git init
2. git add . # para añadir los cambios
3. git reset .  # para deshacer la última adición
4. git commit -m "nombre-commit" # para darle nombre al commit
5. git checkout -- .  # reconstruye el archivo como estaba en el último commit
6. git log  # para mostrar los registros de los commits
7. git commit --amend  # para editar el nombre del ultimo commit (para salir esc + wq! + enter)
8. git checkout -b nombre-rama  # para crear otra rama, distinta a la principal
9. git checkout master  # para cambiar a la rama master
10. git merge nombre-rama # para fusionar la rama principal con la secundaria
11. git branch -d nombre-rama  # para eliminar una rama del repo
12. git remote add origin # ruta para enviarlo al repositorio github
13. git push origin master  # comando para enviarlo a github y subir últimos cambios
14. git commit -am "nombre-commit"  # combinación del punto 2 y 4 
15. git switch "nombre-rama"  # para cambiar a otra rama"


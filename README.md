#Comandos utiles de Git.

1. ``git init`` : Inicializa mi repositorio.

2. ``git add .`` : Agrega todo los cambios al stage. O sea toma 'una foto' de los ultimos cambios y lo prepara para un commit por ejem.

3. ``git reset .`` : revertir el git add.

4. ``git commit -m "primer commit"`` : salvo o guardo todos los cambios.

5. ``git checkout -- .`` : revierto cualquier tipo de cambio hecho, hasta el ultimo commit. (Es como un Ctrl + Z).

6. ``git log`` : muestra todo el listado de los commit.

7. ``git commit --ammend`` : permite editar el nombre del ultimo commit. Se abre la terminal, hago el cambio, preciono ESC y escribo :wq! y Enter.

``RAMAS``

8. ``git checkout -b nombre de la rama`` : creo una nueva rama, ademas de la master en la que estoy trabajando principalmente.

9. ``git branch`` : muestra todas las ramas.

10. ``git checkout master`` : me muevo a la rama principal.

11. ``git merge 'nombre de la rama'`` : se unen los cambios a la rama principal.

12. ``git branch -d 'nombre de la rama'`` : eliminar alguna rama determinada.

13. ``git push`` : mandar/subir los cambios al repositorio de Github.

14. ``git commit -am 'nombre del commit'``: combina los comandos ```git add .```  y ```git commit -m ``` en un solo comando. 
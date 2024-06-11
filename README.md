forma 2: utilizando la cli(terminal).
git branch → verificar las ramas en local.

git checkout -b {nombre_nueva_rama} → crear y cambiar a esa rama

git add .
git commit
git push -u origin {nombre_nueva_rama} → subir las ramas nuevas al remoto.


git branch -d {nombre_rama} → borrar una rama del local.


------------------------------------------------------------


Pasos para hacer merge:
	- traer la rama a la que quiero hacer merge 
	- git fetch
	- git checkout {Rama_fusion}
	*nota la rama activa, debe a la que quiero hacer merge
	*recomendado, hacer pull de la rama antes del merge.
	- git merge {nombre_rama_a_fusionar}.
	*opcional git commit -m "merge"
	- git add .
	- git push -u origin {Rama_fusion}.

# Guía básica sobre el uso de branchs:

Verificar la Rama Actual:
> git branch


Crear una Nueva Rama:
> git branch Modulo-1

Cambiar a la Nueva Rama:
> git checkout nueva-funcion

## A partir de este punto, cualquier cambio que realices estará en la rama "Modulo-1" y no afectará a la rama "master/main".

Realizar Cambios en tu Código:
> Aquí es donde escribes el código de tu nueva función o realizas los cambios deseados.

Añadir y Confirmar los Cambios:
> git add .
> git commit -m "Añadida nueva función"

Fusionar la Rama con Master/Main:
> git checkout master

Y fusionas la rama "Modulo-1" con "master/main":
> git merge Modulo-1

En caso de no permitir fusionar:
> git merge Modulo-1 --allow-unrelated-histories

Eliminar la Rama:
> git branch -d Modulo-1

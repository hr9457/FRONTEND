# Instalacion de GitFlow

Comando para instalar git flow en el reposito y tener acceso a todas la rams dentro del proyecto.

```git
$ git flow init
```

# Visualcion de Ramas (branchs)

Comando para ver las ramificaciones y ver en la rama actual de trabajo.


```git
$ git branch
```


# Moverse entre ramificaciones

comando para movere entre la difertes ramas que exiten en el repositorio.

```git
$ git checkout "rama"
```

# Ramas Feature

comando para crear una feature o ramificacion a la rama develop.

```git
$ git flow feature start "nombre"
```

# Finalizar un Feature

Pasos para la finalizar un Feature y subir cambios a la ramificacion develop.

* agregar cambios.
* agregar descripcion.
* hacer publicacion del feature.
* guardar el feature local y remoto. 
* subir los cambios a la rama develop. 

```git
$ git add . 
$ git commit -m "descripcion"
$ git flow feature publish "nombre_del_feature"
$ git flow feature finish "nombre_del_feature" --kepplocal --keepremote
$ git push -u origin develop
```
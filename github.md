Apunte de github con comandos utiles

# Indice

[Borrar Archivo](#Borrar-Archivo)
[Borrar Carpeta](#Borrar-Carpeta)

## Borrar Archivo

Cuando se elimina un archivo de manera manual o por consola se tienen que realizar actualizaciones en el repositorio de github. Al chorrer git status deberia aparecer en rojo como deleteado

    git status 
    git rm archivo
    git commit -m "se borro el archivo"
    git status
    git push

## Borrar carpeta

Cuando se elimina una carpeta que tiene archivos hay que tambien agregar este cambio 

    git rm -r nombre_de_la_carpeta
    git commit -m "Se borro la carpeta por x razon"
    git push 

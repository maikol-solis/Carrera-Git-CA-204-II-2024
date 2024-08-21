# Carrera de Git

Vamos a hacer dos carreras en los archivos que se encuentran en el repositorio:

```
carrera-merge.txt
carrera-rebase.txt
```

El objetivo de cada carrera es muy sencillo, **poner su nombre de primero en el archivo.**

Para esto haremos dos modalidades

## Carrera con Merge

1. Todos deben primero crear una rama con el nombre "rama-su-nombre".
2. Escriba su nombre en el espacio indicado.
3. Haga el commit.
4. Luego haga switch hacia la rama `main`
5. Haga merge con `git merge rama-su-nombre`.
6. Finalmente `git push`
7. Revise que su nombre todavía es el primero con `git pull`. Si es así, **Excelente vas ganando!**.  
7. Si no es así, devuélvase a su rama con `git switch rama-su-nombre`
1. Y ejecute `git pull origin/main`
10. Vuelva a repetir los pasos hasta que su nombre sea el primero.

## Carrera con Rebase

1. En este caso no usaremos ninguna rama. Todos deben estar en la rama principal con `git switch main`.
2. Escriba su nombre en el espacio indicado.
3. Haga el commit.
4. Trate de hacer `git push`
5. Si no hay ningún error: **Excelente vas ganando!**.
6. Si dice que no puede hacer `git push`: **Trate de hacer `git pull --rebase`**.
7. Si su nombre no aparece, debes arreglarlo hasta que esté bien.
8. Vuelve a `git push`.
9. Sigue revisando con `git pull --rebase` para ver si alguien más te quitó el nombre.

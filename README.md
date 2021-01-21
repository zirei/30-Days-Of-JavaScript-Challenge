# LosPeques

We are legends!

## Clonar el repositorio

    git clone https://github.com/zirei/LosPeques.git

---

## git status

Para saber verificar si estas actualizado o desactualizado con la versión del servidor.

    git status

---

```javascript
console.log("te adoru pequeñita");
```

---

## git add

para añadir los archivos al commit

    git add <archivo>
    git add * <Para añadir todos los archivos>
    git add *.<extension> <para subir todo lo de la extension>

---

## git commit

Para guardar la versión actual que estas trabajando

    git commit -m "Descripción general de los cambios efectuados"

---

## git push

Para subir al branch actual el ultimo commit realizado en la maquina.

    git push

---

## git pull

Para descargar la ultima version del branch que queramos.

    git pull

---

## git branch

Para crear una nueva rama

    git branch <nombre_rama>

---

## git checkout

Nos permite movernos entre los branch

    git checkout <nombre_branch_desesas_ingresar>

---

## git merge(combinar dos branch)

Nos ubicamos en el branch que queremos actualizar e indicamos el branch con el que queremos actualizarlo

    git merge <branch_referencia>

---

## git push cuando creamos un nuevo branch desde consola

fatal: The current branch minina has no upstream branch.
To push the current branch and set the remote as upstream, use:

    git push --set-upstream origin minina

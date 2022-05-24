# submodules-revealjs
Vamos a configurar GitHub Pages y utilizar submodulos en un repositorio de GitHub. Haremos uso del framework HTML Revealjs.

Primero, he habilitado GitHub Pages en el Settings del repo, indicando la rama main como la principal para los cambios de la pagina.

![image](https://user-images.githubusercontent.com/91556405/170119627-b84c29d7-624a-4686-87ae-52489dff437e.png)

Luego, he clonado y iniciado el repo de reveal.js con:

```
git submodule add https://github.com/hakimel/reveal.js revealjs
git submodule update --init --recursive
```

![image](https://user-images.githubusercontent.com/91556405/170120117-beb8adfb-1ae9-42b1-885f-4b3d914565da.png)

Finalmente, Copiamos el index.html del repo clonado al nuestro y modificamos el contenido:

![image](https://user-images.githubusercontent.com/91556405/170120824-60778f49-a14e-4fca-9bf3-bd49f6bbf2f2.png)


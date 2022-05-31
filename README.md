# tutorial GitHub pages para portfolios

![https://s3-us-west-2.amazonaws.com/devcodepro/media/tutorials/publicar-tu-web-usando-github-pages-t1.png](https://s3-us-west-2.amazonaws.com/devcodepro/media/tutorials/publicar-tu-web-usando-github-pages-t1.png)

**En el presente tutorial te enseñaremos a publicar una página estática en la web utilizando GitHub Pages.**

**GitHub** es la plataforma de desarrollo colaborativo de software en donde usando el sistema de control de versiones de Git podemos gestionar mejor nuestro código además de alojarlo y compartirlo con la comunidad.

Lo que tal vez pocos sepan es que GitHub cuenta con una característica que nos permite crear o publicar una pagina web para nuestro proyecto, llamada **GitHub Pages**.

En este tutorial vamos a explicar cómo podemos usar esta característica y sacarle el máximo provecho. Antes de empezar debes tener en consideración lo siguiente:

- Debes tener una cuenta de GitHub creada. Si no la tienes, puedes crearla aquí: [https://github.com/join](https://github.com/join).
- Debes de tener GIT instalado en tu equipo [https://git-scm.com/downloads](https://git-scm.com/downloads)
- En este caso debes tener una plantilla de Bootstrap para poder realizar este tutorial  [templates de bootstrap](https://startbootstrap.com/themes/portfolio-resume)
- este template ira dentro de la carpeta portfolio el cual crearemos mas adelante
- Para este  tutorial usaremos el siguiente template

[startbootstrap-freelancer-gh-pages.zip](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/startbootstrap-freelancer-gh-pages.zip)

1. Primero vamos a nuestro [github.com](http://github.com/) y creamos un nuevo repositorio para nuestro código, le pondremos un nombre a nuestro repo, se recomienda que el nombre del repositorio sea [nombreusuario].github.io . En este caso el repositorio se llama “`cristianl0pez.github.io`”.

![portfolio.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio.png)

1. Una vez creado el repositorio, crearemos una carpeta llamada portfolio para nuestra pagina

![portfolio 1.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio_1.png)

1. Mediante el terminal nos ubicamos dentro de la carpeta “portfolio”, la cual contendrá  los archivos del template  que subiremos.

<aside>
⚠️ Recuerda descomprimir el rar del template en la carpeta

</aside>

![portfolio 2.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio_2.png)

1. ahora clonaremos el repo de GitHub a nuestra carpeta portfolio

```
echo "# cristianl0pez.github.io" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/cristianL0pez/cristianl0pez.github.io.git
git push -u origin main

```

1. Ahora los archivos del proyecto aparecerán en nuestro repositorio en GitHub.

![portfolio 3.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio_3.png)

1. ya que tenemos todo listo iremos a settings

![portfolio 3.1.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio_3.1.png)

1. luego a pages

![portfolio 3.2.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio_3.2.png)

1. aca deberíamos ver  algo como esto 

![portfolio final.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio_final.png)

1. luego iremos a la url que nos dan 

![portfolio final 1.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/portfolio_final_1.png)

1. y nuestra pagina debiera verse así  recuerden que puede demorarse unos 10 minutos  o menos

![Captura.PNG](tutorial%20GitHub%20pages%20para%20portfolios%202b0c39475e7b444a8257c43b7b3f1d69/Captura.png)

<aside>
⚠️ Tambien puedes clonar este repositorio para usarlo para hacer este portfolio

</aside>

Y así tenemos nuestra página publicada en GitHub.

Espero les haya sido de utilidad este tutorial.

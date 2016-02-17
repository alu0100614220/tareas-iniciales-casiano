<<<<<<< HEAD
Tutorial NodeJS, Express,  Atom, Github, Cloud 9 y Markdown.
===================
----------

NodeJS
-------------
> **Descripción:**  
>Es un intérprete Javascript del lado del servidor que cambia la noción de cómo debería trabajar un servidor.
>Su meta es permitir a un programador construir aplicaciones altamente escalables y escribir código que maneje decenas de miles de conexiones simultáneas en una sólo una máquina física.

>**Instalación:**  
> Para instalar NodeJS nos descargamos el instalador correspondiente para nuestro sistema operativo, en mi caso, el instalador de mac os x.
> Para comprobar que se ha instalado correctamente, ejecutamos el comando node en la terminal.
> Para instalar express ejecutamos el siguiente comando:

Atom
-------------
>**Descripción:**  
>Es un editor de código abierto desarrollado para windows, linux y mac. Soporta plungis escritos en nodeJS y control de versiones(git). Es desarrollado por github.

Github Destkop
-------------
> Es aplicación diseñada para simplificar los pasos esenciales a la hora de trabajar con el workflow de Github.

Cloud 9
-------------
>**Descripción:**  
>Es un IDE de desarrollo online, para su uso será necesario crear una cuenta en la página oficial o acceder con las credenciales de GitHub si ya se dispone de una cuenta. Una vez registrados podremos crear proyectos de varias tecnologías como puede ser NodeJS, HTML5, C++, Ruby On Rails, etc.

Markdown
-------------
>**Descripción:**  
Se trata de un lenguaje de marcado que facilita la aplicacion de un formato a un texto empleando una serie de caracteres de una forma específica.
Se penso para desarrollar textos cuyo destino fuese el formato web, pero con más rapidez y sencilles que editando directamente HTML.  

>**Conversion:**  
Existen diferentes tipos y conversores online y locales para pasar nuestro texto en Markdown a HTML.    

>>**Online:**
 [Stackedit](https://stackedit.io/) es una pagina web que sirve como editor de markdown y previsualizador, además nos tiene algunas herramientas de editores como cursiva, listas, tamaño de fuente etc. Otra ventaja que tiene es que podemos exportar nuestros archivos escritos online a diversos formatos, entre ellos html.  
>>**Local:**   
El editor de atom a parte de contar con un previsualizador para archivos markdown(ctrl + shift + m ). En cuanto a la conversión de markdown a html, probamos con pandoc.
=======
Tutorial NodeJS, Express, Atom, GitHub, Cloud9 y Markdown
======================================================

## Instalación de NodeJS en Windows

Es un intérprete **Javascript** del lado del servidor que cambia la noción de cómo debería trabajar un servidor. Su meta es permitir a un programador construir aplicaciones altamente escalables y escribir código que maneje decenas de miles de conexiones simultáneas en una sólo una máquina física.

Para empezar a utilizarlo descargar el paquete de instalación para la plataforma windows y seguir los pasos del asistente de instalación de **NodeJS**.

![](images/node.png)

Abrimos la consola de **NodeJS** y comprobamos que se ha instalado correctamente, aparecerá el siguiente mensaje que indica que se ha instalado.

Instalamos el framework **Express** con la consola de **NodeJS** y el siguiente comando:

**Comando**

> `npm install express --save`

![](images/node2.png)

## Instalación del editor de texto Atom

Usaremos **Atom** como editor de texto para el desarrollo de nuestros proyectos, para ello descargamos el instalador en la página oficial de atom, y a continuación ejecutamos el asistente de instalación.

![](images/atom1.png)

Dado que vamos a utilizar el formato **Markdown** es bueno saber que en **Atom** podremos obtener una preview del contenido de nuestro fichero Markdown ya que incorpora el formato **GitHub Markdown** con el comando:

**Comando**

> * Markdown preview `ctrl+shift+m`
> * Markdown export to HTML `Save As HTML`



## Instalación de GitHub Desktop

GitHub es una plataforma para alojar proyectos utilizando el sistema de control de versiones **Git**. Para instalarlo accedemos a la página oficial de **GitHub** y descargamos el instalador que ejecutaremos posteriormente para iniciar el asistente de instalación.

![](images/git.png)

Una vez instalado configuramos nuestra cuenta de **GitHub** en la aplicación para poder sincronizar nuestro repositorio tanto local como remoto, en caso de no tener cuenta crearemos una en la página de **GitHub**.

## Cloud 9

Es un IDE de desarrollo online, para su uso será necesario crear una cuenta en la página oficial o acceder con las credenciales de GitHub si ya se dispone de una cuenta. Una vez registrados podremos crear proyectos de varias tecnologías como puede ser NodeJS, HTML5, C++, Ruby On Rails, etc.

![](images/cloud.png)

Si disponemos de algún proyecto en un repositorio de GitHub podremos asociarlo a **Cloud9** para trabajar en él tan solo creando un “`nuevo workspace`” y añadiendo la url *git* del correspondiente repositorio.

![](images/cloud2.png)

Además **Cloud9** permite el trabajo en equipo en el IDE añadiendo miembros a tu workspace.

## Markdown

Markdown es un lenguaje de marcado ligero, lo vamos a utilizar en el editor de texto Atom ya que incorpora por defecto este formato y podremos obtener un live preview mientras vamos desarrollando además de poder exportarlo a HTML sin la necesidad de usar un conversor adicional.

Sintaxis:


Encabezados
```
# Encabezado H1
## Encabezado H2
### Encabezado H3
```
Tipografía
```
**Negrita**
*Cursiva*
> Citas
Parrafo separar por lineas en blanco
`Codigo`
```
Recursos
```
![Texto imagen](url-imagen)
* [Links](https://example.com)
```
Listas
```
1. Lista 1
2. Lista 2

* Lista 1
* Lista 2
```

**Recursos:**

* [NodeJS](https://nodejs.org)
* [Express](http://expressjs.com)
* [Atom IDE](https://atom.io)
* [GitHub Desktop](https://desktop.github.com)
* [GitHub Pages](https://pages.github.com/)
* [Cloud 9 IDE](https://c9.io)
* [Markdown](http://daringfireball.net/projects/markdown/)
* [Resultado del Markdown HTML](http://alu0100536652.github.io/Tutorial-STW/)
>>>>>>> ULL-ESIT-GRADOII-PL/master

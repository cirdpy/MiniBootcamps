---
title: Herramientas
has_children: false
parent: Herramientas de programación
nav_order: 1
---

# Editores

Una de las herramientas más importantes para el desarrollo de software es el editor. Los editores son procesadores de texto donde escribís el código.

Hagamos algunos experimentos para entender que es un editor y cómo se usa para escribir un programa.

### Tarea: Escribiendo un programa

Empecemos por crear un archivo nuevo en el escritorio, haciendo clic derecho sobre el escritorio, y luego sobre "nuevo" y seleccionando "Documento de texto".

Esto crea un documento nuevo en el escritorio, que se llama `Nuevo documento de texto.txt`, en este punto podemos renombrar el archivo a `prueba.txt`.

Al hacer doble clic sobre el documento nuevo, se abre el block de notas o el notepad, donde vamos a poder editar el documento. Estos programas son editores de texto, y sirven para escribir lo que se llama texto plano, es decir sin formato.

Ahora, copiemos en el documento de texto lo siguiente:

``` javascript
<!DOCTYPE html>
<html>
<head>
   <title>Hola mundo</title>
</head>
<body>
   <h1>Hola Mundo</h1>
</body>
</html>
```
Guardamos los cambios haciendo `ctrl+s`, o haciendo clic en el menú "archivo -> guardar".

Ahora podemos abrir este documento en cualquier navegador para ver que pasa. Hacemos esto haciendo clic derecho sobre el documento, y luego clic en el menú "abrir con" y seleccionando el navegador, o simplemente abriendo el navegador web y arrastrando el documento hasta cualquier parte del mismo.

Lo que pasa, es que se abre el documento y podemos ver exactamente lo que escribimos. Como el navegador no es un editor de texto, solo podemos leer el documento. 

Hasta ahora todo funciona correctamente, salvo que el navegador piensa que esta mostrando un documento de texto, cuando lo que escribimos en realidad es un programa.

Le hacemos saber esto al navegador mediante la **extensión** del archivo, que es lo que viene despues del punto en el nombre. En este caso, la extensión es `.txt`, que significa que se trata de un texto normal.

Cambiemos el nombre del archivo, para que el navegador sepa que se trata de un programa. En este caso, el código que copiamos está escrito en un lenguaje llamado **HTML**. Renombrá el archivo a `prueba.html`.

Ahora podemos abrir el archivo simplemente haciendo doble clic sobre él, y se abrirá en el navegador, que esta vez sabe que *le estamos hablando en su idioma, HTML*, y podrá interpretar correctamente el programa.

## Editores de texto especializados

Como pudimos ver, es posible escribir un programa utilizando cualquier editor de texto. Sin embargo, a medida que el programa se vuelve más largo y grande, se hará más difícil encontrar errores o hacer cambios en secciones específicas del mismo.

Para resolver este problema, los desarrolladores utilizan editores de texto especializados, que nos dan algunas ventajas como:

- *Depuración* - Descubrimiento de errores al recorrer el código, línea por línea. Algunos editores tienen capacidades de depuración o se pueden personalizar y agregar para lenguajes de programación específicos.
- *Resaltado de sintaxis* - Agrega colores y formato de texto al código, lo hace más fácil de leer. La mayoría de los editores permiten el resaltado de sintaxis personalizado.
- *Extensiones e integraciones del navegador*  -  Adiciones especializadas para desarrolladores, por desarrolladores, para acceder a herramientas adicionales que no están integradas en el editor base. Por ejemplo, muchos desarrolladores también necesitan una forma de documentar su código y explicar cómo funciona, e instalarán una extensión de revisión ortográfica para verificar si hay errores. La mayoría de estas adiciones están diseñadas para usarse dentro de un editor específico, y la mayoría de los editores vienen con una forma de buscar extensiones disponibles.
- *Personalización*  - La mayoría de los editores son extremadamente personalizables, y cada desarrollador tendrá su propio entorno de desarrollo único que se adapta a sus necesidades. Muchos también permiten a los desarrolladores crear su propia extensión.

### Tarea: Instalando Visual Studio Code

Visual Studio Code, es uno de los editores más populares y el que vamos a utilizar en este curso.

Para instalarlo, entra a la página web de descarga con el siguiente [link](https://code.visualstudio.com/download){:target="_blank"}, descargalo e instalá el programa.

Una vez instalado, abrí el programa que escriste haciendo clic derecho sobre el documento, y luego clic en el menú "abrir con" y seleccionando *Visual Studio Code* de la lista.

Al abrirse, vemos que el archivo se abre y podemos notar rápidamente las diferencias con el resaltado de sintaxis. Más adelante vamos a explorar otras ventajas y que nos ofrecen estos editores.

## Editores populares y extensiones de desarrollo web

- [Visual Studio Code](https://code.visualstudio.com/){:target="_blank"}
  - [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker){:target="_blank"}
  - [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack){:target="_blank"}
  - [Prettier - Formateador de código](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode){:target="_blank"}
- [Editor de codigo Átom](https://atom.io/){:target="_blank"}
  - [Code Spell Checker para Atom](https://atom.io/packages/spell-check){:target="_blank"}
  - [Teletype](https://atom.io/packages/teletype){:target="_blank"}
  - [atom-beautify](https://atom.io/packages/atom-beautify){:target="_blank"}

# Navegadores

Otra herramienta esencial es el navegador. Los desarrolladores Web confían en el navegador para observar cómo se ejecuta su código. También se usa para ver elementos visuales de una página web que están escritos en el editor, como HTML.

Muchos navegadores vienen con *herramientas para desarrolladores* (DevTools) que contienen un conjunto de características e información útil para ayudar a los desarrolladores a recopilar y capturar información importante sobre su aplicación. Por ejemplo: si una página web tiene errores, a veces es útil saber cuándo ocurrieron. Se puede configurar DevTools en un navegador para capturar esta información.

## Navegadores y herramientas de desarrollo populares

- [Edge](https://docs.microsoft.com/microsoft-edge/devtools-guide-chromium?WT.mc_id=academic-13441-cxa){:target="_blank"}
- [Chrome](https://developers.google.com/web/tools/chrome-devtools/){:target="_blank"}
- [Firefox](https://developer.mozilla.org/docs/Tools){:target="_blank"}

# Herramientas de línea de comandos (CLI)

Algunos desarrolladores prefieren una vista menos gráfica para sus tareas diarias y confían en la línea de comandos **(CLI)** para lograrlo. El desarrollo de código requiere una gran cantidad de escritura, y algunos desarrolladores prefieren no interrumpir su flujo de trabajo con el teclado es por eso que usan atajos(shortcuts) para cambiar entre ventanas de escritorio, trabajar en diferentes archivos y usar herramientas. La mayoría de las tareas se pueden completar con un mouse, pero una de las ventajas de utilizar la línea de comandos es que se pueden hacer muchas cosas sin la necesidad de cambiar entre el mouse y el teclado. Otro beneficio de esta es que son configurables, puedes guardar tu configuración personalizada, asi como tambien cambiarla más tarde o importarla a nueva máquina. Debido a que los entornos son tan exclusivos para cada desarrollador, algunos evitarán usar la línea de comandos, algunos dependerán de ella por completo asi como tambien otros pueden preferir una combinación de ambos.

# Opciones de línea de comandos (CLI) populares

Las opciones para la línea de comando varian según el sistema operativo que utilices.

💻 = *viene preinstalado en el sistema operativo.*

## Windows

- [Powershell](https://docs.microsoft.com/powershell/scripting/overview?view=powershell-7?WT.mc_id=academic-13441-cxa){:target="_blank"} 💻
- [Command Line](https://docs.microsoft.com/windows-server/administration/windows-commands/windows-commands?WT.mc_id=academic-13441-cxa){:target="_blank"} (también conocido como CMD) 💻
- [Windows Terminal](https://docs.microsoft.com/windows/terminal/?WT.mc_id=academic-13441-cxa){:target="_blank"}
- [Mintty](https://mintty.github.io/){:target="_blank"}
  
## MacOS

- [Terminal](https://support.apple.com/guide/terminal/open-or-quit-terminal-apd5265185d-f365-44cb-8b09-71a064a42125/mac){:target="_blank"} 💻
- [iTerm](https://iterm2.com/){:target="_blank"}
- [Powershell](https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-macos?view=powershell-7?WT.mc_id=academic-13441-cxa){:target="_blank"}

## Linux

- [Bash](https://www.gnu.org/software/bash/manual/html_node/index.html){:target="_blank"} 💻
- [KDE Konsole](https://docs.kde.org/trunk5/en/konsole/konsole/index.html){:target="_blank"}
- [Powershell](https://docs.microsoft.com/powershell/scripting/install/installing-powershell-core-on-linux?view=powershell-7?WT.mc_id=academic-13441-cxa){:target="_blank"}

## Línea de comandos (CLI) Populares

- [Git](https://git-scm.com/){:target="_blank"} (💻 en la mayoría de los sistemas operativos)
- [NPM](https://www.npmjs.com/){:target="_blank"}
- [Yarn](https://classic.yarnpkg.com/en/docs/cli/){:target="_blank"}

# Documentación

Cuando un desarrollador quiere aprender algo nuevo, lo más probable es que recurras a la documentación para aprender a usarla. Los desarrolladores a menudo confían en esta para guiarlos a través de cómo usar ciertas herramientas asi como tambien para entender como funcionan los lenguajes.

## Documentación popular sobre desarrollo de web

- [Mozilla Developer Network (MDN)](https://developer.mozilla.org/docs/Web){:target="_blank"}, de Mozilla, editores de [Firefox](https://www.mozilla.org/firefox/){:target="_blank"}
- [Frontend Masters](https://frontendmasters.com/learn/){:target="_blank"}
- [Web.dev](https://web.dev), de Google, editores de [Chrome](https://www.google.com/chrome/){:target="_blank"}
- [Documentos para desarrolladores propios de Microsoft](https://docs.microsoft.com/microsoft-edge/#microsoft-edge-for-developers){:target="_blank"}, para [Microsoft Edge](https://www.microsoft.com/edge){:target="_blank"}

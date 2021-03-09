---
category: Introduccion
url_path: '/Introduccion'
title: '1. Introducción a Unix'
type: 'INTRO'
layout: null
---

Esta guía contiene comandos básicos de Unix esenciales para bioinformática (pero útiles en cualquier momento). La guía asume que el usuario tiene acceso a la línea de comandos por medio de una [consola o interfaz de línea de comandos](https://es.wikipedia.org/wiki/Interfaz_de_l%C3%ADnea_de_comandos). Las consolas más comunes incluídas por defecto en los sistemas operativo usan [bash](https://es.wikipedia.org/wiki/Bash) para interpretar los comandos y dar instrucciones al sistema operativo. La consola en Mac es el mismo **[Terminal](https://en.wikipedia.org/wiki/Terminal_(macOS))** (igual que en sistemas Linux). En Windows 10 es posible activar un subsistema Linux e instalar [Ubuntu](https://ubuntu.com/#download) para usarlo como consola (siguiendo las intrucciones **[acá](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)**).

La idea de esta guía es aprender a usar la consola para manipular archivos de manera fácil y eficiente usando los comandos de Unix y Linux sin importar el sistema operativo base. Esta guía es básica y solo pretende dar una introducción rápida a los comandos más comunes. Al final, dejaremos una lista con más recursos útiles en español e inglés.

Notas:
- El código y resultado del código está en las cajas grises. Cualquier texto después del símbolo numeral (#) es un comentario y la consola lo ignora. 

- Copiar y pegar los comandos de la caja de código puede resultar en errores si hay caracteres escondidos. Lo mejor es escribir el comando en la consola usando las cajas de código como guía.

- El texto en verde después de las cajas de código representan el output del comando.

Ejemplo:

```
$ ls -lh # lista archivos dentro de la carpeta
```

<span style="color:#5fa300">carpeta1/</span>  
<span style="color:#5fa300">doc1.txt</span>  
<span style="color:#5fa300">doc2.txt</span>  

Los contenidos de esta guía son:

1. Listas, directorios y ayuda
2. Direcciones relativas y absolutas
3. Crear, editar y leer archivos
4. Patrones, expresiones regulares y metacaracteres
5. Ciclos (loops)
6. awk (opcional)
7. Referencias y otros recursos


----


La consola (bien sea la Terminal o Ubuntu), una vez iniciada, muestra la información del usuario y la ubicación del usuario en el sistema (en que folder está). Esa información se ve así (por ejemplo):

```
usuario123@mac-73458-12 /usuario123/Documentos
$
```

En este caso, **usuario123** es el nombre de usuario (puede o no ser el mismo que el nombre de usuario en la sesión), **mac-73458-12** es el hospedero (o equipo) del usuario, y **/c/Usuario/usuario123/Documentos** es la ubicación del usuario (puede variar). El símbolo de dolar ($) en demarca el espacio donde podemos escribir.

Por ejemplo, para imprimir la ubicación del usuario en la consola podemos usar el comando **pwd** (**p**rint **w**orking **d**irectory):

```
usuario123@mac-73458-12 /usuario123/Documentos
$ pwd # enter después
# de ahora en adelante, solo mostraremos el código y el resultado, sin la linea de usuario
```

<span style="color:#5fa300">/usuario123/Documentos/</span>


Ahora que sabemos en donde estamos, podemos empezar.
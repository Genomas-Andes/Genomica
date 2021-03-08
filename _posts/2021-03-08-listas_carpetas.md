---
url_path: '/Introduccion'
title: '1.1 Listas, directorio y ayuda'
type: 'LISTAS'
layout: null
---


Un directorio es equivalente a una carpeta tal y como se ve en el explorador de Windows o Mac. La única diferencia es que no hay una interfaz visual que muestre los íconos para cada tipo de archivo o su información asociada. Para esto, es posible usar el comando **ls** (**l**i**s**t). El comando imprime en pantalla los contenidos de un folder. Por ejemplo:

```
ls # simplemente muestra la lista de los contenidos dentro de la carpeta
<span style="color:#5fa300">carpeta_1/</span>.
<span style="color:#5fa300">imagenes/</span>.
<span style="color:#5fa300">archivo_temporal.txt</span>.
<span style="color:#5fa300">documento_enword.doc</span>.

```

Una lista de archivos puede se insuficiente. Para ver más información, por ejemplo el tamaño y fecha de última modificación, podemos hacer:


```
ls -lh # imprime una lista de una sola columna y el tamaño del archivo en formato leíble
<span style="color:#5fa300">carpeta_1/</span>.
<span style="color:#5fa300">imagenes/</span>.
<span style="color:#5fa300">archivo_temporal.txt</span>.
<span style="color:#5fa300">documento_enword.doc</span>.

```

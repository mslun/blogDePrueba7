---
layout: post
title:  "Mi primer articulo"
date:   2014-11-17 11:09:00
categories: jekyll update
--- 
Este es mi primer articulo en el blog que estoy creando utilizando jekyll. 


[<img src="https://raw.githubusercontent.com/franchescomora/blogDePrueba7/gh-pages/_images/car.jpeg" width="50%" align="right">](http://es.wikipedia.org/wiki/F%C3%B3rmula_1)

En la imagen se observa un auto de carreras, el cual se utilizo para probar uno de las maneras de hacer inserción de imágenes en un post de un blog hecho con Jekkyl.

En este caso, primero se subio la imagen a una carpeta [Images](https://github.com/franchescomora/blogDePrueba7/tree/gh-pages/_images) dentro del repositorio en GitHub que contiene el sitio y luego se llamo la url. Para ilustrar esto, a continuación se muestra la línea de texto correspondiente:

{% highlight ruby %}
<img src="https://raw.githubusercontent.com/franchescomora/blogDePrueba7/gh-pages/_images/car.jpeg" width="50%" align="right">
{% endhighlight %}

Si queremos que la imagen se comporte como un enlace a otro sitio,en este caso a [un artículo en wikipedia sobre la fórmula 1](http://es.wikipedia.org/wiki/F%C3%B3rmula_1) la línea sería:

{% highlight ruby %}
[<img src="https://raw.githubusercontent.com/franchescomora/blogDePrueba7/gh-pages/_images/car.jpeg" width="50%" align="right">](http://es.wikipedia.org/wiki/F%C3%B3rmula_1)
{% endhighlight %}

Ahora bien, para hacer la inserción de un video en vimeo, se hace con una linea que tenga la siguiente forma:

{% highlight ruby %}
<iframe src="//player.vimeo.com/video/70663871" width="600" height="337" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
{% endhighlight %}

y el resultado es el siguiente:

<iframe src="//player.vimeo.com/video/70663871" width="600" height="337" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

Y para insertar un video en youtube:

{% highlight ruby %}
<iframe width="640" height="394" src="http://www.youtube.com/embed/kQPWy8N0mBg?hd=1&amp;rel=0" frameborder="0" allowfullscreen></iframe>
{% endhighlight %}

y el resultado es el siguiente:

<iframe width="640" height="394" src="http://www.youtube.com/embed/kQPWy8N0mBg?hd=1&amp;rel=0" frameborder="0" allowfullscreen></iframe>

Observese que tanto para el video de Vimeo como el de Youtube, se permite la pantalla completa.

Para descargar un pdf, lo primero que se hizo fue crear localmente una carpeta llamada _pdf en el directorio del sitio, luego [se subio a github](https://github.com/franchescomora/blogDePrueba7/tree/gh-pages/_pdf) y se creo el enlace para la descarga a través de la siguiente línea:

{% highlight ruby %}
[Descargar pdf](https://raw.githubusercontent.com/franchescomora/blogDePrueba7/gh-pages/_pdf/Todos%20los%20pasos%20para%20hacer%20un%20blog%20con%20jekyll.pdf)
{% endhighlight %}

Por tanto, la descarga se puede efectuar desde el siguiente enlace:

[Descargar pdf](https://raw.githubusercontent.com/franchescomora/blogDePrueba7/gh-pages/_pdf/Todos%20los%20pasos%20para%20hacer%20un%20blog%20con%20jekyll.pdf)


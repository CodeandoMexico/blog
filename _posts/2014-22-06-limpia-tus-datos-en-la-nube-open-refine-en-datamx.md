---
layout: post

title: "Limpia tus datos en la nube: Open Refine en datamx"
cover_image: /posts/banner_openrefine.png

excerpt: "Refina tus datos en la nube con datamx"

author:
  name: Ricardo Alanís
  twitter: rdalanist
  gplus: 103851993836605615467
  bio: Datos Abiertos e Innovación Abierta
  image: authors/ric_moustache.jpg
---

Cuando se trabaja con datos generados en el mundo real, la información puede venir con muchos errores: espacios de más, caracteres fuera de lugar y errores de dedo al por mayor. Para poder hacer análisis de calidad, se necesita que los datos estén libres de estos errores. Este salto implica que muchos se enfrentan a la labor horrible de arreglarlos a mano, tarea que toma horas y horas. Por suerte, existe [Open Refine](http://openrefine.org/), nombrada como “La Herramienta” para la [limpieza de datos](http://theodi.org/case-studies/mexico-case-study-using-data-squads-to-jump-start-government-open-data-publishing). Si, me acabo de citar a mi mismo.

Open Refine fue originalmente desarrollado por la gente que trabajaba en el proyecto Freebase, una gran base de datos que busca vincular a personas, lugares y cosas del internet. Para hacer esta vinculación, es importantísimo tener datos limpios. Open Refine busca hacer esto de manera rápida y práctica. Por esta utilidad, en datamx hemos preparado nuestro sistema para que lo puedas usar de manera fácil y sin tener que instalar nada en tu computadora para trabajar con tus datos en la plataforma.

Para empezar a usar esta aplicación, sólo encuentra el botón de Open Refine en el recurso que quieras trabajar. 

<div class="full zoomable"><img src="/images/posts/datamx1.png"></div> 
{% highlight yaml %}
Me encanta el conjunto de datos de Comercio Informal en Zapopan, como un amante de los tacos de calle ¡siempre es bueno donde saber donde hay opciones!
{% endhighlight %}


Dale click a la sección de “Create Project”, y estarás listo para importar tu tabla. En esta ventana querrás verificar el tipo de archivo que quieres cargar, la codificación del texto y si quieres ignorar algunas líneas en la parte superior del archivo para los títulos de las columnas.

<div class="full zoomable"><img src="/images/posts/refine_1.png"></div> 
{% highlight yaml %}
En el conjunto de datos de comercio informal, seleccionas el encoding “ISO-8859-1” (latin-1, el default para excel en español) que el archivo con el que estás trabajando está separado por comas e ignorar la primera fila. ¡Qué bonito se ve el conjunto de datos!
{% endhighlight %}

Ya que terminaste de seleccionar las características de tus datos, ahora selecciona “Create Project”. En este momento, ya puedes empezar a jugar a modificar a los datos con las operaciones que tiene esta herramienta podrás tener acceso a todas las operaciones al conjunto de datos. Mi favorita es la faceta, que puedes usar al darle click a la flecha  que está justo a lado del nombre de cada columna. Selecciona la opción “Facet”. Verás que a la izquierda se llena una lista de las opciones. Dale click a cualquiera de ellas y verás que te mostrará la(s) línea(s) que cumple(n) ese valor en esa columna. Lo mejor es que puedes modificar uno de los valores, para agruparse con otro. 


<div class="full zoomable"><img src="/images/posts/refine_2.png"></div> 
{% highlight yaml %}
En el conjunto de datos de comercio informal, seleccionas el encoding “ISO-8859-1” (latin-1, el default para excel en español) que el archivo con el que estás trabajando está separado por comas e ignorar la primera fila. ¡Qué bonito se ve el conjunto de datos!
{% endhighlight %}

Cuando tu tabla ya está lista para ver el mundo, guarda el archivo a tu computadora usando el botón exportar y elige el formato que más te sirva. No dudes en subirlo otra vez a datamx. ¡Mucha gente te lo agradecerá!

Hay muchísimas más cosas que puedes hacer con Open Refine: puedes transformar tus datos, filtrarlos, y hasta mandar llamar páginas de internet a partir de tu información. La gente de escuela de datos preparó un excelente  [complemento a este post aquí](http://es.schoolofdata.org/2014/06/30/openrefine/). Si te quedan ganas de aprender aún más, te recomiendo el libro [“Using Open Refine”](http://www.amazon.com/Using-OpenRefine-Ruben-Verborgh/dp/1783289082/ref=sr_1_1?ie=UTF8&qid=1424227482&sr=8-1&keywords=using+openrefine) de Wilde y Verborgh. ¡Nos vemos en datamx!
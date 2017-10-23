---
layout: page-fullwidth
title: "Dudas sobre los contradores en Deepin"
teaser: "Ayudando a probar los dispositivos de la PC"
categories:
    - anexos
tags:
    - dudas
    - driver
    - controladores
header:
   image_fullwidth: "hot.jpg"
---
<div class="row">
<div class="medium-4 medium-push-8 columns" markdown="1">
<div class="panel radius" markdown="1">
**Índice**
{: #toc }
*  TOC
{:toc}
</div>
</div><!-- /.medium-4.columns -->

<div class="medium-8 medium-pull-4 columns" markdown="1">
{% include _improve_content.html %}

En la *Comunidad Deepin* aclaramos que el sistema operativo  perfecto no existe. Buscamos que cualquiera conozca Deepin, como si fuera un vehículo o una ciudad.

En esta página respondemos las dudas relacionadas a los controladores en Deepin. Es un complemento a la página [Dudas frecuentes]({{ site.url }}{{ site.baseurl }}/anexos/dudas/) y [Dudas técnicas]({{ site.url }}{{ site.baseurl }}/anexos/dudas-tecnicas/).

{% include alert success='Esta guía forma parte de una <a href="/dudas">serie de dudas frecuentes</a> para facilitar la comprensión a todos los usuarios y usuarias' %}

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

## Preámbulo
Queremos explicarte cómo funciona Deepin con las tres primeras preguntas.
### ¿Qué es un controlador? ¿Para qué sirve?

Un controlador (también "driver" o "rutina") es un software encargado de enviar y recibir información del dispositivo y es el intermediario del sistema operativo.

<div class="flex-video">
        <iframe width="1280" height="720" src="//www.youtube.com/embed/d5BQwOowSiA" frameborder="0" allowfullscreen></iframe>
</div>

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

### ¿Qué dispositivos puede cubrir el controlador?
Varios:

* Tarjetas gráficas
* Placa madre o Motherboard
* Lectora de disco
* Impresoras
* Micrófonos
* Altavoces o parlantes
* Y muchos más...

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

### ¿Qué puede proveer el controlador?
El núcleo Linux o la aplicación correspondiente. Ten en cuenta que los parches comunitarios vienen incluidos. Sin embargo, algunas distribuciones agregan binarios (blobs) que añaden parches de rendimiento por la empresa pero carecen de una auditoría comunitaria.

Visita [esta página para conocer algunos aspectos del software libre]({{ site.url }}/anexos/dudas-softlibre/).

## Problemas con los controladores
### ¿Es posible usar el controlador propietario de la tarjeta gráfica?
Sí. Algunos paquetes para optimizar la tarjeta gráfica de NVidia, por ejemplo, está disponible por separado. Visita [está página para conocer los controladores exclusivos disponibles]({{ site.url }}/manual/videocard/).

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

### ¿Cómo arreglar la tarjeta inalámbrica o Wifi?
Por defecto, la conexión inalámbrica está actividada en Laptops y dispositivos tipo "rompe muros". Si tienes problemas, [este tip te sirve para encontrar una solución a la conectividad WiFi]({{ site.url }}/tips/wififix/).

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

### ¿Existen parches para los microprocesadores?
Microcode es un controlador que aplica parches de rendimiento a los microprocesadores. En general, existen parches para AMD e Intel.

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

### ¿Existe un controlador para los equipos de sonido?
En Deepin 15.4 se usa [ALSA](https://www.alsa-project.org/main/index.php/Main_Page) (acrónomo de "Advanced Linux Sound Architecture").

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

## Recursos adicionales
* [Lista de portales de consulta](https://www.linux-drivers.org/) por linux-drivers.
* [Linux Hardware](https://linux-hardware.org/)
* [h.node](https://h-node.org/home/index/es)

<small markdown="1">[Ir al índice](#toc)</small>
{: .text-right }

## Seguimos creciendo

No olvides que estamos en [en Github](https://github.com/comunidad-deepin/comunidad-deepin.github.io).

{% include _improve_content.html %}

</div><!-- /.medium-8.columns -->
</div><!-- /.row -->
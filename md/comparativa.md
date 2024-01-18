# Comparativa con Apache

Apache se define a sí mismo como un servidor HTTP open source, mientras que Nginx se define como un servidor HTTP de alto rendimiento open source.

* Apache necesita abrir múltiples hilos para atender múltiples peticiones de clientes, mientras que Nginx con un hilo puede atender múltiples peticiones de clientes. Como resultado, consume menos recursos y es capaz de responder más rápidamente.
* Mientras que en alta carga Apache no es capaz de atender múltiples peticiones de forma concurrente y asíncrona, Nginx es todo lo contrario. Está diseñado para atender muchas peticiones de forma asíncrona y siendo lo más eficiente posible al consumir recursos de RAM y CPU.
* Mientras que Apache permite ejecutar PHP dentro del propio servidor web, en Nginx debemos externalizarlo, lo que es mucho más eficiente. Actualmente, usar mod_php en lugar de PHP-FPM es una locura.

![comparativa](/img/comparativa.jpg)

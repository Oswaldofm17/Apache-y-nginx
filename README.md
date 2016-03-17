## Servidor Apache:

El servidor HTTP Apache es un servidor web HTTP de código abierto, para plataformas Unix (BSD, GNU/Linux, etc.), Microsoft Windows, Macintosh y otras, que implementa el protocolo HTTP/1.12 y la noción de sitio virtual. Cuando comenzó su desarrollo en 1995 se basó inicialmente en código del popular NCSA HTTPd 1.3, pero más tarde fue reescrito por completo. Su nombre se debe a que alguien quería que tuviese la connotación de algo que es firme y enérgico pero no agresivo, y la tribu Apache fue la última en rendirse al que pronto se convertiría en gobierno de EEUU, y en esos momentos la preocupación de su grupo era que llegasen las empresas y "civilizasen" el paisaje que habían creado los primeros ingenieros de internet. Además Apache consistía solamente en un conjunto de parches a aplicar al servidor de NCSA. En inglés, a patchy server (un servidor "parcheado") suena igual que Apache Server.
El servidor Apache es desarrollado y mantenido por una comunidad de usuarios bajo la supervisión de la Apache Software Foundation dentro del proyecto HTTP Server (httpd).
Apache es usado principalmente para enviar páginas web estáticas y dinámicas en la World Wide Web. Muchas aplicaciones web están diseñadas asumiendo como ambiente de implantación a Apache, o que utilizarán características propias de este servidor web.
Apache es el componente de servidor web en la popular plataforma de aplicaciones LAMP, junto a MySQL y los lenguajes de programación PHP/Perl/Python (y ahora también Ruby).
Este servidor web es redistribuido como parte de varios paquetes propietarios de software, incluyendo la base de datos Oracle y el IBM WebSphere application server. Mac OS X integra apache como parte de su propio servidor web y como soporte de su servidor de aplicaciones WebObjects. Es soportado de alguna manera por Borland en las herramientas de desarrollo Kylix y Delphi. Apache es incluido con Novell NetWare 6.5, donde es el servidor web por defecto, y en muchas distribuciones Linux.

## Servidor nginx: 
nginx (pronunciado en inglés “engine X”) es un servidor web/proxy inverso ligero de alto rendimiento y un proxy para protocolos de correo electrónico (IMAP/POP3).2
Es software libre y de código abierto, licenciado bajo la Licencia BSD simplificada; también existe una versión comercial distribuida bajo el nombre de nginx plus3 . Es multiplataforma, por lo que corre en sistemas tipo Unix (GNU/Linux, BSD, Solaris, Mac OS X, etc.) y Windows.4
Originalmente, nginx fue desarrollado para satisfacer las necesidades de varios sitios web de Rambler que recibían unas 500 millones de peticiones al día en septiembre de 2008.7
De acuerdo con el estudio de Netcraft, Netcraft's Jul 2014 Web Server Survey, nginx es el segundo servidor web más usado en dominios activos (14,35%) superando a Microsoft Information Server. Además, pasó la marca de ser usado en más de 100 millones de sitios.8
##### Características básicas del servidor web
* Servidor de archivos estáticos, índices y autoindexado. 
* Proxy inverso con opciones de caché. 
* Balanceo de carga. 
* Tolerancia a fallos. 
* Soporte de HTTP y HTTP2 sobre SSL. 
* Soporte para FastCGI con opciones de caché. 
* Servidores virtuales basados en nombre y/o en dirección IP. 
* Streaming de archivos FLV y MP4.9 
* Soporte para autenticación. 
* Compatible con IPv6 
* Soporte para protocolo SPDY 
* Compresión gzip. 
* Habilitado para soportar más de 10.000 conexiones simultáneas.

##### DIFERENCIAS:
Nginx se basa en una arquitectura orientada a eventos. Apache se basa en una arquitectura basada en procesos.
Nginx no crea un nuevo proceso para una nueva solicitud. Apache crea un nuevo proceso para cada solicitud.
En Nginx, el consumo de memoria es muy bajo para servir páginas estáticas. Pero, la naturaleza de Apache de crear nuevos procesos para cada petición aumenta el consumo de memoria.
Varios resultados de evaluación comparativa indica que, en comparación con Apache, Nginx es extremadamente rápido para servir páginas estáticas.
En general, Nginx tiene menos componentes para agregar más características. Pero Apache tiene un montón de características y proporciona mucha más funcionalidad que Nginx.
Nginx no son compatibles con sistemas operativos como OpenVMS y IBMi. Pero Apache soporta mucho más amplia gama de sistemas operativos.
Nginx sólo viene con las características básicas que se requieren para un servidor web, es ligero en comparación a Apache.
El rendimiento y la escalabilidad de Nginx no es completamente dependiente de los recursos de hardware, mientras que el rendimiento y la escalabilidad de Apache depende de los recursos de hardware subyacentes como la memoria y la CPU.

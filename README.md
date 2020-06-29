# GOOGLE-CLOUD-MV

## Introducción

Las máquinas virtuales en la actualidad se han convertido en herramientas prácticas de trabajo ya que existe una variedad de sistemas operativos en los cuales se puede laborar para probar dichos sistemas sin necesidad de tener más de un computador, se emplea el uso de las máquinas virtuales las cuales se crean en las diferente nubes como el caso de GOOGLE CLOUD  en el que almacena diferentes máquinas virtuales y guarda la información que estas poseean con el objetivo de acceder desde cualquier lugar del mundo simplemente con el acceso a Internet.

## Objetivos

Generar máquinas virtuales con la utilización de la plataforma de GOOGLE CLOUD,para utilizar un sistema operativo diferente al que se tiene con la finalidad de probar ambos sistemas al mismo tiempo.

## Marco Teórico

**MÁQUINA VIRTUAL**
 Es un software que permite emular el funcionamiento de un ordenador dentro de otro mendiante el encapsulamiento que aísla a ambos.Puede ejecutar cualquier sistema operativo o   programa, sin que nada de lo que suceda en el interior de esa ventana afecte al ordenador que la ejecuta.
Se puede trabajar con varios sistemas operativos al mismo tiempo en un mismo ordenador por ejemplo se podria usar Linux y windows.

   ![Img3MaquinaVirtual.png](https://github.com/CFernanda/Maquinas-Virtuales-Amazon-Ec2/blob/master/imagenenes/Img3MaquinaVirtual.png)  
  
**GOOGLE CLOUD**
Es una suite que contiene diversos servicios que funcionan en la misma infraestructura que utiliza Google de manera interna.
El conjunto de herramientas que proporciona la suite abarca Cloud Computing, Networking, Data Storage, Data Analytics, Machine learning, etc. 
Provee los productos, servicios y herramientas para poder diseñar, realizar testing y lanzar las aplicaciones en la plataforma garantizando una gran escalabilidad y seguridad gracias al diseño de la infraestructura proporcionada por Google.
Ofrece más de 90 servicios de tecnología de la información, que las empresas, los profesionales de TI y los desarrolladores pueden aprovechar para trabajar de forma más eficiente, ganar más flexibilidad y/o permitirles una ventaja estratégica.(DoctorMetrics, 2018)

Esta infraestructura se divide en regiones y zonas. Al trabajar en distintas regiones se debe tener en cuenta el coste adicional para el tráfico de red entre éstas. Este enlace contiene información más detallada sobre este tema.
Dentro la variedad de productos y servicios dentro de la plataforma, vamos a mencionar las siguientes categorías:
- Computing   
- Networking   
- Storage   
- Big data   
- Machine learning

![google-cloud-platform.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/google-cloud-platform.png)  

##  Ventajas
Elegir Google Cloud
Motivos para elegirnos
Confianza y seguridad
Mantén tus datos protegidos y asegúrate de que cumplen las normativas pertinentes
Nube abierta
Escala con una tecnología abierta y flexible
Infraestructura mundial
Desarrolla sobre la misma infraestructura que usa Google
Informes de analistas
Cómo destaca Google Cloud
Testimonios de clientes
Descubre cómo usan Google Cloud las empresas
Partners
Aprovecha al máximo nuestro ecosistema mundial de expertos en la nube
Blog de Google Cloud
Lee las últimas noticias y novedades sobre nuestros productos
Eventos
Participa en eventos y descubre más información sobre Google Cloud--

**Precios de Google Cloud**
Google no tiene costes por adelantado, 
Servicios de pago por uso, ni comisiones por cancelación. 
Google ofrece descuentos en los precios y ofrece innovaciones como el tamaño adecuado.
Los clientes también pueden utilizar una calculadora de precios a través de su sitio web. 
Esta herramienta ayuda a los clientes a anticiparse a los costes. 
Los precios varían según el servicio individual, por lo que también querrá ver en toda la plataforma cada una de las ofertas y evaluar los precios en consecuencia.

## MANUAL DE USUARIO

Para crear una máquina virtual en la plataforma GOOGLE CLOUD, lo primero que se hace es crear una cuenta que le permita hacer uso de los beneficios que la plataforma ofrece.
**Creación de la cuenta**

- 1. Ingresar a la pagina de GOOGLE CLOUD mediante el siguiente link. https://cloud.google.com/ aparece la pantalla que se muestra a continuación 

![img1GC.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/img1GC.png) 

- 2. Para iniciar debemos dar click sobre **Empezar Gratis**, de abrirá una nueva ventana con un formulario del primer de dos paso que se debe seguir.
![img2GC.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/img2GC.png)

Se ingresa datos de la cuenta como nombre, correo el país y se aceptan las condiciones.

-3. Al dar click en **continuar** se abrirá otra ventana con el paso 2 se inresa los datos del Cliente y adicional pide un número de tarjeta de crédito que sirve solo para verificar la cuenta y permitirá trabajar con la cuenta de forma gratuita durante 12 meses.

![paso2.JPG](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/paso2.JPG) 

![paso2s.JPG](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/paso2s.JPG) 

Al dar click en **Iniciar versión de prueba gratuita**  se abrirá una nueva ventana de inicio a la plataforma de GOOGLE CLOUD, y ha sido creada una nueva cuenta.

![Img3VentanaInicio.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/Img3VentanaInicio.png) 

**Creación de Máquina Virtual**

- 1. En la página de Inicio de dirige al **Menú de Navegación**, que se encuentra en la parte superior izquierda de la ventana.
- 2. se busca la pestaña **Compute** y en ella **Compute Engine**  se despliegan opciones y se debe elegir la primera **Instancias de VM**

![Img4Compute.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/Img4Compute.png) 

- 3. Se abrirá una nueva ventana en la que se debe escoger **Crear**.

![Img5Crear.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/Img5Crear.png) 

- 4. Una nueva pantalla llamada **Crear una nueva Instancia**  en la que se especificarán los datos de la máquina que se creará.
 - El nombre de la maquina debe tener minusculas
 - Se escoge todos los detalles dependiendo de las necesidades para crear la máquina, si se requiere se puede cambiar el sistema operativo , la versión y su tamaño,

 ![Img6DetallesMaquina1.JPG](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/Img6DetallesMaquina1.JPG) 
 
 
  ![tiposdesistemasoperativos.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/Img7tiposdesistemasoperativos.png)
  

 Se debe dar Click en Crear y se procesará la  nueva máquina virtual en este caso se escogió el sitema operativo UBUNTU.

 ![Img6DetallesMaquina2.JPG](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/Img6DetallesMaquina2.JPG) 
 
- 5. Se abre una nueva ventana en la que se mostrará el proceso que lleva a cabo la máquina virtual cuando pase a verde la máquina estará lista para utilizarla.
  
  ![Img9MaquinasCreadas.png](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/Img9MaquinasCreadas.png)
  
 - 6. Se debe dar Click sobre SSH y s escoge la primera opción, seguido se abrirá la terminal de la Máquina creada en el sistema operativo Ubuntu.
 
 ![MaquinaUbuntu.JPG)](https://github.com/CFernanda/GOOGLE-CLOUD-MV/blob/master/Imagenes/MaquinaUbuntu.JPG)
 
 
 
 ## Bibliografia

* DoctorMetrics. (13 de Junio de 2018). Obtenido de https://www.doctormetrics.com/google-cloud-platform/#:~:text=potencial%20y%20versatilidad.-,Introducci%C3%B3n,como%20Youtube%20o%20Google%20Search.&text=Esta%20infraestructura%20se%20divide%20en%20regiones%20y%20zonas.
* Ibermatica. (7 de mayo de 2019). Obtenido de https://www.ibermatica365.com/microsoft-azure-que-son-las-maquinas-virtuales/
* GOOGLECLOUD.https://cloud.google.com/

 
 




- 




















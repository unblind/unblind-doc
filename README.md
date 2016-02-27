# MyEyes

Cierra los ojos. Imagina tenerlos cerrados una hora, un día, un año... hay cerca de 40 millones de personas ciegas en el mundo, y alrededor de 300 millones con algún tipo de discapacidad visual. My Eyes les permite volver a abrir los ojos. 

El proyecto consiste en unas gafas impresas en 3D con una cámara HD integrada. La cámara está conectada a una Raspberry Pi, que el invidente lleva en la cintura. Se puede interactuar con las gafas mediante comandos de voz, para recibir distintos tipos de ayuda:

- Identificar y describir qué personas tienes delante (Ejemplo: "tienes delante a 2 personas de unos 25 años que tienen barba")
- Identificar productos y marcas (Ejemplo: "tienes en la mano un producto de la marca Coca Cola")
- Leer textos escritos.

Además, permite reportar incidencias en la vía, para generar una base de datos abierta que ayude tanto a las administraciones, como a otras personas con dificultades, a encontrar mejores rutas.

El proyecto se ha realizado teniendo en mente que las gafas deben ser baratas. El coste completo de las gafas, la cámara HD, una Raspberry Pi Zero y los conectores es inferior a los 50 euros. Tanto el software como los modelos 3D de todos los componentes están disponibles públicamente para que cualquiera pueda reproducirlas con facilidad.

## Equipo

* **Juan**: Ingeniero de teleco, maestro del soldador y especialista en electrónica.
* **Cristian**: Ingeniero en informática y experto en desarrollo web y dispositivos móviles.
* **Guido**: Licenciado en investigación de mercados e ingeniero de telecomunicación, experto en cloud computing y desarrollo backend ([@palmerabollo](http://twitter.com/palmerabollo)).

## Arquitectura

* **Gafas**: impresas en 3D durante el Hackaton, llevan integrada una pequeña cámara HD y un micrófono. Su peso total es de unos 50 gramos.

* **Controlador**: basado en una Raspberry Pi, es el cerebro encargado de interpretar las órdenes dadas por la persona que lleva las gafas, utilizar diferentes servicios online y responder con una respuesta adecuada al usuario.

## Tecnologías utilizadas

La solución está desarrollada utilizando software libre.

* Jasper

Y servicios online como wit.ai, Microsoft Oxford y Google Vision API.

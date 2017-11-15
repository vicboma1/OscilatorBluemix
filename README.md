# Oscilator Bluemix
Pequeño proyecto que forma parte del starter kit de la hackathon.

### Esquema Node-RED

![](https://github.com/vicboma1/oscilatorBluemix/blob/master/assets/_oscilatorBluemix.png)

La solución se basa en un esquema de nodos que representa el funcionamiento de un oscilador.

El dispositivo kinect procesa la información y la envía al IoT Watson de Bluemix.

Mediante Node-RED accedemos a esa información y la manipulamos.

El ejemplo consta de un juego de manos, derecha e izquierda.

La mano izquierda enciende (Open) el oscilador y lo apaga (Close).

La mano derecha define el sonido del oscilador. Sonido agudos hacia abajo y sonidos graves hacia arriba.

Adicionalmente, carga una libería de sonido dinámicamente a través de un componente "template".

Esta librería es Tone.js

### Kinect Studio Application Windows + Movimientos reales 
#### (Click en el gif para ver video)

[![](https://github.com/vicboma1/oscilatorBluemix/blob/master/assets/_oscilatorBluemix.gif)](http://www.youtube.com/watch?v=5SWKVNh-q2c "Oscilador")

### Pasos a seguir 
#### (El código no estará disponible hasta la finalización de la Hackathon)

1.   Copiar la ![Plantilla txt](https://github.com/vicboma1/oscilatorBluemix/blob/master/assets/_oscilatorBluemix.txt) con "Control A" + "Control C"

2.   Ir al menú contextual de nuestra aplicación Node-RED

3.   Importar

4.   Clipboard

5.   Import Nodes -> "Control V" para pegar la template

6.   Aceptar pulsando el botón de "Import"

7.   Configura el nodo IBM IoT Input con la Api Key de tu Universidad.

8.   Para renderizar los componentes del dashboard necesitas instalar la dependencia "node-red-dashboard"

9.   Ir al menú contextual de nuestra aplicación Node-Red -> "Manage Palette" -> Install

10.  Escribimos -> "node-red-dashboard" para Web | "node-red-dashboard-es" para mobile


@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal  [CoEValencia - Hackathon 2017](https://github.com/CoEValencia/Hackathon_2017)


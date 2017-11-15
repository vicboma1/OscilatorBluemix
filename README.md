# Oscilator Bluemix
Pequeño proyecto que forma parte del starter kit de la hackathon.

### Esquema Node-RED

![](https://github.com/vicboma1/StarterKitBluemixHands/blob/master/assets/_starterKitBluemixHands.png)

La solución se basa en un esquema de nodos que representa el funcionamiento de un oscilador.
El dispositivo kinect procesa la información y la envía al IoT Watson de Bluemix.
Mediante Node-RED accedemos a esa información y la manipulamos.
El ejemplo consta de un juego de manos, derecha e izquierda.
La mano izquierda enciende (Open) el oscilador y lo apaga (Close).
La mano derecha define el sonido del oscilador. Sonido agudos hacia abajo y sonidos graves hacia arriba.
Adicionalmente, carga una libería de sonido dinámicamente a través de un componente "template".
Esta librería es Tone.js

### Kinect Studio Application Windows + Movimientos reales (Click en la imagen para ver video)
[![](http://img.youtube.com/vi/5SWKVNh-q2c/0.jpg)](http://www.youtube.com/watch?v=5SWKVNh-q2c "Oscilador")

## Pasos a seguir
1.   Copiar la ![Plantilla txt](https://raw.githubusercontent.com/vicboma1/StarterKitBluemixHands/master/assets/_starterKitBluemixHands.txt) con "Control A" + "Control C"

2.   Ir al menú contextual de nuestra aplicación Node-RED

3.   Importar

4.   Clipboard

5.   Import Nodes -> "Control V" para pegar la template

6.   Aceptar pulsando el botón de "Import"

7.   Configura el nodo IBM IoT Input con la Api Key de tu Universidad.


@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal  [CoEValencia - Hackathon 2017](https://github.com/CoEValencia/Hackathon_2017)

# Casa de Pepe y Julián
 
[![Build Status](https://travis-ci.org/wollok/casaDePepeYJulian.svg?branch=master)](https://travis-ci.org/wollok/casaDePepeYJulian)

Pepe y Julián viven juntos, y les gusta comprar cosas. 
De cada cosa nos interesa el precio, si es comida o no, y si es un electrodoméstico o no.

## Sobre las cosas que se compran
En este modelo reducido, vamos a considerar las siguientes cosas que podrían ser interesantes para comprar: 
- una heladera que vale 20000 pesos
- una cama que sale 8000
- una tira de asado que sale 350 pesos
- un paquete de fideos que sale 50 pesos
- una plancha que vale 1200 pesos. 

Por las dudas aclaramos: la cama no es un electrodoméstico, la plancha sí.

Implementar, además de los objetos que representan cada cosa, un objeto que represente a la casa, que contenga una coleccion una coleccion de cosas y que entienda los siguientes mensajes:
- `comprar(cosa)`: registra que se ha comprado una cosa.
- `cantidadDeCosasCompradas()`: indica ... eso.
- `tieneComida()`: indica si compró algo que es comida al menos una vez.
- `vieneDeEquiparse()`: indica si la _última_ cosa que se compró es un electrodoméstico, o bien vale más de 5000 pesos.
- `electrodomésticosComprados()`: devuelve un objeto que contiene todas las cosas compradas que son electrodomésticos. 
- `malaEpoca()`: indica si todas las cosas compradas son comida.


## Más cosas
Agregar las siguientes cosas que pueden comprarse:
- un kilo de milanesas rebozadas: 260 pesos.
- una botella de salsa de tomates: 90 pesos.
- un microondas: 4200 pesos.
- un kilo de cebollas: 25 pesos.
- una compu: 500 dólares. Para saber el precio en pesos, multiplicar por la cotización del dólar. Agregar un objeto `dolar` al que se le pueda preguntar el `precioDeVenta()`, alcanza con que devuelva un valor fijo. 
- un "pack comida" que incluye un plato (que puede ser tira de asado, fideos o milanesas) y un aderezo (que puede ser la botella de salsa de tomates o el kilo de cebollas. Precio: la suma del precio de sus componentes.

**Pregunta**  
para lograr que la casa pueda comprar estas cosas nuevas, ¿qué hubo que cambiar en la definición del objeto que representa la casa? Si hay que tocar poco, o nada, ¿qué concepto nos ayuda?


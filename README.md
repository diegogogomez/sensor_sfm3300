Código funcional desarrollado para ser ejecutado usando arduino y realizando la conexión I2C al sensor de flujo SFM3300

Distribución de pines del sensor
NC*-VCC-SCL-GND-SDA-NC*

*NC = no conectar

Pines usados en el arduino
VCC-GND-A4-A5
	
Sensor SFM3300	-> 	pin arduino
VCC	->	VCC

SCL	->	A5

GND	->	GND

SDA	->	A4

Los pines de interface (SDA y SCL) deben llevar una resistencia pull-up a VCC para su correcta comunicación.

Esta es una primera versión funcional donde se evidencia variacion de las variables a y b del código cuando se realiza flujo de aire. 
Es necesario leer el datasheet y programar los bites funcionales para realizar la conversion de la información.

!!!NO SOLDAR LOS PINES DEL SENSOR, PUEDE GENERAR DAÑOS SOBRE EL MISMO!!!

autor Diego Gomez
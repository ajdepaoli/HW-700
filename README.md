# HW-700
# Modulo de potencia HW-700 para HOT-END o HOT-BED (modificado).
Esta modificación es necesaria, ya que de esta forma el MOSFET al activarse conduce con su menor resistencia posible entre D-S, lo cual disminuye drásticamente la potencia producto del factor P=V(D-S_on)xI.
En el SCH se aclara que componentes cambiar y cuales agregar.

Para usar con 24VCC debes agregar un diodo Zener, solo cumple la función de protección para el Gate, si quieres por seguridad se lo colocas en 12VCC pero es optativo.

NOTA para los menos expertos:

1- ENTRADA ALIMENTACION (JP1): Solo debes tener cuidado con +IN y -IN. ya que si lo inviertes NO vas a quemar nada del circuito, solo quedaría la salida permanentemente con tensión o sea que lo que conectes allí quedará con alimentación.

2- SALIDA ALIMENTACION (JP2): En +OUT y -OUT; NO IMPORTA la polaridad de lo conectado, NI el HOT-END ni la HOT-BEB tienen polaridad.

3- ENTRADA ACTIVACION (JP3): NO importa la polaridad de conexión, U2 se encarga de polarizar correctamente U1.

4- TODOS LOS CAMBIOS los debe realizar alguien con experiencia, ya que no serlo, de seguro destruirás las pistas.

2024-05-26

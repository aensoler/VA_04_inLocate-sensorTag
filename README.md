VA_04_inLocate-sensorTag
========================

inLocate : Ante la problemática de la localización en espacios interiores, en los cuales el sistema de geolocalización estándar GPS no es viable; surge esta nueva aproximación para resolverla.

El objetivo es conseguir que se pueda hallar la posición exacta mediante la tiangulación de un dispositivo móvil (Android) a través de unas balizas emisoras de radiofrecuencia a 2.4 GHz que emplean la novedosa tecnología Bluetooth 4.0 LE.


Subproyecto: Sensor Tag

Como empleamos dispositivos Sensor Tag CC2541 como emisores Bluetooth tuvimos que modificar ciertas características de dichos dispositivos a nivel de firmware.

Se ha modificado el aspecto firmware del dispositivo para que cumpla los requisitos que se propusieron inicialmente. El problema inicial era que los dispositivos sólo se mantenían activos durante un corto periodo de tiempo (3 minutos). Por esto, se modificó el firmware para que el dispositivo se mantuviera enviando durante un periodo de tiempo que permitiera la localización correcta. Por otro lado, se intentó mejorar la transmisión de potencia ajustando la ganancia de la etapa amplificadora, a la vez que se mantienen unos requisitos de eficiencia energética.

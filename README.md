# convolution-reverb

### Guia de uso del software

Dentro del script de python se pueden encontrar las clases responsables de la normalizacion de senales de audio en formato wave(.wav)
Para aplicar canvolucion a una senal de audio es necesario cambiar la senal de muestra que se encuentra como 'sample.wav'

La funcion convolution_reverb('/sample.wav', '/ir.wav', '/result.wav') es la encargada de todo el proceso
Debe insertarse como primer parametro la direccion de la senal a la cual se desea aplicar convolucion
Como segundo parametro se ingresa la direccion de la respuesta al impulso que se quiere aplicar
Como ultimo parametro se elige el nombre y la direccion de guardado de la nueva senal de audio que se va a generar resultado de la convolucion

Este programa se encuentra limitado a senales con poca informacion, por lo que no es factible usar audios de alta calidad

# convolution-reverb

### Guia de uso del software

<p>Dentro del script de python se pueden encontrar las clases responsables de la normalizacion de senales de audio en formato wave(.wav).</p>
<p>Para aplicar canvolucion a una señal de audio es necesario cambiar la senal de muestra que se encuentra como 'sample.wav'</p>
<p>La funcion convolution_reverb('/sample.wav', '/ir.wav', '/result.wav') es la encargada de todo el proceso</p>
<p>Debe insertarse como primer parametro la direccion de la senal a la cual se desea aplicar convolucion</p>
<p>Como segundo parametro se ingresa la direccion de la respuesta al impulso que se quiere aplicar</p>
<p>Como ultimo parametro se elige el nombre y la direccion de guardado de la nueva senal de audio que se va a generar resultado de la convolucion</p>
<p>Este programa se encuentra limitado a señales con poca informacion, por lo que no es factible usar audios de alta calidad</p>

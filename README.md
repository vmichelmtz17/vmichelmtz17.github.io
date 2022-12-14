# vmichelmtz17.github.io
<a href="https://cooltext.com"><img src="https://images.cooltext.com/5620351.png" width="373" height="86" alt="IR REMOTE" /></a>
![Image text](https://github.com/vmichelmtz17/vmichelmtz17.github.io/blob/main/emisor.gif)


Un mando universal, también conocido como control remoto universal, es un control remoto capaz de controlar distintos elementos (como equipos audiovisuales, aire acondicionado o sistemas de robótica) de uno o varios fabricantes distintos, mediante códigos IR (infrarrojos), porque tiene almacenados esos códigos de control en una base de datos interna o porque es capaz de aprender los códigos IR del mando original del elemento a controlar.

# COMO FUNCIONA
Un mando a distancia IR funciona conmutando el LED encendido y apagado en una secuencia particular. Sin embargo, para evitar interferencias a partir de fuentes de IR tales como la luz del sol o las luces, el LED no está encendido de forma permanente, pero se enciende y se apaga a una frecuencia de modulación (típicamente 36 a 40 KHz). En el momento en que se está enviando una señal modulada se llama marca (1) y, cuando el LED está apagado se llama espacio (0).

Naturalmente, en el mando a distancia, cada tecla tiene un código asociado a ella (por lo general de 12 a 32 bits), y transmite este código cuando se pulsa esa tecla. Si la tecla se mantiene pulsada, el mando a distancia normalmente transmite repetidamente el código clave. En los controles remotos de Philips RC5 o RC6, el código activa un bit cada vez que se pulsa una tecla, el receptor utiliza este bit de conmutación para determinar cuando se pulsa una tecla por segunda vez.
![Image text](https://github.com/vmichelmtz17/vmichelmtz17.github.io/blob/main/REMOTEIR.jpg)

# MECANISMO DE FUNCIONAMIENTO
El mecanismo de funcionamiento de una transmisión por infrarrojos es bastante “simple”; un haz de luz, de alta frecuencia de 38 kHz (típico de los mandos a distancia para la TV) se proyecta frente a un receptor. Este haz de luz no es más que una secuencia de bits (0 y 1) que son codificados por el receptor, a través de la polarización del foto-transistor. Veamos este caso simple; el control remoto, es el cifrado de los distintos impulsos con diversos bits y secuencias, por ejemplo, el botón de encendido/apagado es:
![Image text](https://github.com/vmichelmtz17/vmichelmtz17.github.io/blob/main/FIG1.gif)

En el extremo receptor, el detector IR demodula esta señal, y emite una señal de nivel lógico que indica si se está recibiendo una señal o no. El detector de infrarrojos, funciona mejor cuando su frecuencia coincide con la frecuencia del emiso.

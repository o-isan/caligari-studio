# Caligari Studio
Caligari Studio es una aplicación que te permite tocar los instrumentos: guitarra, piano, xilófono y flauta.

Su nombre  es en honor al grupo de rock español Gabinete Caligari.
La aplicación está hecha en python con la tecnología de GUI kivy y liberías comp pydub o playsound, entre otras.

## Vistas
**Vista de piano:**
En el piano se pueden escoger las octavas y el estilo (o sonido) de las teclas a travás del menú desplegable. También se puede escoger si se desea el tono más grave o más agudo.

![Piano 1](img/1.png)
2 octavas.

![Piano 2](img/2.png)
5 octavas.


**Vista de guitarra:**
Se pueden escoger dos tipos distintos de sonidos, y también elegir si tocar con plantilla.

![guitarra con plantilla](img/5.png)
![guitarra con cuadrícula](img/6.png)


**Vista de xilófono:**
![Xilófono](img/3.png)


**Vista de flauta:**
![flauta](img/4.png)


**Panel principal**
Desde el panel principal se puede escoger el instrumento a tocar
![Panel principal](img/7.png)


**Reproducción de melodías:**
También se pueden elaborar melodías mediante un lenguaje propio inventado a través de expresiones regulares. Permite reproducir melodías de forma automatizada.
Pues el usuario escoge el tiempo de cada nota y su tono.
![Panel principal](img/12.png)



## Vídeos de demostración:
**Instrumentos tocados de forma individual.**
[Ver video](vid/1.mp4)


**Melodía automatizada**
Esta melodía corresponde a la marcha granadera.
[Ver video](vid/2.mp4)


## Muestras de código:

**Xilófono**
![Xilófono](img/8.png)


**Guitarra**
![Guitarra](img/9.png)


**Menú principal**
![Menú principal](img/10.png)


**Melodías automáticas**
Como puede ver se usa el módulo re para construir las expresiones regulares e identíficar cada
nota separa por /
![Melodías automáticas](img/11.png)

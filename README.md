# DAWcontroller
 MIDI-USB DAW controller

He creado el blog http://uxiogonzalez.blogspot.es/ para describir cómo voy avanzando en mi nuevo proyecto: un controlador MIDI para estaciones de trabajo de audio digital (DAW). 

Descripción del proyecto:

La idea principal es crear un controlador físico multicanal (del estilo Pro Tools S3 Control Surface), es decir, un controlador con faders motorizados, botones para MUTE, SOLO, REC, PLAY, PAN, pantallas de display, etc. Todo ello controlado mediante Arduino y con conexión mediante USB o MIDI. 

Estimo un coste total alrededor de los 300 euros (notable diferencia con lo que cuesta un controlador de Protools) y lo mejor de todo es que se puede construir con el número de canales que queramos, ya que utilizaré los protocolos de comunicación SPI e I2C que proporciona Arduino para minimizar el número de pines utilizados en el proyecto.

El proyecto lo iré construyendo por módulos, lo cual facilitará la expansión del controlador con más módulos si se desea. 

El primer módulo está compuesto de todos los componentes necesarios para controlar hasta 8 canales del DAW. Como referencia puedo mencionar el conocido controlador de Behringer BCF2000. 

El segundo módulo estará compuesto por los controles principales del DAW: Play, Stop, Rec, etc, la pantalla principal, knobs de modificación de parámetros, y  un fader motorizado para control del volumen principal. Este módulo todavía no lo tengo definido completamente ya que por ahora me he centrado en el primer módulo del proyecto. Más adelante lo definiré con más precisión.

Con respecto a la alimentación del proyecto, para minimizar costes utilizaré una fuente de alimentación ATX, perfecta para mi proyecto, ya que tiene los voltajes de salida idóneos para los componentes necesarios que voy a utilizar. Intentaré subir todas las fotos posibles para una completa explicación.

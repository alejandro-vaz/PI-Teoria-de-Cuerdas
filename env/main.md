## Índice
---

1. [Índice](#índice)<index>1</index>
1. [Introducción](#introducción)<index>2</index>
    1. [Resumen](#resumen)
    1. [Objetivos](#objetivos)
1. [Situación inicial](#situación-inicial)<index>4</index>
    1. [Mecánica clásica](#mecánica-clásica)
    1. [Mecánica cuántica](#mecánica-cuántica)
    1. [Mecánica relativista](#mecánica-relativista)
    1. [Teoría cuántica de campos](#teoría-cuántica-de-campos)
1. [El Modelo Estándar](#el-modelo-estándar)<index>7</index>
    1. [Origen](#origen)
    1. [Qué es](#qué-es)
    1. [Hadrones](#hadrones)
    1. [Leptones](#leptones)
    1. [Bosones](#bosones)
    1. [Limitaciones](#limitaciones)
1. [Gravedad](#gravedad)<index>13</index>
    1. [Relatividad especial](#relatividad-especial)
    1. [Relatividad general](#relatividad-general)
1. [La teoría de cuerdas](#teoría-de-cuerdas)<index>17</index>
    1. [Superficies](#superficies)
    1. [Armónicos](#armónicos)
    1. [Gravitón](#gravitón)
1. [Problemas](#problemas)<index>20</index>
    1. [Dimensiones](#dimensiones)
    1. [Bosones](#bosones-1)
    1. [Taquiones](#taquiones)
1. [Conclusión](#conclusión)<index>21</index>
1. [Bibliografía](#bibliografía)<index>22</index>

## Introducción
---

> Este proyecto de investigación ha sido redactado con CSScribe[(1)](#bibliografía), el lenguaje de marcado perfecto para hacer trabajos escritos. Para estandarizar la simbología LaTeX del trabajo, se han utilizado los estándares matemáticos anglosajones, intercambiando las comas por los puntos. Puedes acceder a el código fuente del proyecto en su repositorio oficial[(2)](#bibliografía).

### Resumen

Nuestro universo contiene materia que, al agrandar la escala lo suficiente, está formada por partículas. Estas partículas están reunidas y organizadas en el Modelo Estándar de física de partículas.

Existen dos categorías de partículas:

   - Los fermiones, que conforman la materia.
   - Los bosones, que median las interacciones entre partículas.

A primera vista, se podría pensar que se trata de una teoría que describe todo. Pero, hay una interacción que el Modelo Estándar no incluye: la fuerza gravitatoria.

A gran escala, la gravitación puede describirse mediante la relatividad general. Los astros curvan el espacio-tiempo, lo que atrae a otros astros. Como ocurre con otros tipos de interacciones, cabría esperar que la curvatura del espacio-tiempo también estuviese cuantizada, dando lugar así a partículas llamadas gravitones.

El problema surge cuando se intenta incluir el gravitón en el modelo estándar, ya que los cálculos dan resultados absurdos, con valores infinitos que no se pueden remediar.

Para unificar todas las fuerzas, los físicos llevan más de medio siglo buscando nuevas teorías. Una de las más prometedoras es la teoría de cuerdas.

En el Modelo Estándar, las partículas se describen como pequeños puntos sin dimensión. En la teoría de cuerdas, por el contrario, cada partícula tiene se interpreta como una pequeña cuerda, que puede estar abierta o cerrada.
 
Además, estas cuerdas pueden vibrar, al igual que una cuerda real, pero solo en frecuencias armónicas. La frecuencia de vibración y el tipo de cuerda determinan la partícula resultante y todas sus propiedades.

Al hacer los cálculos de las partículas que representan todos los tipos de cuerdas posibles, una nos llama la atención, se trata del gravitón. Mientras que el Modelo Estándar no puede incluir matemáticamente al gravitón, la teoría de cuerdas lo hace de forma inherente al definirlo como una cuerda con determinadas propiedades.

Desgraciadamente, esta teoría que parece tan prometedora presenta tres problemas:

1. Nuestro espacio-tiempo tiene cuatro dimensiones (tres de espacio y una de tiempo), pero la teoría solo parece funcionar en un universo de 26 dimensiones.

1. Todas las cuerdas se comportan como bosones.

1. Se predice la existencia de una partícula llamada taquión, cuya masa es un número imaginario.

Aunque la teoría de cuerdas es especulativa y difícil de verificar experimentalmente, es uno de los modelos más prometedores, ya que proporciona una descripción cuántica de la gravedad.

### Objetivos

El objetivo principal de este trabajo es comprender las bases de la teoría de cuerdas y los fundamentos teóricos necesarios para llegar a entender qué es, qué hace, por qué existe y cuáles son sus inconvenientes.

Para ello, empezaremos realizando este trabajo escrito. Este documento nos servirá de guía para realizar una presentación con los contenidos explicados de manera sencilla e intuitiva.

Durante todo el proceso, nos apoyaremos únicamente de unas matemáticas sencillas, sin adentrarnos mucho en el cómputo o el significado de variables o fórmulas. Hemos tomado esa decisión porque no podríamos explicar la teoría de cuerdas desde un punto de vista matemático sin enseñar previamente las matemáticas de la relatividad general ni las de la mecánica cuántica.

A pesar de ello, hemos intentado incluir las matemáticas en la mayor medida que nos ha dejado un proyecto de investigación de estas características.


## Situación inicial
---

![Relative](/images/1.png) <br> Los cuatro dominios principales de la física moderna. <br> Figura $1$.

Para entrar en contexto, conviene repasar las fuerzas fundamentales, tenemos cuatro tipos de interacciones:

   - Electromagnética: actúa entre partículas con carga eléctrica. Es responsable de fenómenos como la electricidad y las interacciones químicas. Tiene un alcance infinito.
   - Gravitatoria: actúa entre partículas con masa y energía. Es la más débil y tiene un alcance infinito.
   - Nuclear fuerte: mantiene unida a los protones y los neutrones dentro de un átomo. Es muy fuerte pero tiene un alcance corto.
   - Nuclear débil: es responsable de algunos procesos como la desintegración $\beta$ pero tiene un alcance menor, menor incluso que el de la interacción nuclear fuerte.

Por otra parte, para explicar nuestro universo, desde la escala más grande a la más pequeña, tenemos cuatro teorías. La figura $1$ resume cuándo usamos cada una de las propuestas para representarlo.

### Mecánica clásica

> Se utiliza cuando $S \gg h$ y $v \ll c$.

La mecánica clásica es el modelo más antiguo que tenemos para describir la realidad física, data desde hace más de dos mil años y nos sirve para describir los sucesos que experimentamos en la vida cotidiana. Hasta el siglo XX, la mecánica clásica comprendía toda la física[(3)](#bibliografía).

Gracias a la mecánica clásica, podemos describir los movimientos (cinética), el comportamiento del calor (termodinámica) y muchos fenómenos eléctricos y magnéticos (electromagnetismo), entre otros fenómenos físicos.

Pero esta teoría presentaba varios grandes problemas sin resolver a finales del siglo XIX. Uno de ellos es que fallaba al predecir los sucesos del mundo microscópico, como la radiación del cuerpo negro o los espectros de emisión y absorción discontinuos de los átomos.

Tampoco describía bien el comportamiento de los objetos a altas velocidades. Según las leyes de Newton de la mecánica clásica, la velocidad de la luz podía ser alcanzada y las leyes físicas podían variar según la inercia del observador (debido a las transformaciones de Galileo).

### Mecánica cuántica

> Se utiliza cuando $S \approx h$ y $v \ll c$.

La cuántica surgió a principios del siglo XX para explicar la realidad a escalas muy pequeñas, donde la física clásica fallaba.

Inicialmente este modelo surgió para corregir el espectro de radiación del cuerpo negro. Las predicciones clásicas de finales del siglo XIX indicaban que la intensidad de la radiación del cuerpo negro siempre aumentaba con su frecuencia, llegando a dar valores muy por encima de los observados en las altas frecuencias. A este fallo de la física clásica se le denominó catástrofe ultravioleta.

Max Planck era un físico alemán que estaba trabajando en este problema cuando, como último recurso, se le ocurrió resolver el problema cuantizando la energía. En vez de ser la energía una magnitud contínua, que puede tomar cualquier valor; Planck hizo que solo pudiese tomar valores que fuesen múltiplos de una cantidad determinada, $h$, y a cada paquete de energía lo llamo cuanto[(4)](#bibliografía).

De esa forma obtuvo un resultado matemático idéntico al experimental y surgió la mecánica cuántica. Con las contribuciones posteriores de muchos otros físicos, consiguieron crear este modelo en el que los sucesos son probabilidades y no podemos conocer ni predecir las magnitudes físicas con total precisión.

### Mecánica relativista

> Se utiliza cuando $S \gg h$ y $v \approx c$.

![Relative](/images/2.png) <br> Campo gravitatorio. <br> Figura $2$.

Por otro lado, si observamos la estructura del universo a gran escala, podemos describir y predecir con extraordinaria precisión el comportamiendo de las grandes estructuras del universo con la teoría de la relatividad.

Cuando nos referimos a la teoría de la relatividad, nos referiremos a la teoría de la relatividad general, a pesar de que hay dos teorías de la relatividad:

   - Teoría de la relatividad especial: propuesta por Albert Einstein en 1905 y que describía el comportamiento de los objetos a alta velocidad. Mantiene como principios que las leyes de la física son iguales para todos los observadores y que la velocidad de la luz es constante.
   - Teoría de la relatividad general: también propuesta por Einstein, es una extensión de la relatividad especial que tenía en cuenta magnitudes como la aceleración y la gravedad. Es la teoría más completa que tenemos para entender el universo a gran escala.

En la relatividad general, el espacio y el tiempo actúan como si fuesen una única entidad, es decir, el espacio y el tiempo dependen uno de otro y son indivisibles. Propone que la energía curva el espacio-tiempo de forma parecida a que si hiciéramos fuerza en una colchoneta, como en la figura $2$.

La relatividad general se interpreta geométricamente como que el espacio-tiempo está curvado, arrastrando así a los objetos; objetos que siguen trayectorias geodésicas sobre el espacio-tiempo, y describe que la gravedad es la tendencia de esos objetos a "caer" en el espacio-tiempo.

### Teoría cuántica de campos

> Se utiliza cuando $S \approx h$ y $v \approx c$.

![Relative](/images/3.png) <br> Partículas como excitaciones de su campo cuántico. <br> Figura $3$.

La teoría cuántica de campos combina la relatividad especial con la física cuántica. Considera la presencia de partículas como excitaciones de unos campos cuánticos, que representan la probabilidad de encontrar a ese tipo de partícula en el espacio en un momento determinado.

Esta teoría es la base del Modelo Estándar de partículas, donde cada partícula tiene su campo cuántico asociado.

Aunque sí que se ha podido combinar la relatividad especial y la cuántica para formar esta teoría, cuando intentamos hacerlo con la relatividad general, todo falla y nos quedan resultados infinitos y absurdos.


## El Modelo Estándar
---

### Origen

A mediados del siglo XX, los físicos empezaron a enfretarse con dificultades debido a la gran cantidad de nuevas partículas que se estan descubriendo. A este suceso histórico se le dio el nombre de "zoología de partículas,"[(5)](#bibliografía) y se intensificó de forma alarmante en la década de los $60$.

Los físicos de aquel entonces estaban desconcertados. Las teorías de aquel entonces no explicaban la gran cantidad de partículas que estaban encontrando, ni tampoco que tuvisen unas propiedades aparentemente arbitrarias.

La razón detrás de la zoología de partículas era desconocida en aquel entonces, pero muchos físicos empezaron a intuirla: ¿y si las partículas que estamos detectando no son fundamentales?

> Cuando en física nos referimos a una partícula, queremos referirnos a una partícula fundamental, una partícula que no está conformada por ninguna más pequeña. Un grano de arena no lo podríamos considerar una partícula, ya que está compuesto por unidades más pequeñas, como pueden ser los átomos.

Los físicos de la época se preguntaban si las partículas que estaban siendo descubiertas eran realmente partículas fundamentales, o simplemente eran uniones, grupos, de partículas más pequeñas.

![Relative](/images/4.png) <br> Premio Nobel de física de $1979$. <br> Figura $4$.

¿Era el neutrón una partícula fundamental? ¿Y el electrón? ¿El barión lambda? ¿Lo será el mesón $\phi$? Los científicos tuvieron que esperar $20$ años más para obtener respuestas definitivas.

Durante esos $20$ años surgieron tres avanzes que hicieron posible que se formulase el Modelo Estándar:

1. En la década de $1960$, los físicos teóricos Sheldon Glashow, Abdus Salam y Steven Weinberg (premios Nobel, figura $4$)[(6)](#bibliografía) introdujeron la teoría electrodébil, que unificaba la fuerza electromagnética y la débil en una única teoría que explicaba ambas.
1. En 1964 se introdujo el concepto de cuark, proponiendo que algunas partículas como los neutrones y los protones estaban compuestas por ellas. Inicialmente los cuarks eran solo abstracciones matemáticas, pero más tarde se verificó su existencia experimentalmente.
1. En 1973 se formuló la cromodinámica cuántica (QCD, por sus siglas en inglés), que explicaba las interacciones entre cuarks mediada por la fuerza fuerte.

Al año siguiente, en 1974, el físico italiano Luciano Maiani reunió la QCD y la teoría electrodébil en lo que fue llamado "El Modelo Estándar de física de partículas." El Modelo Estándar unifica tres de las cuatro fuerzas fundamentales, pero la gravedad todavía queda excluida.

### Qué es

El Modelo Estándar es un marco teórico que describe con precisión las partículas fundamentales y sus interacciones. Hablaremos ahora de sus partículas y características. Puedes observar su representación gráfica en la figura $5$.

![Relative](/images/5.png) <br> Partículas del Modelo Estándar. <br> Figura $5$.

La primera impresión que da es que hay muchas partículas, pero en realidad son solo unas pocas con diferentes variantes.

Lo primero que llama la atención es que hay dos grandes columnas. En la primera columna se encuentran los fermiones; los fermiones conforman toda la materia, están organizados en tres generaciones y tienen espín semientero ($\pm 1/2$).

Las tres generaciones de fermiones son en realidad, idénticas. Lo único que varía entre las generaciones es la masa, o energía, de cada partícula: cuanto mayor es la generación, mayor es la energía.

La masa en física de partículas se mide en $eV/c^2$, electronvoltios partido de la velocidad de la luz al cuadrado. El electronvoltio en realidad es una unidad de energía, correspondiente a la energía adquirida por un electrón al ser acelerado desde el reposo mediante una diferencia de potencial de un voltio en el vacío[(7)](#bibliografía). Como ya sabemos que Einstein introdujo en su teoría de la relatividad especial que

$$
\begin{align*}
E &= m \cdot c^2 \\
m &= \frac{E}{c^2}
\end{align*}
$$

si dividimos la energía entre la velocidad de la luz al cuadrado nos quedan unidades de masa.

### Hadrones

Nos centraremos ahora en los cuarks de la primera generación, ya que conforman la mayoría de la materia visible. Los datos de la masa parecen arbitrarios para todas las partículas y es algo a lo que todavía no se le ha dado sentido en la física moderna, por lo que no nos detendremos en ello.

Mira los datos de la carga de los cuarks $u$ y $d$ situados en la primera generación. Considerando que para formar una partícula no fundamental la carga tiene que ser un número entero, ¿que pasaría si juntásemos un cuark $u$ y dos $d$? Tendríamos una partícula resultante no fundamental con carga nula y que tuviese una masa de $11.56\, MeV/c^2$. Se parece sospechosamente mucho al neutrón, pero tiene una masa $81$ veces menor.

En realidad, esta partícula sí que es el neutrón. Su masa restante es fruto de la interacción entre gluones, las partículas que median la fuerza fuerte y que unen los cuarks. Algo similar pasa con el protón, al juntar dos cuarks $u$ y uno $d$.

Además de los fermiones de materia, cada fermión tiene su contraparte antipartícula. Todos los y los leptones y cuarks tienen su partícula correspondiente de antimateria. Es decir, tendremos un anticuark $u$, otro $d$ y así. A las antipartículas las representamos poniendo una línea horizontal encima del símbolo de la partícula original: $\overline{u}$, $\overline{d}$... La única excepción a esta norma es el positrón (antielectrón): como el electrón es $e^-$, el positrón se denomina $e^+$.

Las antipartículas tienen las mismas propiedades que las partículas originales pero con el signo de la carga invertido. Es decir, un $\overline{d}$ tiene carga $+1/3$.

Cuando una partícula entra en contacto con su contraparte antipartícula (no cualquier antipartícula, solo la suya correspondiente), ambas se aniquilan y liberan toda su energía. Eso significa que sí que podemos juntar partículas y antipartículas siempre que no existan pares partícula-antipartícula.

![Relative](/images/6.png) <br> Clasificación de hadrones. <br> Figura $6$.

Podríamos, por ejemplo, juntar un cuark $u$ y otro $\overline{d}$ para formar una partícula no fundamental con carga $+1$ conocida como mesón $\pi ^+$. Pero no podríamos juntar unos cuarks $u$ y $\overline{u}$ ya que se aniquilarían entre sí.

> Se pueden hacer combinaciones también con los cuarks de segunda y tercera generación, pero las partículas resultantes suelen ser muy inestables y pesadas. Por ejemplo, un solo cuark $t$ pesa lo mismo que un átomo de astato ($At$), presente al final del periodo seis de la tabla periódica, lo que lo hace muy inestable.

Los cuarks también tienen colores, descritos por la cromodinámica cuántica, pero no profundizaremos en ello.

A las partículas resultantes de la combinación de cuarks se les denomina hadrones, que se clasifican en mesones si tienen dos cuarks y bariones si tienen tres (figura $6$).

### Leptones

Los leptones, por sí solos, son fermiones que no se combinan para dar otras partículas. Podemos diferenciar dos tipos de partículas, un tipo en cada fila: los derivados del electrón y los neutrinos.

Todos derivados del electrón tienen carga $-1$ y propiedades similares. El más reconocible de todos ellos es el electrón, presente en todos los átomos estables, aunque las otras dos generaciones, que son más difíciles de encontrar en la naturaleza, también tienen un papel en el universo.

Los muones son conocidos por tener una gran capacidad de penetración en la materia, por lo que se usan principalmente para obtener imágenes de formaciones rocosas. El tauón es una partícula rara que presenta propiedades únicas[(8)](#bibliografía), debido a que es increíblemente inestable, y al desintegrarse, por su alta masa, produce la mayoría de las veces mesones $\pi ^-$ y $\pi ^0$.

Los neutrinos, en cambio, tienen propiedades radicalmente diferentes. Los neutrinos son partículas que interactúan muy poco. Estas partículas son afectadas únicamente por la fuerza débil, que tiene un alcanze muy corto, por lo que raramente tienen la posibilidad de interactuar con otras.

Los neutrinos además sufren de un extraño fenómeno denominado como la "oscilación de neutrinos." En el caso de los neutrinos, un $v_e$ puede cambiar repentinamente a ser otro tipo de neutrino, como el $v_\tau$. Este fenómeno ocurre según el neutrino se desplaza por el espacio-tiempo.

Las oscilaciones de los neutrinos implican que estos tienen masa, una característica que el Modelo Estándar no predecía. Hoy en día sabemos experimentalmente que los neutrinos tienen masa, pero desconocemos cuánta tienen ni cómo la adquieren.

El neutrino es la única partícula fundamental que no consigue su masa mediante el mecanismo de Higgs, como veremos más tarde.

### Bosones

Los bosones son las partículas mediadoras de las interacciones y tienen espín entero. Cada una de las fuerzas fundamentales tiene su partícula (o partículas) mediadoras:

   - Fuerza electromagnética: el fotón, $\gamma$, que no tiene masa ni carga. La radiación electromagnética está compuesta por fotones.
   - Fuerza fuerte: el gluón, $g$. Los cuarks en los hadrones se unen mediante estas partículas, y de ellos proviene la mayoría de su masa (a pesar de que los gluones en sí no tienen masa ni carga).
   - Fuerza débil: los bosones $Z^0$, $W^-$ y $W^+$, que tienen masa y carga. La gran masa de estos bosones limita en gran medida su alcance, y por tanto, el alcance de la fuerza.

![Relative](/images/7.png) <br> Desintegración del bosón $Z^0$ en un par electrón-positrón. <br> Figura $7$.

También tenemos un bosón diferente, el bosón de Higgs ($H$), descubierto en $2012$. Este bosón no media ninguna fuerza, sino que se encarga de dar a las partículas masa mediante el mecanismo de Higgs[(9, 10)](#bibliografía).

El mecanismo de Higgs le da masa a todas las partículas. Se interpreta como que las partículas interactúan con el campo de Higgs obteniendo así su masa. Todas las partículas obtienen su masa así, excepto los neutrinos. Se desconoce a día de hoy cómo los neutrinos adquieren su masa.

### Limitaciones

Aparte de la incertidumbre del mecanismo que da la masa a los neutrinos, tenemos una cuestión más desconcertante en el Modelo Estándar:

La fuerza electromagnética es mediada por el $\gamma$, la fuerza fuerte lo es por el $g$ y la fuerza débil por los bosones $Z^0$ y $W^{\pm}$; ¿qué pasa con la gravedad? ¿La fuerza gravitatoria no tiene un bosón?

Conocemos la forma en la que la gravedad actúa a gran escala gracias a la relatividad general, pero a escala cuántica tiene que haber una partícula que medie la fuerza, ¿no? Todas las fuerzas fundamentales tienen su partícula mediadora, por lo que la gravedad no debería ser una excepción.

Un argumento que apoya la existencia de esta partícula misteriosa es la reciente detección de ondas gravitacionales. Desde su primera detección en $2015$, los observatorios LIGO y Virgo han identificado ondas gravitacionales provocadas por eventos cósmicos en múltiples ocasiones[(11, 12)](#bibliografía).

Otro argumento a favor es que las ecuaciones de campo de la relatividad general que indican cómo se comporta el espacio-tiempo pueden ser justificadas considerando que la gravedad es mediada por un bosón de espín $2$.

Detectar la partícula mediadora de la gravedad es muy difícil, ya que la gravedad es la más débil de todas las fuerzas. A esta partícula mediadora de la gravedad se la llamó gravitón y es necesaria que exista para entender la gravedad a una escala pequeña.

Aunque no sepamos de su existencia experimental, podemos deducir algunas propiedades del gravitón. Como se propaga a la velocidad de la luz, sabemos que su masa tiene que ser cero, o al menos muy cercana, mucho menor incluso que la de los neutrinos. También podemos predecir que tiene carga cero, ya que si no interactuaría con otras partículas cargadas, y ese comportamiento no lo hemos detectado.

¿El Modelo Estándar falla? ¿O acaso el gravitón no existe? Para entender por qué el gravitón y la relatividad general son incompatibles tendremos que entender previamente que dice la teoría de la relatividad.


## Gravedad
---

La fuerza gravitatoria es descrita en física mediante la relatividad general, teoría propuesta por Albert Einstein en 1915. Esta teoría solo funciona a gran escala, donde las magnitudes actúan como si no estuviesen cuantizadas y fuesen contínuas.
 
Empezaremos respondiendo una pregunta aparentemente sencilla: ¿Por qué la velocidad de la luz es constante? Es una pregunta bastante interesante que plantearse, ¿cómo lo sabemos? La realidad es que eso ya se sabía mucho antes de que Einstein propusiese ninguna de las teorías de la relatividad.

Las ecuaciones de Maxwell que describían el comportamiento de la fuerza electromagnética a escalas no-cuánticas sugerían implícitamente que la velocidad de la luz debería ser constante.

Esto se debe a que al despejar $c$ (la velocidad de la luz) en una combinación de la ley de Faraday y la de Ampère-Maxwell[(13)](#bibliografía), nos queda únicamente que

$$
\begin{align*}
c &= \frac{1}{\sqrt{\varepsilon _0 \cdot \mu _0}}
\end{align*}
$$

siendo $\varepsilon _0$ la permitividad eléctrica del vacío y $\mu _0$ la permeabilidad magnética en el vacío. Con esos valores medidos experimentalmente:

$$
\begin{align*}
\mu _0 &= 4\pi \cdot 10^{-7} \, H/m \\
\varepsilon _0 &\approx 8.8541878176 \, F/m \\
\end{align*}
$$

podemos calcular la velocidad de la luz de forma precisa: $299\,792\,458\,m/s$.

> En realidad, la longitud del metro se define como la distancia que recorre la luz en $1/299\,792\,458$ segundos, por lo que la velocidad de la luz es exactamente $299\,792\,458\,m/s$.

### Relatividad especial

Einstein, al formular su teoría de la relatividad especial (también conocida como relatividad restringida), introdujo únicamente dos postulados:

1. $c$ es una constante universal.
1. Las leyes de la física son iguales para todos los observadores.

El primer postulado lo introdujo porque las leyes de Maxwell predecían que la velocidad de propagación de las ondas electromagnéticas en el vacío debía ser constante, y hemos calculado su valor. Además, la velocidad de la luz es también la máxima velocidad de la causa y efecto.

Por otra parte, el segundo postulado fue introducido para preservar las leyes físicas en presencia de observadores inerciales. Para que las leyes de la física fueran las mismas para todos los observadores, las antiguas transformaciones de Galileo, como la de la suma de velocidades:

$$
\begin{align*}
v_f &= \sum_{i=0}^{n}{v_i}
\end{align*}
$$

tenían que ser sustituidas por otras, ya que estas llegaban a paradojas como la paradoja de la adición de velocidades; que ocurre porque $v_f$ puede ser mayor que $c$ sin que ningún término $v_i$ la exceda.

Hendrik Antoon Lorentz era un físico neerlandés que desarrollo el tipo de transformaciones que llevan su nombre: "transformaciones de Lorentz." Estas ecuaciones matemáticas describen cómo las medidas de espacio y tiempo se relacionan entre dos observadores en movimiento relativo uniforme.

En las transformaciones se introduce un factor denominado "factor de Lorentz" representado con la letra griega $\gamma$, que se define como:

$$
\begin{align*}
\gamma &= \frac{1}{\sqrt{1-\frac{v^2}{c^2}}}
\end{align*}
$$

y aplica a cualquier objeto en función de su velocidad.

El espacio y el tiempo pasan a ser interdependientes con las transformaciones de Lorentz, y las siguientes fórmulas describen cómo pasar de un sistema de referencia a otro:

$$
\begin{align*}
t' &= \gamma \left(t - \frac{vx}{c^2}\right) \\
x' &= \gamma \,(x - vt) \\
t &= \gamma \, t'
\end{align*}
$$

donde la adición de velocidades ya no es la adición clásica, sino una transformación que tiene en cuenta los efectos relativistas:

$$
\begin{align*}
v_f &= \frac{v_1 + v_2}{1 + \frac{v_1 v_2}{c^2}}
\end{align*}
$$

Este tipo de transformación impide que $f$ exceda $c$ siempre que ni $u$ ni $v$ la excedan.

Además, Einstein también añadió otros dos efectos que dedujo a partir de esas ecuaciones iniciales: la dilatación temporal y la contracción espacial:

   - Dilatación temporal: se trata de la ecuación
    $$
    \begin{align*}
    t &= \gamma \, t'
    \end{align*}
    $$
    que hemos expuesto anteriormente. Esta fórmula predice que el tiempo para un móvil en movimiento transcurre más lento.
   - Contracción espacial: la contracción espacial sigue la siguiente fórmula:
    $$
    \begin{align*}
    L &= \frac{L_0}{\gamma}
    \end{align*}
    $$
    Este fenómeno nos permite preservar las leyes físicas de forma universal al reducir la longitud de un objeto inercial en eje de la dirección de movimiento.

Las fórmulas de la energía y momento de un objeto también son alteradas para mantener nuestros postulados:

$$
E_t = \gamma \, m c^2 \qquad E_c = (\gamma - 1) \cdot mc^2 \qquad p = \gamma \, m v
$$
> Para una explicación más detallada sobre la relatividad especial, puedes consultar este otro proyecto de investigación[(14)](#bibliografía).

### Relatividad general

La relatividad general, como dijimos antes, es una expansión de la relatividad especial. En ella, la gravedad no se describe como una fuerza, sino como la manifestación de un espacio-tiempo curvo.

El espacio-tiempo es la entidad matemática que describe cómo cambia el espacio en el tiempo y cómo el espacio cambia la percepción del tiempo. La teoría de la relatividad general se basa en tres postulados:

1. El principio de equivalencia, que establece que en regiones suficientemente pequeñas del espacio, un sistema en caída libre es indistinguible de uno inercial.
1. El espacio-tiempo tiene cuatro dimensiones (tres espaciales y una temporal) y puede curvarse. Esta curvatura determina cómo se mueven los objetos por el espacio en el tiempo, ya que sobre el espacio-tiempo los objetos siguen trayectorias geodésicas. La curvatura local del espacio-tiempo depende de la energía presente en las proximidades.
1. El espacio-tiempo se comporta en función a las ecuaciones de campo de Einstein. Esas fórmulas explican el comportamiento del universo y han sido confirmadas por una multitud de experimentos y observaciones con excepcional precisión a lo largo del último siglo.

La relatividad general es una teoría que se basa en la geometría. Einstein interpretaba el espacio-tiempo como un campo (no cuántico) que cubría todo el espacio.

Él no pensaba que hubiese ninguna partícula asociada a este campo, como el gravitón; pensaba que el espacio-tiempo es una cualidad inherente de nuestro universo, mientras que las interacciones a nivel cuántico eran fuerzas.

Es decir, la gravedad no era una fuerza sino una característica intrínseca de nuestro universo. Además, la mecánica cuántica operaba con probabilidades y cantidades discretas, con un enfoque muy diferente al de la relatividad.

¿Por qué no podemos cuantizar la relatividad general? Hacerlo parecería una tarea sencilla, pero al hacerlo ocurren diversos problemas:

   - Superposición del espacio-tiempo: cuando una partícula cuántica está en dos estados excluyentes al mismo tiempo, se dice que se encuentra en una superposición de estados, y lo mismo le ocurre a su campo cuántico asociado. Sin embargo, no se tiene constancia de que el espacio-tiempo se encuentre en una superposición de estados, ya que esto contradeciría la naturaleza bien definida y verificada que presenta el espacio-tiempo.
   - Si tratamos al campo gravitatorio como un campo cuántico convencional, las teorías dan resultados matemáticos infinitos e inconsistentes. La gravedad no ha podido ser renormalizada debido a que las interacciones entre gravitones presentan un comportamiento no lineal.


## Teoría de cuerdas
---

> La información recopilada en este y el siguiente capítulo ha sido obtenida de las referencias 16 a 23.

La teoría de cuerdas es una de las más prometedoras propuestas que pretenden determinar el comportamiento de la gravedad cuántica.

Su principal premisa es muy sencilla: las partículas ya no serán puntos indivisibles, sino que serán cuerdas, es decir, tendrán tamaño aunque sea muy pequeño.

### Superficies

![Relative](/images/8.png) <br> Cuerda elástica representando una cuerda cuántica. <br> Figura $8$.

La figura adyacente explica a qué nos referimos con cuerda. Todo en principio sigue exactamente igual, solo que la partícula ha pasado de ser un punto sin dimensión, infinitamente pequeño, a una cuerda con cierto tamaño.

Esta cuerda, que representa una partícula, la tratamos como una sola entidad. Es decir, la cuerda entera tendrá unos parámetros que la definan (y que determinarán qué tipo de partícula es) pero no diferenciamos entre una parte y otra de la misma cuerda: no existe nada más pequeño que la cuerda en sí que no sea el propio espacio-tiempo.

Que hayamos convertido la partícula de un punto a una cuerda tiene repercusiones al nivel de interacciones. La principal de ellas es que cuando dos partículas, bosones o fermiones, interactúan; transcurre un tiempo en el que las partículas se están fusionando o emitiendo.

![Relative](/images/9.png) <br> Interacción de la figura $7$ según la teoría de cuerdas. <br> Figura $9$. 

Este tiempo se debe a que las partículas ahora no son puntos adimensionales, sino que trazan superficies al moverse. Al trazar superficies, lo que antes considerábamos emitir o recibir una partícula mediadora, ahora requiere que poco a poco, las cuerdas se vayan uniendo, requiriendo tiempo.

También diferenciamos entre dos tipos de cuerdas:

   - Cuerdas cerradas: como la postulada en la imagen superior. Son bidimensionales y trazan una superficie dentro de sí.
   - Cuerdas abiertas: difieren en las cerradas en que han sido "cortadas," y no trazan superficies.

### Armónicos

Las cuerdas pueden vibrar. Estos modos de vibración, que serán armónicos de la longitud de la cuerda, junto con el tipo de cuerda que son determinan sus propiedades (su masa, su carga, su espín...) y por ello los tipos de partículas.

Las fórmulas para tratar estas cuerdas de forma cuántica con sus armónicos son un tanto complejas, pero el proceso lógico para llevarlo a cabo es el siguiente:

1. No podemos tratar las cuerdas como cuerdas en mecánica clásica, por lo que las tenemos que cuantizar. Al cuantizarlas, estamos pasando a tratar con unas fórmulas que modelan la cuerda y facilitan su estudio. Una de ellas es la acción de Polyakov:
    $$
    \begin{align*}
    S_P &= - \frac{1}{4\pi \alpha'} \int d^2 \sigma \sqrt{-h} h^{ab} \partial_a X^\mu \partial_b X_\mu
    \end{align*}
    $$

1. Posteriormente explotamos la simetría conforme e imponemos algunas restricciones como las ligaduras de Virasoro.

1. Una vez hemos hecho eso, podemos extraer el espectro de partículas a partir de los modos de vibración de esa cuerda.

### Gravitón

La teoría de cuerdas predice el gravitón como una partícula fundamental. El gravitón se describe como una cuerda cerrada actuando como bosón. Eso quiere decir que hemos cuantizado la gravedad.

> En realidad, aunque sí que hemos conseguido describir la gravedad a efectos cuánticos, el consenso científico no lo considera como tal. Esto se debe a que la teoría de cuerdas no representa nuestro universo de forma precisa, como veremos en el próximo capítulo.

El gravitón, además, actúa de manera extraña, aunque algunas predicciones de sus propiedades apuntan a que:

   - Su espín debería ser $2$ (como hemos dicho previamente), ya que la interacción afecta el tensor de rango $2$ energía-momento. Eso quiere decir que la gravedad interactúa con la energía (dándole energía potencial gravitatoria a las partículas) y el momento (acelerando los cuerpos hacia el centro de gravedad).
   - No tiene masa, por lo que se propaga a la velocidad de la luz, aunque esto no se ha comprobado experimentalmente ya que todavía no se ha detectado ningún gravitón. Aún así, las últimas observaciones[(15)](#bibliografía) predicen que si el gravitón tuviese masa, sería inferior a $1.2 \cdot 10^{-22} \, eV/c^2$.
   - Es muy difícil de detectar. Este fragmento del artículo de Wikipedia sobre el gravitón explica por qué y cómo de difícil es: «La detección inequívoca de gravitones individuales, aunque no está prohibida por ninguna ley fundamental, es imposible con cualquier detector físicamente razonable. La razón es la extremadamente baja sección transversal para la interacción de los gravitones con la materia. Por ejemplo, un detector con la masa de Júpiter y una eficiencia del 100%, situado en una órbita cercana a una estrella de neutrones, sólo podría observar un gravitón cada 10 años, incluso en las condiciones más favorables.»

Un problema que sí que resuelve la teoría de cuerdas relacionado con el gravitón es el que presentamos al final del capítulo gravedad:

Decíamos que la gravedad no había podido ser renormalizada porque los gravitones interactuaban de forma no lineal. Pero tratando al gravitón como una cuerda, sí que se pueden reformular los cálculos para dar lugar a resultados coherentes.


## Problemas
---

La teoría de cuerdas, aunque ha conseguido solucionar algunos problemas relacionados con la unificación de las fuerzas en búsqueda de una teoría del todo; presenta tres grandes problemas o inconvenientes.

Debido a estos problemas han surgido algunas otras teorías, principalmente derivadas de ésta, como la teoría de supercuerdas, la teoría M o la supergravedad.

### Dimensiones

En la versión más aceptada de la teoría de cuerdas, se requiere un total de $25$ dimensiones espaciales y $1$ dimensión temporal para su consistencia matemática.

Esta característica inherente de su formalismo matemático es frecuentemente ridiculizada, ya que en el universo en el que existimos, las $4$ dimensiones espacio-temporales parecen ser las únicas que existen y no tenemos ninguna prueba de que hayan $22$ dimensiones espaciales más.

La única posibilidad de que estas $22$ dimensiones existieran es que estuviesen compactificadas, o enrolladas en sí mismas. A este tipo de dimensiones se les conoce como dimensiones Calabi-Yau.

### Bosones

El segundo problema de esta teoría es que todas las partículas actúan como bosones, es decir, todas las partículas son partículas mediadoras.

Este problema fue solucionado de forma exitosa con la formulación de la teoría de supercuerdas, que es conceptualmente idéntica a la de cuerdas pero añade unas entidades matemáticas en cada punto de cada cuerda llamadas espinores.

### Taquiones

Los taquiones son un tipo de partícula predicha por la teoría de cuerdas que presentan masa imaginaria ($m = \alpha i$). ¿Qué significa que una partícula tenga masa imaginaria? Nadie lo sabe.

Además, cuenta con una serie de propiedades raras, entre ellas:

   - Tienen energía imaginaria.
   - Se mueven a velocidades superiores a la de la luz, por lo que violan el principio de causalidad y no pueden interaccionar con nada.
   - Pierden energía (en su componente imaginaria) cuanto más rápido vayan, por lo que siempre están acelerando.

Estas partículas no se consideran reales, principalmente porque no se puede comprobar si existen o no, eluyendo así el dominio de la ciencia. Su existencia sería más bien una pregunta de la metafísica.


## Conclusión
---

En este proyecto de investigación hemos tratado las bases de la teoría de cuerdas, desde el Modelo Estándar, pasando por la relatividad hasta llegar a la teoría de cuerdas.

Este trabajo ha servido a modo de introducción al campo de la física de partículas, o física de alta energía, aunque además hemos cubierto algunos temas de importancia para el futuro examen de la PAU que muchos alumnos tomarán.


## Bibliografía
---

<!-- Código = línea - 313 -->

1. [CSScribe.](https://github.com/alejandro-vaz/CSScribe) <!-- FIXED -->
1. [Repositorio oficial.](https://github.com/alejandro-vaz/teoria-de-cuerdas) <!-- FIXED -->
1. [Historia de la física.](https://es.wikipedia.org/wiki/Historia_de_la_f%C3%ADsica?utm_source=chatgpt.com) <!-- FIXED -->
1. [Catástrofe ultravioleta.](https://es.wikipedia.org/wiki/Cat%C3%A1strofe_ultravioleta?utm_source=chatgpt.com) <!-- FIXED -->
1. [Zoología de partículas.](https://en.wikipedia.org/wiki/Particle_zoo) <!-- FIXED -->
1. [Premio Nobel $1979$.](https://en.wikipedia.org/wiki/Standard_Model) <!-- FIXED -->
1. [El electronvoltio.](https://en.wikipedia.org/wiki/Electronvolt) <!-- FIXED -->
1. [El tauón.](https://en.wikipedia.org/wiki/Tau_(particle)#Tau_decay) <!-- FIXED -->
1. [El bosón de Higgs.](https://es.wikipedia.org/wiki/Bos%C3%B3n_de_Higgs) <!-- FIXED -->
1. [El bosón de Higgs - David Blanco.](https://tienda.rba.es/coleccionables/un-paseo-por-el-cosmos?utm_source=google.com#collection-section) <!-- FIXED -->
1. [Detección de ondas gravitacionales, fuente 1.](https://www.agenciasinc.es/Noticias/Deteccion-historica-de-ondas-gravitacionales?utm_source=google.com) <!-- FIXED -->
1. [Detección de ondas gravitacionales, fuente 2.](https://www.virgo-gw.eu/los-detectores-ligo-y-virgo-reanudan-la-observacion-de-ondas-gravitacionales/?utm_source=google.com) <!-- FIXED -->
1. [Ecuaciones de Maxwell.](https://es.wikipedia.org/wiki/Ecuaciones_de_Maxwell) <!-- FIXED -->
1. [Relatividad especial explicada de forma sencilla - Alejandro Vaz.](https://github.com/alejandro-vaz/teoria-de-cuerdas/blob/91fa1ec63b35b25853a169de1e52fbb138587bc0/step-4/Relatividad%20especial%20explicada%20de%20forma%20sencilla.pdf) <!-- FIXED -->
1. [Masa del gravitón.](https://pdglive.lbl.gov//DataBlock.action?node=G033M) <!-- FIXED -->
1. [La materia oscura - Alberto Casas.](https://tienda.rba.es/coleccionables/un-paseo-por-el-cosmos?utm_source=google.com#collection-section)
1. [Los agujeros negros - Antxon Alberdi.](https://tienda.rba.es/coleccionables/un-paseo-por-el-cosmos?utm_source=google.com#collection-section)
1. [El vacío y la nada - Enrique F. Borja.](https://tienda.rba.es/coleccionables/un-paseo-por-el-cosmos?utm_source=google.com#collection-section)
1. [Espacio-tiempo cuántico - Arturo Quirantes.](https://tienda.rba.es/coleccionables/un-paseo-por-el-cosmos?utm_source=google.com#collection-section)
1. [Las constantes universales - Jesús Navarro.](https://tienda.rba.es/coleccionables/un-paseo-por-el-cosmos?utm_source=google.com#collection-section)
1. [String theory - Joseph Polchinski.](https://nucleares.unam.mx/~alberto/apuntes/polchinski1.pdf)
1. [A First Course in string theory - Barton Zwiebach.](https://ia801201.us.archive.org/3/items/AFirstCourseInStringTheory2eZwiebach/A%20First%20Course%20in%20String%20Theory%202e-Zwiebach.pdf)
1. [String theory - ScienceClic English.](https://www.youtube.com/watch?v=n7cOlBxtKSo&t=489s)
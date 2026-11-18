# Caso 10 — Resolución

> Transcripción de consulta del documento original `Caso 10.docx`. Se conserva el texto extraído; para conservar el formato y elementos originales, el DOCX debe adjuntarse por una vía de carga binaria.

<PARSED TEXT FOR PAGE: 1 / 22>Caso 10

Parte 1: Semana 7

1. Datos iniciales y parámetros del sistema

       Demanda diaria (): 600 documentos
       Tiempo neto disponible:
       Composición del paquete base: 3 documentos de la Familia A y 2 documentos de la
        Familia B (, total por paquete = 5 documentos).
       Capacidad de paquetes: .

2. Cálculos para el Método Base

A partir de la tabla de tiempos del método Base (en segundos por documento):

       Preparación (PA):
           o Familia A = | Familia B =
           o Carga por paquete (Base):
       Escaneo Automático (SA):
           o Familia A = | Familia B =

                image_09676e.jpg

           o Carga por paquete (Base):
       Revisión (RA):
           o Familia A = | Familia B =
           o Carga por paquete (Base):

Cálculo de Capacidades y Cuello de Botella (Método Base):

Para 120 paquetes diarios:

       Carga total de Preparación:
       Carga total de Escaneo: (Supera el tiempo neto de 390 min; la línea se satura).
       Carga total de Revisión:

        Cuello de botella: El recurso con mayor carga es el Escaneo, ya que requiere 420
        minutos de trabajo frente a los 390 minutos netos disponibles por jornada. Por lo
        tanto, la capacidad actual con el método Base no satisface la demanda de 600
        documentos sin ajustar tiempos o utilizar una alternativa.

3. Evaluación de Alternativas (A, B y C)

Evaluando las cargas totales de los 120 paquetes para cada método alternativo suministrado:<PARSED TEXT FOR PAGE: 2 / 22>       Método A:
          o PA:
          o SA:
          o RA:
          o Costo:
       Método B:
          o PA:
          o SA: (¡Escaneo optimizado!)
          o RA:
          o Costo:
       Método C:
          o PA:
          o SA: (Entra en el límite de 390 min)
          o RA:
          o Costo:

        Decisión de menor inversión: El Método C reduce el tiempo de escaneo a 364
        minutos (menor a los 390 minutos disponibles) con un costo de 140 UM, siendo
        una opción más económica que el Método B (220 UM) para cumplir con los 600
        documentos diarios.

Parte 2: Semana 11

1. Muestreo de Estados del Escáner

A partir de los datos de conteo obtenidos en la jornada:

       Escáner en ciclo =
       Escáner espera preparación =
       Escáner espera espacio de revisión =
       Total de observaciones ():

Cálculo de la proporción en ciclo ():




Cálculo del tamaño total de muestra para un margen absoluto (con de confianza, ):




Como el estudio actual cuenta con 180 observaciones, se recomienda ampliar el muestreo a 323
observaciones para garantizar la precisión estadística solicitada.<PARSED TEXT FOR PAGE: 3 / 22>2. Análisis Ergonómico (Percentiles P5, P50, P95)

Utilizando las tablas antropométricas proporcionadas en la imagen:

      Altura de codo sentado desde el suelo:
           o

               image_09676e.jpg

           o

               image_09676e.jpg

           o

               image_09676e.jpg

      Alcance cómodo frontal:
           o
           o

               image_09676e.jpg

           o

       Recomendación de diseño: Para acomodar al rango poblacional adecuado
       (enfocándose en proteger al personal de menor estatura o percentile menor
       como ), la superficie de trabajo debe regularse a una altura de 20 mm por debajo
       del codo sentado (es decir, para el ajuste base), asegurando que los materiales
       frecuentes se encuentren dentro del alcance frontal del () para evitar
       sobreesfuerzos y fatiga postural.

Lo que pide la Parte 1 (Semana 7 adicional):

   1. Diagramas<PARSED TEXT FOR PAGE: 5 / 22>Recorrido Superpuesto A/B (Cálculo de Distancias Totales)

                                Recurso       Distancia     Distancia
 Paso     Ruta de Proceso
                                Implicado     Familia A     Familia B

          Recibir paquete e
 1                              Preparación   0m            0m
          identificar familia

          Llevar a mesa de
 2                              Preparación   3m            3m
          preparación

          Ordenar hojas y
 3                              Preparación   0m            0m
          quitar separadores

          Preparar guía de
 4        formato especial      Preparación   0m            0m
          (solo B)

          Comprobar orden y
 5                              Preparación   0m            0m
          alimentar bandeja

          Entregar al
 6        alimentador del       Preparación   4m            4m
          escáner

          Ejecutar escaneo
 7                              Escáner       0m            0m
          automático<PARSED TEXT FOR PAGE: 6 / 22>                              Recurso     Distancia   Distancia
Paso    Ruta de Proceso
                              Implicado   Familia A   Familia B

        Trasladar y revisar
8       integridad de la      Revisión    2m          2m
        copia

        Llevar B a bandeja
9                             Revisión    0m          6m
        especial y volver

        Registrar y
10      almacenar             Revisión    1m          1m
        reproducción

        Recorrido por
TOTAL                         —           10 m
        documento<PARSED TEXT FOR PAGE: 7 / 22>2. Interpretación de la suma de tiempos:

    Comparación y Justificación de la Suma de Tiempos en Serie

    1. Qué representa la suma ():

   Representa el tiempo total de procesamiento acumulado (throughput time o
    tiempo de recorrido) que tarda un único paquete desde que entra a recepción
    hasta que se almacena, asumiendo que avanza por las tres estaciones sin esperas
    en fila.

   Cálculo por método (mezcla 3A / 2B):

       o   Base: .

       o   Método A: .

       o   Método C: .

    2. Por qué NO equivale al intervalo de salida en régimen estable:

   Como se observa en el diagrama de flujo, los tres recursos (Preparación, Escaneo
    y Revisión) son independientes y trabajan en paralelo simultáneamente sobre
    paquetes distintos (separados por espacios intermedios o buffers antes y después
    del escáner).

   En régimen estable (steady state), no hay que esperar a que un paquete termine
    todo su recorrido de (Base) o (Método C) para que salga el siguiente; en cambio,
    sale un paquete terminado cada vez que la estación más lenta (cuello de botella =
    Escaneo) completa su ciclo.<PARSED TEXT FOR PAGE: 8 / 22>      Comparación de capacidades (en netos disponibles):

          o   Si se calculara erróneamente sumando los tiempos en serie, se
              subestimaría la capacidad real de la línea (por ejemplo, en el Método C
              daría ).

          o   En realidad, al estar gobernada por el cuello de botella (Escaneo = en el
              Método C), el intervalo real de salida en régimen estable es de , lo que
              permite producir (superando la demanda de ).



   3. Papel del inventario inicial y buffers:

 Absorción de variaciones transitorias y desacoplamiento:

      Los inventarios intermedios (buffers) ubicados entre las estaciones
       (especialmente antes y después del Escáner, que es el recurso cuello de
       botella) actúan como colchones operativos. Permiten desacoplar las operaciones
       de Preparación, Escaneo y Revisión, absorbiendo las pequeñas fluctuaciones en
       los tiempos de manipulación de los documentos sin detener toda la línea de
       producción.

 Mitigación del transitorio de arranque (Primer turno vacío):

      Al iniciar operaciones, la línea se encuentra en un estado transitorio donde
       ningún recurso tiene trabajo avanzado ("línea desde una línea vacía").

      Contar con inventario inicial asegura que las estaciones secundarias tengan
       material disponible de inmediato para procesar, evitando tiempos muertos
       mientras el cuello de botella comienza a liberar el primer flujo continuo.

 Garantía y prudencia en la promesa de entregas:

      La recomendación explícita del caso advierte: "la capacidad es de régimen
       estable, no la promesa de terminar desde una línea vacía. Deben declarar esta
       limitación".

      Por lo tanto, prometer entregas exactas al 100% desde el minuto uno de un
       turno totalmente vacío es un error de planeación; los buffers y el inventario inicial
       garantizan que el sistema pueda cumplir con la demanda proyectada ()
       únicamente una vez que la línea ha alcanzado su régimen estable y
       sincronizado.

 Punto de control y pruebas públicas (Herramienta de decisión - Semana 7):<PARSED TEXT FOR PAGE: 9 / 22>Punto de control y pruebas públicas (Herramienta de decisión - Semana 7): En la
página 53 (Herramienta de decisión y pruebas públicas) se pide registrar las salidas
esperadas (cargas por recurso en , capacidad de paquetes, cuello, capacidad de
documentos e indicadores de demanda y presupuesto) para 3 pruebas obligatorias (y
una 4.ª opcional) antes de programar o automatizar en código/Excel:

     1. Base, , , demanda , presupuesto .

     2. C, , , demanda , presupuesto .

     3. A, , , demanda , presupuesto .

     4. (Opcional) B, , , demanda , presupuesto .

Tabla de Registro de Salidas Esperadas (Pruebas Públicas)
(Cálculos base: ; paquete de con y ).

                        Car
                        gas                 Capaci   Capacida   Indica   Indicador
                               Cuello
               Entra    por                 dad de   d de       dor de   de
 Prueba                        de
               das      Rec                 Paquet   Docume     Deman    Presupue
                               Botella
                        urs                 es       ntos       da       sto
                        o


               Base
               ,                                                No
                               Escane                                    Sí
 1             Dem.     / /                 ()       ()         cumpl
                               o ()                                      cumple
               ,                                                e ()     ()
               Presu
               p.

               C,
               Dem.                                             Sí       Sí
                               Escane
 2             ,        / /                 ()       ()         cumpl    cumple
                               o ()
               Presu                                            e ()     ()
               p.

               A,
               Dem.                                             No       Sí
                               Escane
 3             ,        / /                 ()       ()         cumpl    cumple
                               o ()
               Presu                                            e ()     ()
               p.

 4 (Opc.)      B,       / /                 ()       ()         Sí       Sí
                               Escane
               Dem.                                             cumpl    cumple<PARSED TEXT FOR PAGE: 10 / 22>                       Car
                       gas                  Capaci     Capacida      Indica       Indicador
                               Cuello
              Entra    por                  dad de     d de          dor de       de
 Prueba                        de
              das      Rec                  Paquet     Docume        Deman        Presupue
                               Botella
                       urs                  es         ntos          da           sto
                       o


              ,
              Presu            o ()                                  e ()         ()
              p.




Lo que pide la Parte 2 (Semana 11 adicional):

Muestreo de Estados del Escáner (Estadística y Precisión)

A partir del muestreo observado en otra jornada sobre el equipo (no sobre las personas):

      Escáner en ciclo: observaciones

      Escáner espera preparación: observaciones

      Escáner espera espacio de revisión: observaciones

      Total de observaciones ():

A. Proporción en ciclo () e Intervalo Aproximado del 95%:

      Proporción en ciclo:



      Intervalo de confianza aproximado al 95%:




B. Tamaño Total de Muestra para Margen Absoluto de :



(Se requieren observaciones adicionales para alcanzar la precisión solicitada).

2. Interpretación Operativa y Registro Propuesto de Estados<PARSED TEXT FOR PAGE: 11 / 22>      Aclaración clave sobre la interpretación: Aclaración clave sobre la
       interpretación: Que el escáner espere preparación (, observaciones) o
       espacio de revisión (, observaciones) no debe interpretarse como
       desocupación o falta de trabajo de ambas personas (Preparación y Revisión
       pueden estar ocupadas ordenando hojas complejas, preparando guías de
       formato especial o registrando copias mientras la máquina aguarda).



      Registro propuesto para distinguir falta de trabajo vs. bloqueo por revisión
       (y contrastar buffers):



Hoja de Registro de Estados Simultáneos (Escáner + Buffers +
Operarios)
                     Estado      Estado
 N.º                 Buffer      Buffer     Activida
                                                                      Clasificació
 Obs     Estado      Entrada     Salida     d            Actividad
                                                                      n de Causa /
 ./      del         (Antes      (Despu     Operario     Operario
                                                                      Diagnóstico
 Hor     Escáner     del         és del     Preparac     Revisión
                                                                      del Sistema
 a                   Escáne      Escáne     ión
                     r)          r)

                                                                      Operación
                                                                      normal: El
                                                                      escáner
                                            Ordenand                  trabaja sin
                     Con 1       Espaci                  Revisand
                                            o                         interrupcione
         En ciclo    paquete     o libre                 o copia
 01                                         siguiente                 s; los buffers
                     listo       (0 paq.)                anterior
                                            paquete                   cumplen su
                                                                      función de
                                                                      desacoplami
                                                                      ento.


                                                                      Falta de
                                                                      trabajo
                                            Preparan
                                                         Registran    (Starvation):
         Espera      Vacío                  do guía
                                 Espaci                  do /         El escáner
         preparac    (0                     formato
 02                              o libre                 almacena     se detiene
         ión         paquet                 especial
                                 (0 paq.)                ndo          porque el
                     es)                    B
                                                                      buffer de
                                                                      entrada se
                                                                      agotó<PARSED TEXT FOR PAGE: 12 / 22>                 Estado    Estado
N.º              Buffer    Buffer     Activida
                                                               Clasificació
Obs   Estado     Entrada   Salida     d           Actividad
                                                               n de Causa /
./    del        (Antes    (Despu     Operario    Operario
                                                               Diagnóstico
Hor   Escáner    del       és del     Preparac    Revisión
                                                               del Sistema
a                Escáne    Escáne     ión
                 r)        r)

                                                               (variabilidad
                                                               en Familia
                                                               B), no por
                                                               ociosidad del
                                                               operario.


                                                               Bloqueo por
                                                               revisión
                                                               (Blocking):
                                                               El escáner
                                                               termina su
                                                               ciclo pero no
                           Lleno                  Llevando
      Espera                          Esperand                 puede
                           (1                     Ba
      espacio    Con 1                o espacio                descargar; el
                           paquet                 bandeja
03    de         paquete              en mesa /                buffer
                           e sin                  especial
      revisión   listo                ordenand                 intermedio
                           retirar)               (6 m)
                                      o                        de 1 paquete
                                                               resulta
                                                               insuficiente
                                                               ante
                                                               traslados
                                                               largos de B.


                                                               Demora por
                                                               alimentació
                                                               n: Hay
                 Con 1                                         material
      Espera     paquet               Ausente /   Revisand     disponible en
      preparac   e listo   Espaci     pausa no    o            el buffer,
04
      ión        (sin      o libre    programa    integridad   pero no se
                 aliment              da                       ha entregado
                 ar)                                           al
                                                               alimentador
                                                               del escáner.<PARSED TEXT FOR PAGE: 13 / 22>Criterios de Decisión para Contrastar el Supuesto de Buffers No
Limitantes:
  1. Validación de Falta de Trabajo (Starvation) vs. Desocupación:


        o   Se clasifica como falta de trabajo real del escáner únicamente cuando:
            Estado Escáner = Espera preparación Y Buffer Entrada = Vacío (0
            paquetes).

        o   Al registrar simultáneamente la actividad del operario de Preparación, se
            demuestra que este se encuentra activo (ej. ejecutando el paso 4 para
            documentos B) y no desocupado.

  2. Validación de Bloqueo por Revisión (Blocking) y Capacidad del Buffer:


        o   En las condiciones del caso se indica que hay espacio intermedio para un
            paquete antes y después del escáner y se pide suponer que no limita la
            capacidad de régimen estable.

        o   Si en el muestreo el estado Espera espacio de revisión (actualmente ,
            observaciones) coincide sistemáticamente con Buffer Salida = Lleno (1
            paquete), se refuta el supuesto de buffer no limitante: la capacidad de
            almacenamiento de 1 solo paquete después del escáner es insuficiente
            para absorber los ciclos largos de revisión de la Familia B (paso 9: llevar a
            bandeja especial y volver, ), bloqueando directamente al recurso cuello de
            botella.
Diseño Ergonómico y Cálculo del Momento Externo

     Regulación Antropométrica de Puestos (Preparación y Revisión)<PARSED TEXT FOR PAGE: 14 / 22>A partir de los datos antropométricos suministrados en el caso (percentiles ,
y ) y aplicando la regla de diseño de situar la superficie de trabajo por debajo
de la altura del codo sentado:

                    Per
                    cen           Percen
 Dimensi                                            Percen           Criterio
                    til           til
 ón                                                 til              de
                    P5P           P50P_{
 Antropo                                            P95P_{           Diseño /
                    _5P           50}P50
 métrica                                            95}P95           Regulaci
                    5             (Medi
 (mm)                                               (Alto)           ón
                    (Baj          o)
                    o)


                                                                     Referen
 Altura
                                                                     cia
 de codo
                                                                     postural
 sentado
                                                                     neutra
 desde el
                                                                     ( en
 suelo
                                                                     codo).


                                                                     Mesa
 Altura
                                                                     regulabl
 regulad
                                                                     e en
 a de
                                                                     altura
 mesa ()
                                                                     ().


                                                                     Material
                                                                     es
 Alcance
                                                                     frecuent
 cómodo
                                                                     es
 frontal
                                                                     dentro
                                                                     de ().<PARSED TEXT FOR PAGE: 15 / 22>   Justificación de diseño: No se debe asumir una sola altura fija para todas las
    personas. El uso de superficies regulables (o sillas ajustables con reposapiés
    para los percentiles bajos) permite que cada operario mantenga los hombros
    relajados y los antebrazos horizontales sin encorvar la espalda ni elevar los
    hombros.
   Disposición de elementos en el puesto:
        o Zona primaria (, alcance del ): Bandejas de entrada y salida de
           paquetes A/B, guías de formato especial y área central de
           ordenamiento/revisión.
        o Apoyo de antebrazos: Borde frontal redondeado y espacio libre de
           apoyo en los primeros de la mesa para descargar el peso de los brazos
           durante la manipulación continua.
        o Pantalla de registro: Ubicada al fondo de la mesa (fuera de la zona de
           manipulación manual, a de distancia visual) con el borde superior a la
           altura de los ojos del operario sentado, evitando reflejos e iluminación
           deficiente.
    2. Comparación Biomecánica del Momento Externo
    Para evaluar el impacto de acercar los materiales frecuentes al cuerpo, se
    calcula el momento flexor externo () generado al sostener o manipular una
    carpeta hipotética de masa () a dos distancias horizontales diferentes:
   Escenario A — Alcance extendido ():

   Escenario B — Alcance cercano recomendado (, dentro del radio ):

   Comparación e Interpretación Metodológica:
      o Al reducir la distancia de alcance de a , el momento externo
         disminuye exactamente en un (de a ), lo que reduce a la mitad la<PARSED TEXT FOR PAGE: 16 / 22>              carga biomecánica exigida a los músculos del hombro (deltoides) y de
              la zona lumbar.
          o   Nota metodológica: De acuerdo con las directrices del caso, este
              cálculo es exclusivamente una comparación física relativa para
              justificar el acercamiento de bandejas y materiales al operario; no
              debe interpretarse como un diagnóstico clínico ni como un límite
              normativo legal.




A. Regulación de Puestos (Preparación y Revisión):

      Altura de superficie de trabajo: Se propone regular las mesas a por debajo de
       la altura de codo sentado:

          o   Para el percentil bajo (): .

          o   Para el percentil medio (): .

          o   Para el percentil alto (): .

          o   Nota de diseño: Como una sola altura fija no sirve para todas las personas,
              se deben utilizar mesas regulables en altura (rango de a ) o sillas
              ajustables con reposapiés.

      Ubicación de materiales frecuentes: Todas las bandejas de alimentación, guías
       de formato especial y herramientas frecuentes deben ubicarse dentro del alcance
       cómodo frontal del () para garantizar que el 95% de los operarios alcancen los
       materiales sin extender el tronco.<PARSED TEXT FOR PAGE: 17 / 22>B. Comparación del Momento Externo (Carpeta hipotética de , ):

       Fuerza gravitacional (): .

       A distancia extendida ():



       A distancia cercana recomendada (, dentro de los del ):



       Interpretación: Acercar la carpeta de a reduce exactamente a la mitad () el
        momento externo sobre el hombro y la zona lumbar. (Nota: Tal como indica el
        caso, este valor es una referencia biomecánica comparativa para ubicar bandejas,
        pantallas y apoyos, y no constituye un diagnóstico médico ni un límite normativo
        legal).

 Análisis de sensibilidad obligatorio (Cambio de mezcla de 3A/2B a 2A/3B)


1. Tabla Comparativa de Cargas y Capacidades (Mezcla 2A / 3B)
                                                         Minu
                                                                  Capac
                                                         tos
                       Carg                                       idad
            Carga               Carga                    Req.
 Méto                  a                   Cuello de              Máxi      Cumple
            Prepar              Revisi                   Esca
 do                    Esca                Botella                ma        Demanda
            ación               ón                       neo
                       neo                                        (Paq. /
                                                         (120
                                                                  Docs)
                                                         paq.)

 Base                                                                       NO
                                           Escaneo
 ()                                                                         CUMPLE
                                           ()
                                                                            ()

                                                                            NO
 A ()                                      Escaneo
                                                                            CUMPLE
                                           ()
                                                                            ()

                                                                            NO
 C ()                                      Escaneo
                                                                            CUMPLE
                                           ()
                                                                            ()
2. Conclusiones del Análisis de Sensibilidad
    1. ¿Cambia el cuello de botella?


           o   No cambia. En las tres alternativas obligatorias (Base, A y C), el recurso
               limitante sigue siendo el Escaneo automático, debido a que los<PARSED TEXT FOR PAGE: 18 / 22>              documentos de la Familia B consumen exactamente el doble de tiempo
              de escaneo que los de la Familia A ( vs. en Base/A; vs. en C).

   2. Factibilidad y Declaración de Incumplimiento:


          o   Ninguna de las alternativas obligatorias (Base, A ni C) cumple con la
              demanda de diarios bajo la mezcla dentro de los disponibles.

          o   Incluso el Método C (que era la opción óptima en la mezcla base ),
              requiere ahora (superando el límite de takt time de ) y alcanza una
              capacidad máxima de (), dejando un déficit de () respecto a la meta.

          o   Declaración final: Siguiendo las reglas del caso ("si ninguna cumple,
              declárenlo sin exigir la extensión opcional"), se declara formalmente que
              la línea es infactible para atender con mezcla bajo el presupuesto y
              métodos obligatorios vigentes, por lo que no debe prometerse dicha
              entrega sin renegociar la mezcla, ampliar el tiempo neto o evaluar la
              extensión opcional (Método B, ).



Lámparas del Bajío»:

      ¿En qué estación creen que está el cuello de botella y por qué?
         o A simple vista pareciera ser Ensamble porque su tiempo unitario es el
            mayor (); sin embargo, al contar con 2 puestos paralelos, su tiempo
            efectivo de salida es de . Por lo tanto, el verdadero cuello de botella es
            Cableado, ya que tiene un solo puesto y tarda (el tiempo de ciclo efectivo
            más largo de toda la línea).

Ronda 1: La capacidad que parece disponible

1. Minutos disponibles por jornada



2. Capacidad de cada estación y de la línea



      1. Preparación:
      2. Ensamble:
      3. Cableado: (Cuello de botella)
      4. Prueba eléctrica:
      5. Empaque:<PARSED TEXT FOR PAGE: 19 / 22>      Capacidad de la línea, estación que la limita y déficit frente a 125 unidades:
       La capacidad de la línea es de , limitada por Cableado, generando un déficit de .

3. Tabla de ocupación (produciendo al ritmo del cuello = )

(Nota: En Ensamble se suman los minutos de los 2 operadores: disponibles).

                     Capacidad         Minutos          Minutos        Ocupación
 Estación
                     (u/jornada)       ocupados         sin ocupar     (%)

 Preparación

 Ensamble (2
 puestos)

 Cableado

 Prueba
 eléctrica

 Empaque

4. Respuesta al gerente sobre contratar a alguien más en Ensamble

      ¿Cambiaría la producción de la línea? No cambiaría en absoluto.
      Cálculo de apoyo: Con un tercer puesto idéntico, la capacidad de Ensamble
       subiría a , pero la salida total de la línea seguiría estancada en porque
       Cableado () continúa limitando el flujo[cite: 6, 7].

5. Acumulación entre Preparación y Cableado

      Si Preparación trabaja a su máxima capacidad () y Cableado conserva su ritmo
       (), se acumularían en el inventario en proceso (WIP) antes de Cableado[cite: 7].

Ronda 2: Lo que ocurre durante la jornada

6. Recálculo con interrupciones () y rechazo () en Prueba eléctrica

      Tiempo disponible de Prueba eléctrica: .
      Nueva capacidad de Prueba eléctrica: .
      Cuello de botella de flujo: Sigue siendo Cableado (), por lo que llegan a
       prueba.
      Cantidad esperada de lámparas conformes (con de rechazo):<PARSED TEXT FOR PAGE: 20 / 22>      Déficit para la meta: .

7. Lámparas necesarias a Prueba eléctrica para lograr 125 conformes



      Redondeando hacia arriba a unidades enteras: Se necesitan llegando a
       Prueba eléctrica por jornada.

Ronda 3: ¿En qué invertirían? y Hoja de Resultados

8. Tabla comparativa de escenarios (Presupuesto máximo: MXN)

(Nota sobre combinaciones de tres: la combinación más barata de tres opciones es , y ;
por lo tanto, ninguna combinación de tres cabe en el presupuesto de ).

                           Cuello
                 Costo                    A prueba        Conformes       ¿Cumple
 Escenario                 (antes de
                 ($)                      (u/jornada)     (u/jornada)     125?
                           empaque)

 Sin
                           Cableado ()                                    No
 mejora

 M1                        Cableado ()                                    No

                           Prueba
 M2                                                                       No
                           eléctrica ()

 M3                        Cableado ()                                    No

 M4                        Cableado ()                                    No

                           Prueba
 M1+M2                                                                    No
                           eléctrica ()

 M1+M3                     Cableado ()                                    No

 M1+M4                     Cableado ()                                    No

                           Prep.,
                           Ensamble,
 M2+M3                                                                    Sí
                           Cableado y
                           Prueba ()

                           Prueba
 M2+M4                                                                    No
                           eléctrica ()<PARSED TEXT FOR PAGE: 21 / 22>                           Cuello
                Costo                      A prueba        Conformes        ¿Cumple
 Escenario                 (antes de
                ($)                        (u/jornada)     (u/jornada)      125?
                           empaque)

 M3+M4                     Cableado ()                                      No

9. Elección de propuesta óptima

      Propuesta elegida: (Guía de cableado + Disponibilidad de prueba).
      Costo total: (deja un ahorro de bajo el tope de ).
      Capacidad esperada: ().
      Margen frente al pedido: de holgura.
      Porcentaje de aumento respecto a la situación real sin mejoras ():



10. ¿Dónde queda la limitación si aplican solo M2 vs. la combinación elegida ()?

      Si aplican solo M2: Cableado sube de a , por lo que el cuello de botella se
       desplaza inmediatamente a Prueba eléctrica (, que sigue perdiendo por
       fallas), entregando solo .
      Con la combinación elegida (): La línea queda balanceada a en cuatro
       estaciones simultáneas (Preparación, Ensamble, Cableado y Prueba eléctrica).
      ¿Una nueva mejora en cableado aumentaría por sí sola la salida? No,
       porque Preparación, Ensamble y Prueba eléctrica seguirían limitando el sistema
       a ().

11. Recomendación breve final

      Opción y costo: Implementar con un costo piloto de .
      Dos cálculos de respaldo: (1) Elimina ambos cuellos sucesivos elevando el
       flujo a Prueba a , y (2) aun conservando el de rechazo, produce ( sobre la meta
       de ).
      Dato por verificar en el piloto: Que la guía de cableado () realmente sostenga
       el ritmo de durante toda la jornada sin aumentar la tasa de rechazo eléctrico por
       errores de armado[cite: 8].
      Condición que haría cambiar la decisión: Si en la práctica el rechazo en
       Prueba eléctrica supera el (es decir, si de unidades se pierden más de
       lámparas, cayendo por debajo de conformes), sería necesario incorporar
       medidas de calidad () o renegociar el presupuesto[cite: 8].

Pregunta Final sobre Variabilidad<PARSED TEXT FOR PAGE: 22 / 22>   El tiempo promedio de una operación es de 4 minutos, pero algunas piezas
    tardan 2 y otras 6. ¿Podemos asegurar que cada hora saldrán exactamente
    15 piezas? ¿Por qué?
        o No se puede asegurar. El cálculo de es solo un promedio esperado a
           largo plazo, no una garantía hora por hora. Debido a la variabilidad en
           los tiempos de proceso, si en una misma hora coinciden varias piezas
           difíciles de (por ejemplo, diez piezas de ocupan los completos), saldrán
           muchas menos de unidades en esa hora, provocando bloqueos o
           tiempos muertos en las estaciones vecinas que no se recuperan de
           inmediato.
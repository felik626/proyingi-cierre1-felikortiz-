**Autor:** [Felik Gabriel Ortiz gomez]

**Fecha:** [20/09/26 ]

  

---

  

## Criterios de viabilidad

  

Una idea es viable para esta materia si cumple los cuatro criterios:

  

1. Atiende un **problema concreto de mi entorno** (mi casa, la IBERO, mi colonia, mi municipio), no un tema general.

2. Tiene una **parte física fabricable** con impresión 3D, corte láser o router CNC.

3. Usa **al menos un sensor o un actuador** controlado por un microcontrolador pequeño.

4. Lo puede construir un **equipo de principiantes en unas ocho sesiones**, con materiales accesibles.

  

---

  

## Idea 1: [robot pintor]

  

**Problema.** [la mayoria de las veces hay pintores que no logran realizar su tarea de forma correcta, haciendo que el material se desperdicie como la pintura y el tiempo no logra usarse de la manera mas optima ]

  

**A quién le pasa.** [Le pasa a instituciones y personas que contratan o hacen trabajos de pintura.]

  

**Dónde lo he visto.** [ en mi familia contratabamos a pintores para pintar nuestra casa y aveces nos quedaba mal o lo hacia mal aunado a que no eficientizaba ni el tiempo ni el material, de igual manera lo pensé una ves que vi la manera de trabajo de los pintores fue cuando hice como click un poco.]

  

**Cómo funcionaría.**

- Qué mide o detecta (sensor): [ (Giroscopio y Acelerómetro); de los cuales el (acelerómetro) detecta la Aceleración en el eje X, Y, y Z, detectando el movimiento eh inclinación; por parte del giroscopio mide la velocidad de giro del dron en los ejes X, Y y Z. Permite saber cómo está rotando. También el (ESP32) que es básicamente el cerebro del dron nos permite hacer la conexión con aplicaciones y con wifi para hacer mas fácil la conectividad inalámbrica; otro sensor llamado (TCS34725) este nos ayudara para el momento de pintar gracias al sensor RGB que detecta los colores que tiene enfrente, (deposito de pintura) y (bomba) para guardar la pintura y tener un sistema con presión para que la pintura tenga un buen uso, (sistema de aplicación) como spray y por ultimo la estructura suficientemente grande para cargar todos los componentes ya mencionados ]

- Qué hace con eso (actuador, aviso, pantalla): [  el giroscopio y acelerómetro funcionan para que el dron se mantenga estable, por parte de el sensor TC34725 mediante esta volando siguiendo los puntos en el espacio puede localizar que lugares siguen sin pintarse o que lugares ya no hay necesidad, se necesita un sistema de aplicación para que logre que la aplicación de la pintura uniforme mediante en el sensor TC34725, por ultimo y mas importante el cerebro que tiene de nombre ESP32 siendo el centro de control siendo de mucha ayuda para conectarse entre aplicaciones y usarse de lejos porque tiene wifi]

- Qué pieza habría que fabricar: [ se tendría que fabricar la base completa del dron, con algun diseño para poder sostener cada uno de sus elementos, y bueno el sistema de aplicación tendría que armarlo con algún sistema de presión que este conectado al sensor TC34725 ]

  

---

  

## Idea 2: [silla de ruedas inteligente]

  

**Problema.** [hay tareas que para personas con discapacidades diferentes que llegan a ser difíciles como el subir escaleras o solo no logran tener la fuerza para controlar la silla de ruedas en la que están postrados  ]

  

**A quién le pasa.** [ le pasa a la gente discapacitada de diferentes maneras por diferentes circunstancias]

  

**Dónde lo he visto.** [ lo eh visto en el diario, la manera en que a veces se limitan las personas a a hacer diferentes actividades por la manera en que las instalaciones o no llegan a ser empáticas con las personas en sus condiciones o solo no llega a ser una cuestión fácil de abordar por la propia persona ]

  

**Cómo funcionaría.**

- Qué mide o detecta (sensor): [sensor ultra sónico detecta si hay algún obstáculo delante o a los lados, un sensor lidar medir distancias con mayor precisión, un sensor mp6050 para medir la inclinación de la silla, unos encoder para saber cuanto giraran las orugas que serán las ruedas se la silla, otro sensor pero para la altura y distancia y ya por ultimo una cámara ]

- Qué hace con eso (actuador, aviso, pantalla): [ bueno claro solo puse los sensores pero la idea en si es hacer una silla de ruedas que pueda subir escaleras mediante ruedas con forma de oruga ayudando a tener agarre y no limitar a ninguna persona a realizar actividades; cada sensor ayudara al mecanismo siendo que el sensor lidar ayudara a medir distancias y regular las velocidades para que el conductor no se tenga que preocupar, de igual manera se conecta con el sensor mp6050 que ayuda a poder ver la inclinación de la silla y la misma silla tenga claro de que manera subir las escaleras, el encoder controla lo mas importante que son las orugas ayudando a modificar el funcionamiento de las orugas, claro se necesita un arduino o un cerebro para que todo este conectado, se maneja solo con cada sensor detecta las escaleras o el desnivel con la cámara y intentara subirlo sin problema ]

- Qué pieza habría que fabricar: [ se tendrían que fabricar las orugas, el espacio para cada sensor   ]

  

---

  

## Idea 3: [mochila inteligente]

  

**Problema.** [ desde pequeño siempre eh sido muy olvidadizo y pierdo mis cosas me gustaría hacer una mochila que me avise si después de cada clase tengo todas mis cosas en su lugar ]

  

**A quién le pasa.** [ a personas muy olvidadizas o personas con problemas de atención y niños pequeños que viven en las nubes  ]

  

**Dónde lo he visto.** [ el porblema lo eh visto con amigos conmigo mismo y primos pequeños]

  

**Cómo funcionaría.**

- Qué mide o detecta (sensor): [ necesitaria como todo un cerebro, funcionaria un ESP32, necesitaria sensores de peso para saber si estan las cosas en la mochila, un motor que vibre y un buzzer para un aviso con sonido ]

- Qué hace con eso (actuador, aviso, pantalla): [ en el cerebro se programara para que cada sensor dependiendo la hora revise si las cosas se encuentran en su lugar usando el sensor de peso para tener claro que esta y que no esta en la mochila ]

- Qué pieza habría que fabricar: [ la mayoria son sensores asi que fabricar ciertamente no se ocupa tal vez imprimir en 3d la manera que la mochila se conformara con todos sensores y los motores ]

  

---

  

## Tabla de viabilidad

  

> Instrucción: escribe Sí, No o Parcial en cada celda. Una idea con un "No" no está

> descalificada: lo que se evalúa es que reconozcas el problema, no que las tres ideas

> salgan perfectas.

  

| Criterio | Idea 1 | Idea 2 | Idea 3 |

|---|---|---|---|

| Problema concreto de mi entorno |no | si| no|

| Parte física fabricable | si| si|si |

| Sensor o actuador |si | si|si |

| Construible en ocho sesiones por principiantes | no|no | si|

| Qué tan seguro estoy de lo anterior (alto / (**medio)** / bajo) | | | |

  

## Mi elección

  

**Idea elegida:** [mochila inteligente ]

  

**Por qué.** [es la que necesita menos tiempo y siento que esta fácil de ejecutar claro es todo un sistema de reconocimiento de peso y sensores pero a comparación de la silla de ruedas es mas ejecutable.]

  

**Qué todavía no sé.** [tendría que averiguar donde conseguir los motores sensores y que tipo de material ayudaría a la mochila a no calentarse o solo no llegar a tener problemas, de igual manera a programar cada sensor y el cerebro para que lleguen a tener un coordinación unica ].

Esta sección vale: reconocer la incertidumbre es parte del trabajo de ingeniería.]

  

---

  

## Declaración de uso de IA

  

- **Herramienta utilizada:** [chat gpt 5.6 luna"]

- **Qué le pedí:** [ "que piensas de una silla de ruedas con sensores y orugas para que suba escaleras"]

- **Qué modifiqué o rechacé de su respuesta, y por qué:** [ me dijo que era bueno para un proyecto escolar pero que lo hiciera a escala y me dio algunos datos sensores y nombres de motores, use los nombres y rechace la idea extra que me dio sobre hacerlo con ruedas y las orugas  y cuando encuentres unas escaleras cambie de ruedas a orugas   ]
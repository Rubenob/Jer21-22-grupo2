![image](https://user-images.githubusercontent.com/69243718/138761826-db49e65e-29c3-48c5-ac74-3a8d510415dd.png)
# Game Design Document
## Fase 1 Juegos en red
Practica Juegos en red universidad Rey Juan Carlos 


INFERNO GAMES – EQUIPO 2

![image](https://user-images.githubusercontent.com/69243718/138954050-314060fc-603b-4478-b009-f40c1a3b4787.png)

DANIEL CALDÉS GARCÍA

MATEO HERNANDEZ GONZALEZ

MIGUEL ÁNGEL OSUNA GALINDO

RUBÉN ORTEGA BERRUGUETE


# **ÍNDICE DE CONTENIDO**
[1. Introducción](#_Toc86089968)

[1.1	Concepto del juego](#_Toc86089969)

[1.2	Características principales](#_Toc86089970)

[1.3	Género](#_Toc86089971)

[1.4	Propósito y público objetivo](#_Toc86089972)

[1.5	Jugabilidad](#_Toc86089973)

[1.6	Estilo visual](#_Toc86089974)

[1.7	Alcance](#_Toc86089975)

[2	Mecánicas del juego](#_Toc86089976)

[2.1	Jugabilidad](#_Toc86089977)

[2.2 	Flujo de juego](#_Toc86089978)

[2.3	Personajes](#_Toc86089979)

[2.3.1 El Humano:](#_Toc86089980)

[2.3.2 El ‘Ente’:](#_Toc86089981)

[2.4	Movimientos y físicas](#_Toc86089982)

[2.4.1 Interacción entre elementos](#_Toc86089983)

[2.4.2 Controles](#_Toc86089984)

[3	Interfaz](#_Toc86089985)

[3.1	Diagrama de flujo](#_Toc86089986)

[3.2	Menú principal](#_Toc86089987)

[3.3	Créditos](#_Toc86089988)

[3.4	Selección de perfil](#_Toc86089989)

[3.5	Pantalla de juego](#_Toc86089990)

[3.6	Pantalla de opciones](#_Toc86089991)

[4	Arte](#_Toc86089992)

[4.1	Artes 2D](#_Toc86089993)

[4.1.1 Paletas de color](#_Toc86089993)

[4.1.2 Estilo artistico](#_Toc86089993)

[4.2	Pixel Art o dibujo](#_Toc86089994)

[4.3	Audio](#_Toc86089995)

[5	Diseño de nivel](#_Toc86089996)

[5.1	Mapa](#_Toc86089997)

[5.2	Puzlles](#_Toc86089998)

[6	Comunicación en red](#_Toc86089999)

[7	Diagrama de flujo](#_Toc86089999)

[8	Capturas de pantalla](#_Toc86089999)

# **1. Introducción**

En este documento se tratará el contenido del diseño y desarrollo del videojuego Project G.H.O.S.T, mediante el cual se busca presentar los principales elementos que caracterizan al videojuego, desde el apartado de diseño, sus características técnicas en cuanto a comunicación red, como el apartado gráfico, arte y música.

## 1.1  Concepto del juego

Project G.H.O.S.T. es un videojuego cooperativo donde cada jugador controla a uno de los roles (humano y fantasma), que deben trabajar codo con codo para resolver los rompecabezas que se les presenten y así escapar del psiquiátrico en el que se encuentran atrapados.  

## 1.2  Características principales

- **Planteamiento sencillo**: historia sencilla desarrollada para crear una inmersión suficiente para que los jugadores sientan que tienen un objetivo en común. 

- **Táctica**: resolución de diversos puzles mediante la cooperación entre humano y fantasma. 

- **Dinamismo**: Project G.H.O.S.T debe suponer un desafío mental para los jugadores. 

- **Atmósfera**: Project G.H.O.S.T debe tener diseños de puzles elaborados, siempre imbuidos con un aura tenebrosa a la par de misteriosa.

## 1.3  Género

Project G.H.O.S.T beben de dos grandes géneros:

- **Puzles**: es un género de videojuegos que se caracteriza por exigir agilidad mental al jugador para resolver enigmas por lo regular en una sola pantalla. Involucran problemas de lógica, matemáticas, estrategia, reconocimiento de patrones, completar palabras o hasta simple azar. En Project G.H.O.S.T los jugadores deben colaborar para resolver diversos puzles.  
- 
![image](https://user-images.githubusercontent.com/69243718/138847810-9c528df4-c128-4529-a443-34ab29b19c0b.png)
![image](https://user-images.githubusercontent.com/69243718/138847827-cc10a32d-ed8d-41a1-a684-5f34fdd99d83.png)


- **Aventura Gráfica:** La dinámica de este género consiste en ir progresando en la historia a través de la resolución de diversos rompecabezas, planteados como situaciones que se suceden en la historia, interactuando con otros personajes y objetos.

![image](https://user-images.githubusercontent.com/69243718/138848022-92c70434-0264-4779-826e-c181105682d4.png)
![image](https://user-images.githubusercontent.com/69243718/138848033-39d0df23-a4bd-4f71-a61e-0a3d4a70967b.png)



## 1.4  Propósito y público objetivo

El objetivo principal de Project G.H.O.S.T es ofrecer a los usuarios una experiencia cooperativa inmersiva, atractiva e interesante, a la par que divertida. 

El target para esta producción es de un amplio rango de edad de jugadores no necesariamente muy experimentados en juegos de puzles y exploración; aunque debido a cierto contenido sensible implementado en él, no es apto para usuarios menores de 16 años.

## 1.5  Jugabilidad

Como se ha explicado anteriormente, la jugabilidad va a contar con mecánicas propias de juegos de aventura gráfica combinados con puzles. Algunos ejemplos de mecánicas serían los siguientes:

- En cuanto a la **movilidad**, cada uno de los jugadores controlan a un personaje (al humano, y al fantasma), moviéndose por el escenario de la manera más libre posible. El fantasma puede levitar y atravesar paredes, mientras que el humano sólo puede estar en contacto con objetos físicos.

- Tanto el fantasma como el jugador enfrentarán una serie de **obstáculos** (trampas, mobiliario, etc.), que podrán superar con la ayuda del otro.

- La **dificultad** irá aumentando a medida que el juego avance, haciendo que los jugadores sientan que están progresando.

## 1.6  Estilo visual

Project G.H.O.S.T tiene un estilo visual complejo, con detalles que encajan perfectamente con su **estilo oscuro y lúgubre**. El estilo visual que más encaja con este concepto es el de dibujo **pixelart**, debido a que permite crear escenarios y personajes relativamente complejos en poco tiempo. Los personajes serán definidos con colores oscuros y fríos. 

![image](https://user-images.githubusercontent.com/69243718/138848062-0156c042-5f8e-44b1-a7c4-969f37b46e45.png)
![image](https://user-images.githubusercontent.com/69243718/138848076-a0443927-0891-40a4-bd60-2bef19bb8f18.png)


## 1.7  Alcance

El videojuego contará con un número de puzles suficientes para considerarlo un juego completo con el ciclo de historia principal terminado, pero por el tipo de juego queda abierta la posibilidad de incluir contenido adicional de forma sencilla. Además, está abierto a crear nuevas historias o secuelas a raíz de la realización de este


# **2	Mecánicas del juego**

En este apartado se pretende comunicar las bases de la jugabilidad de Project G.H.O.S.T, se detallarán todas las acciones que ambos jugadores podrán realizar a lo largo de la historia, ya sea como fantasma o humano. Se añaden aquí además todos los personajes del juego, así como objetos y bocetos de las múltiples salas que contiene.

## 2.1	Jugabilidad

- **Puzles**: cada puzle de Project G.H.O.S.T es una prueba que los jugadores deberán superar para salir del psiquiátrico. Escenarios interiores que podrán ser explorados en mayor profundidad a medida que se avance en la historia. Durante los puzles nos encontraremos todo tipo de retos donde los usuarios deberán colaborar como un equipo.

- **Varios focos**: Nuestros personajes se verán sorprendidos al encontrarse en su inicio en una habitación fría, desamparada y sin saber lo que ocurre. Tendrá la posibilidad de moverse con libertad por todo el escenario. El movimiento de los personajes será sobre el plano del suelo, aunque más adelante se darán más detalles sobre ello.

- **Intensidad**: La dificultad de Project G.H.O.S.T viene dada por el aumento de la complejidad de los puzles. Entre desafíos, la intensidad y dificultad irá aumentando, lo que conlleva a una mejor coordinación y comunicación de los jugadores.

- **Progresión del jugador**: Los jugadores progresan a medida que avanzan en la resolución de los puzles, descubriendo nuevas mecánicas u objetos que necesitarán más adelante.

- **Planificación del puzle**: Los jugadores tendrán que reunir los objetos necesarios para su resolución, los cuales estarán por diversas zonas del mapa.


## 2.2 	Flujo de juego

Se detalla aquí todo lo que verán los jugadores desde el momento en que inician el juego hasta completarlo por completo.

Nada más ejecutar el juego, los jugadores podrán ver un Menú Principal, donde encontrarán varios botones: Jugar para iniciar partida, Opciones para llevarlos a los ajustes del juego, y un botón para Salir. Una vez seleccionado Jugar, deberán esperar a establecer conexión, y una vez hecho, aparecerá una pantalla donde elegir si prefieren jugar como espíritu o como humano.

Da comienzo entonces el juego, que se compone de escenas ordenadas que conforman el escenario total de Project G.H.O.S.T. Las salas pueden clasificarse entre salas de puzles, donde los jugadores cooperan para resolverlo y avanzar en la historia; y salas de exploración, que no son más que salas que interconectan las salas de puzles unas con otras. En ambos tipos de sala los jugadores podrán de alguna forma recolectar objetos interactuando con el entorno, estos objetos serán claves para la resolución de determinados rompecabezas.

## 2.3	Personajes

En esta sección describiremos los dos personajes que componen Project G.H.O.S.T.

### 2.3.1 El Humano:

- **Descripción:** Coprotagonista de Project G.H.O.S.T. El Humano no sabe cómo ha acabado en la situación en la que se encuentra. No recuerda nada, tiene una grave amnesia que le ha arrebatado hasta el último de sus recuerdos, aunque parece que estos intentan resurgir desde lo más profundo de su ser. Lo primero que ve al despertar en la habitación en la que se encuentra es a un fantasma. Por alguna razón, el humano no siente miedo, sino una tranquilidad indescriptible, como si estuviera con alguien de confianza. Tras ver que ambos se encuentran de alguna forma atrapados en un lugar desconocido, deciden aunar fuerzas para hallar respuestas y escapar de allí.

- **Habilidades:** Las mismas habilidades que poseería un humano normal y corriente. Es capaz de tocar o coger cualquier objeto físico, abrir puertas, o activar y desactivar cualquier interruptor. No es capaz de ver ni interactuar con nada del ‘plano espectral’.


### 2.3.2 El ‘Ente’:

- **Descripción:** Coprotagonista de Project G.H.O.S.T. No se sabe a ciencia cierta el origen de este espectro, solamente que está por alguna extraña razón fuertemente ligado a un Humano, el cual es el único capaz de percibir su presencia. El ‘Ente’ se siente atrapado en un limbo entre el plano físico de los mortales y el ‘plano espectral’, sin saber qué hacer para llegar al “más allá”. Aun sintiéndose así, decide colaborar con el coprotagonista, ya que piensa que puede servirle de ayuda para conseguir respuestas y ayudarse mutuamente.

- **Habilidades:** El ‘Ente’, a diferencia del Humano, posee diversas habilidades, como la capacidad de traspasar objetos físicos (salvo aquellos que delimiten la escena) y percibir elementos del ‘plano espectral’, otorgándole la posibilidad de recoger objetos o encontrar pistas que el Humano sería incapaz de ver. No es capaz de interactuar con nada del plano físico.

## 2.4	Movimientos y físicas

### 2.4.1 Interacción entre elementos

Project G.H.O.S.T. se desarrolla en un plano sobre el que los personajes pueden desplazarse. De todos modos, el escenario presenta ciertos obstáculos como paredes o mobiliario que solo podrán ser atravesados por el personaje del fantasma. 

Cuando el jugador selecciona un objeto, el personaje lo sacará y lo situará en su mano. En cambio, si el fantasma selecciona un objeto, este se posicionará a su lado flotando. 

Las colisiones que se producirán: 

Personaje - Personaje 

Personaje - Escenario

Fantasma - Límites del escenario

### 2.4.2 Controles

- **Movimiento**: teclas W, A, S, D. 

- **Seleccionar objeto del inventario**: teclas del 1 al 5.

- **Interactuar con un objeto**: click izquierdo sobre el objeto deseado.


# **3	Interfaz**

En esta sección se especifican con detalle cada una de las pantallas que componen Project G.H.O.S.T. Además, se indicarán las transiciones entre ellas, así como la utilidad de cada elemento de la GUI (Graphical User Interface). Las imágenes adjuntas son bocetos que ilustran los componentes que debe contener cada pantalla, no obstante, los artistas podrían hacer cambios en la apariencia y disposición de los elementos si así lo consideran oportuno.

## 3.1	Diagrama de flujo

El siguiente diagrama de estados muestra las pantallas presentes a lo largo de Project G.H.O.S.T. y las transiciones entre ellas.

![image](https://user-images.githubusercontent.com/69243718/138848117-b849df35-ea61-4563-9964-94919b43c721.png)


## 3.2	Menú principal

Se presenta aquí el boceto de la pantalla de Menú Principal:

![image](https://user-images.githubusercontent.com/69243718/138848140-79483ad1-97b1-4ad4-8c79-afbca414c182.png)

Lista y descripción de todos sus componentes: 

- **Botón jugar**: al pulsarlo lleva a la pantalla Selección de Perfil. 

- **Botón opciones**: al pulsarlo lleva a la pantalla de opciones. 

- **Botón salir**: al pulsarlo nos lleva de vuelta al Sistema Operativo. 

- **Logo del equipo de desarrollo.**

- **Fondo**: imagen de nuestros dos personajes en una habitación donde el humano está en una cama dormido mientras que el fantasma le mira. 

## 3.3	Créditos

A continuación, el boceto de la pantalla de Créditos:

![image](https://user-images.githubusercontent.com/69243718/138848166-3c30f923-b4db-49c5-935a-62eab2d60853.png)

Lista y descripción de todos sus componentes:

- **Panel**: texto con los componentes del equipo de desarrollo.

- **Logo del equipo de desarrollo.**

- **Botón menu**: al pulsarlo volvemos al Menú Principal.


## 3.4	Selección de perfil

Se muestra ahora el boceto de la pantalla de Selección de Perfil:

![image](https://user-images.githubusercontent.com/69243718/138848183-ca9a201a-6d26-4a3b-9ccc-101245ab27da.png)


Lista y descripción de todos sus componentes:

- **Fotos de los perfiles / personajes**: foto de cada uno de los personajes posibles a elegir. Se muestra el controlador de cada jugador en el medio y se tienen que colocar en el lado de alguno de ellos.

- **Botón aceptar**: al pulsarlo se toman los perfiles seleccionados y vamos a la pantalla de juego.



- **Botón menu**: al pulsarlo volvemos al Menú Principal.


## 3.5	Pantalla de juego

Boceto básico de la pantalla de Juego:

![image](https://user-images.githubusercontent.com/69243718/138848215-f37155f2-4fd3-45ac-b095-0626a75261fb.png)
![image](https://user-images.githubusercontent.com/69243718/138848223-ecb9bcd4-1031-43dc-8610-9d4135b05afa.png)


Lista y descripción de todos sus componentes:

- **Escenario 3D**: panel de juego.

- **Descripción**: contiene la descripción del objeto activo. 


## 3.6	Pantalla de opciones

Se dispone a continuación el boceto de la pantalla de Selección de Perfil:

![image](https://user-images.githubusercontent.com/69243718/138848245-000f5f2d-20a5-4638-b821-3bf192582f8b.png)


Lista y descripción de todos sus componentes:

- **Botón menu**: al pulsarlo volvemos al Menú Principal.

- **Sonido**: barra para regular.

- **Música**: barra para regular.

- **Brillo**: barra para regular.

- **Pantalla completa**: botón para elegir pantalla completa.

- **Ventana**: botón para elegir modo ventana.




# **4**	**Arte**

Project G.H.O.S.T. debe tener un carácter tétrico a la vez que lúgubre y misterioso. Para nuestros jóvenes protagonistas es todo un reto averiguar cómo han llegado allí y cómo van a conseguir escapar. Los colores deben ser fríos y apagados, los modelos muy básicos y la música acorde al suspense.

## 4.1	Artes 2D

## 4.1.1	Paletas de color

Las imágenes incorporadas en el videojuego deberán mantener el formato .png

En el diseño artístico se mantendrá una paleta de color para todo el proyecto, que no solo unificará todo el estilo visual del videojuego, sino que también dará mayor trasfondo a personajes y escenarios, y guiará al jugador a lo largo de la partida gracias a la simbología del color.

Para los escenarios predominarán paletas de colores grises que gracias a su neutralidad permitirán enfocar mejor la atención del jugador en los personajes principales.

![image](https://user-images.githubusercontent.com/69243718/138955930-97b42fd3-b430-409e-8119-f42fc80ff15c.png)

El amarillo se reservará para momentos puntuales para hacer uso de su aspecto negativo relacionado a la depresión y al suicidio, que sumado al carácter frio y triste de los tonos azules permitirá dar pautas narrativas.

![image](https://user-images.githubusercontent.com/69243718/138955955-a2d8ad91-4d8a-46da-b624-fb1707874e6b.png)
![image](https://user-images.githubusercontent.com/69243718/138955967-e6ae66de-ea9e-411e-b4a6-52c1950da2a3.png)

Haciendo uso de tonos marrones en la vestimenta se consigue crear relación con la depresión y un mal psicológico. Por ello, el personaje principal humano llevará tonos marrones, azules y amarillos. Mientras que el fantasma llevará marrones, azules y morado(magia). Para llamar la atención del jugador reservaremos el amarillo y morado así de forma intuitiva cada jugador sabrá donde tiene que centrar su atención.

![image](https://user-images.githubusercontent.com/69243718/138955998-b4f1f52b-7b0f-47f6-b89b-7ddab54e9cb2.png)


## 4.1.2	Estilo artistico

Para el diseño de personajes se va a seguir un estilo pixel art similar a la obra de Cezary Lucznski <https://www.deviantart.com/luczynski>

![image](https://user-images.githubusercontent.com/69243718/138848271-1c40d17a-4b01-4852-b0c6-680725d287a4.png)


Fuente: <https://www.inkoherence.com/pixel-art-juego-tronos/> Artista: Cezary Lucznski

Para las animaciones se buscará aproximar el trabajo a realizado por “All pixels must die” de Filipe Costa, Matheus Muniz y Paulo Bohrer II. 

(Video: <https://www.youtube.com/watch?v=OLhwdnaoTFg&t=104s> )

![image](https://user-images.githubusercontent.com/69243718/138848311-8c96902e-b477-4409-a41c-11f26382badc.png)

Fuente: https://vsgif.com/gif/3132643

## 4.3	Audio 

Se diferencian dos tipos de audio en Project G.H.O.S.T., la música que acompañará al gameplay en todo momento (la cual estará en formato .ogg), y los efectos de sonido que ayudarán a generar una atmósfera más misteriosa y sombría (convertidos a formato .wav).

**Música:**

- **Menú principal:** música suave y misteriosa en la pantalla principal, menos tensa que las que se pueden escuchar una vez iniciado el juego. Dará una atmósfera de suspense mientras los jugadores esperan establecer conexión.

- **Segunda planta:** se trata de la planta de inicio para los jugadores, donde aún no saben prácticamente nada sobre su situación. Debe ser una música lenta, dará una sensación de tensión a los jugadores, incitándoles a salir de allí lo antes posible.

- **Primera planta o planta baja:** para cuando los jugadores lleguen a esta planta, se habrán acostumbrado a las mecánicas y el estilo del juego, por lo que no será tan necesario que estén en tensión. La música será más relajada en comparación a la planta 1, pero sin abandonar su atmósfera de misterio.

- **Subsuelo:** es el momento de más dudas para los jugadores, el momento crítico de revelación. En este punto, la música llegará a su mayor intensidad y tensión. En parte, deberá oprimir a los jugadores y mantenerlos alerta.

- **Créditos:** una música de piano acompañará a los créditos finales.

**Efectos:**

- **Navegación por la interfaz:** al pasar por cualquier botón del HUD.
- **Selección de un botón**: al hacer click en cualquier botón del HUD.
- **Pasos**: una serie de pisadas que acompañan al movimiento del humano.
- **Goteo**: sonido de gotas cayendo de una cañería.

- **Puerta:** al pasar de una habitación a otra.
- **Viento:** soplido del viento del exterior.
- **Susurros:** débiles susurros que sonarán de vez en cuando.
- **Chirridos:** chirrido metálico al abrir y cerrar puertas.
- **Muebles**: al arrastrar un mueble de un sitio a otro.
- **Objeto encontrado**: al añadir un objeto al inventario.
- **Objeto mundo espectral**: al añadir un objeto al inventario del ente.
- **Plano espectral**: este plano está lleno de entes sufriendo y desesperados por llegar al más allá, por lo que es un sitio donde solo se escuchan sollozos, gritos agónicos y llantos rabiosos de impotencia.


# **5**	**DISEÑO DE NIVEL**

## 5.1	MAPA

El mapa se divide en 4 grandes zonas:

- **La segunda planta**: planta con múltiples habitaciones en la que se encuentran los protagonistas y otros npc del videojuego. Además, hay otras zonas como los baños o la sala de estar para los pacientes.

- **La primera planta, o planta baja**: En esta planta se encuentran el comedor, la recepción, la sala de espera, la sala de taquillas de los empleados, el baño de empleados y la cocina.

- **El patio**: Es un patio con una fuente en el entro, que conecta la zona de recepción, la sala de empleados, el comedor y el edificio de administración (En el mapa referido como ‘mantenimiento’.

![image](https://user-images.githubusercontent.com/69243718/138848350-4db48dd7-9e05-4f6a-8a98-91d1f2daa4cd.png)


- **El subsuelo**: zona final del juego que se desbloquea a medida que los jugadores avancen en el juego.

![image](https://user-images.githubusercontent.com/69243718/138848371-238513e5-f263-45f4-86f3-2aec205fb555.png)



## 5.2	PUZZLES

Durante el desarrollo del videojuego, se podrán reconocer varios tipos de puzles:

- **Reconocimiento de patrones**: Se basan en la observación del mecanismo y cómo le afectan las combinaciones.

- **Combinación:** Se llega a la solución del rompecabezas combinando dos objetos o más del inventario que dan lugar a uno nuevo que puede usarse para resolver un problema.

- **Interacción** **con el entorno**: Se distingue del anterior en que al menos uno de los objetos (o todos) no está en el inventario, bien porque no se pueda recoger, o bien porque no sea necesario combinarlo con nada.


# **6**	**Comunicación en red**

La comunicación en red se manifestará de diversas maneras:

- Mencionado antes, cada jugador puede interactuar y percibir diferentes detalles y objetos según el plano en que se encuentren, por lo que necesitan un medio de comunicación para describir el lugar o compartir pistas entre ellos. Habrá un **chat de texto** para que ambos jugadores puedan comunicarse con total libertad, coordinándose así para la resolución de los puzles.

- Cuando cualquiera de los dos jugadores interactúe con el entorno, esto se verá reflejado en la pantalla del compañero, dando lugar a diversos puzles y mecánicas. Por lo que habrá que actualizar ambas pantallas a la vez según vayan interactuando.

- Se deberá implementar una **sala de espera** en la que los usuarios aguardarán hasta conectarse en parejas para poder iniciar la historia.

# **7. Diagrama de flujo**

Empezamos en la pantalla principal, de la cual podemos ir a la pantalla de juego o a la pantalla de creditos. De la pantalla de creditos se puede volver a la principal y de la de juego a la principal tambien. Una vez demos al boton del play pasaremos al tutorial.

![image](https://user-images.githubusercontent.com/69243718/145733919-4fce37db-c899-4d42-ba3a-12c917eec4ea.png)

# **8. Capturas de pantalla**

Pantalla principal:
Fonndo de pantalla de un hospital pixelart, boton para jugar y otro para ir a la pantalla de creditos.

![image](https://user-images.githubusercontent.com/69243718/145733726-a5def29f-1a8f-4c55-a365-e9f0aff4e577.png)

Pantalla de creditos:
Información sobre los creadores del videojuego y un botón de vuelta atras. 

![image](https://user-images.githubusercontent.com/69243718/145733736-0ec394e7-a98f-4590-89ec-15b550c7c334.png)

Tutorial:
Movimiento, inventario y colisiones. 

![image](https://user-images.githubusercontent.com/69243718/145733682-f7ae1176-24ff-47c4-8780-b9a9dcfc2354.png)

![image](https://user-images.githubusercontent.com/69243718/145733694-eaa323ac-318e-46c8-86a4-5c2af77d4166.png)

![image](https://user-images.githubusercontent.com/69243718/145733700-da36251c-722d-4aa1-bd22-338bc7b05a04.png)

Pantalla de juego:

![image](https://user-images.githubusercontent.com/69243718/145733740-ae32a743-4932-4371-96d6-0be8ccf0b202.png)

Objetos y personajes de la historia:

![image](https://user-images.githubusercontent.com/69243718/145733964-9a2f841c-23dc-40a7-b82f-a412ea8fbbe8.png)

![image](https://user-images.githubusercontent.com/69243718/145733972-8aa9c531-ef38-41df-aadd-3b7483602753.png)

# **9**	**Referencias**
- Ejemplo GDD: Fuente: https://github.com/dsaltares/siontower
- Referencias para animaciones: Fuente: https://vsgif.com/gif/3132643
- Referencias para la creación de los personajes: Fuente: https://www.inkoherence.com/pixel-art-juego-tronos/
  Deviantart del artista Cezary Lucznski
  https://www.deviantart.com/luczynski
- Ejemplos sobre videojuegos de aventura-gráfica: Fuente: https://www.youtube.com/watch?v=QMmL4c2TrY4
- Artículo sobre la teoría del color y paletas de referencia: Fuente: https://soydecine.com/significado-de-los-colores

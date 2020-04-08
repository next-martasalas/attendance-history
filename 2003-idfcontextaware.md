---
title: Marzo | IDF Context-aware
parent: Año 2020
nav_order: 3
---

# IDF Context-Aware computing

## Datos generales
* **Artículo de:** [Interaction Design Foundation](https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/context-aware-computing-context-awareness-context-aware-user-interfaces-and-implicit-interaction)
* **Descripción:** A tablet computer switching the orientation of the screen, maps orienting themselves with the user’s current orientation and adapting the zoom level to the current speed, and switching on the backlight of the phone when used in the dark are examples of computers that are aware of their environment and their context of use. Less than 10 years ago, such functions were not common and existed only on prototype devices in research labs working on context-aware computing.

[Leer artículo](https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/context-aware-computing-context-awareness-context-aware-user-interfaces-and-implicit-interaction){: .btn  .btn-blue }

## Notas
### Notas de los vídeos
* Technology becomes invisible, don't realize that is there. Just use it.
* Things are adapated automatically
* Context information: traffic jams (Ex. Google Maps) More than your position and your target
* Tricky: what the system takes into account to adapt the experience. Make sure that the user understands it.
* Challenge: make these systems understandable
* Context is more than Location
* Multiple sensors but not easy to give that data a meaning. Understanding to process the data. Classification to understand the context.
* Reach to the point that is acceptable, not annoying the mistake
* What if it is wrong modelated? Make sure that doesn't make big impact, that your failure is not expensive
* Make things that are easy and enjoyable. Much more fluent experiences
* **To avoid the feeling of strange behaviour of the system** It's important to give the users tools to understand the system. Know the parameters taken into account to modelate context
* GOAL: Make things easier to concentrate in the main task. Focus on increase **productivity** and efficiency. Automate the boring parts

#### Guidelines
* What sensor is giving information about the real world that is interesting? (regarding to the problem we solve)
* What information can help us and then what sensors can be employed?
* Minimize the cost of error (output guideline) Not increasing the effort in case of error
* You can be creative in the way you use the sensors. Ex. temperature to know if there are people in a room.
* Book with sensors classification
    * Motion and movement: accelerometers, GPS, magnetometers
    * "?" and hearing: camara & microphome, any sensor linked to human perception
    * Temperature
    * Stress levels sensors
    * (New ways of using sensors)
* Adaptation is a natural way of surviving: plants and animals
* Sense is not a sensor, it's much more (talking about human body) We need to process to understand what the sensors (ear) is giving yo us
* The system don't have to take the control, just adjust to our actions (Ex. GPS route changing if we want to go to one specific road) Leaving the human in control

#### Challenges
* Better to get the user into the loop when there is ambiguity. Better choose into 3 option than a whole menu.
* Ambiguity can be solved from both sides, better sensors or user side
* We will have always problems to detect real world. There will be always ambiguity, this is something must no ignore
* The context recognition is going to be wrong sometimes. Designer should be aware. Context information maybe not be accurate
* From academia:
    * Should focus on new sensors to know better what is in the real world
    * What do we adapt?
    * Creation of meta-knoledge
* From Industry
    * Look back into research. What is dumb in our device or system. Why this is not easier?
* No need to be big challenges. Adapting to a context can be as simple as adjusting the brightness of the screen
* Screens adapting to the gravity direction ensures that there is no chance of holding wrong the phone
* The powe of masive data to adapt experiences beyond than one machine
* Ambience adaptation: what if in a bank posters change if they are selling an insurance or morgage. Probably the message you would like to send will be different
* Implicit and explicit interactions. Speed of texting can be a parameter that gices us important info, are you an expert or are you doubting.
* What about privacy? People don't like cameras when you ask them but in reality microphone is much more harming. What you say is more compromising than what is seen
* What information do we need so we can improve a certain aspect in the experience
* The information should be processed near as possible to the sensor for privacy reasons. Ex. if there is a camera to know if the room is being used, the info that should be sent is that, not the whole image
* Be careful with the notion of survelliance. Take serious what people want to share and what they don't want to share



### Subrayado en el artículo (exportado)
* The advantage of this approach is that we can provide optimized user interfaces for a range of contexts.
* many ideas for an exciting user interface for µeach situation:
* If you designed your watch so that it could recognize each of the situations that you had found in your initial research
* transparent meant that the user did not have to care about changes in the environment and could rely on the same functionality independent of the environment.
* the potential to exploit the context of use as a resource to which systems can be adapted.
* In his 1994 paper at the Workshop on Mobile Computing Systems and Applications (WMCSA), Bill Schilit introduces the concept of context-aware
* A system with these capabilities can examine the computing environment and react to changes to the environment.
* context is more than location,
* the time of day, light conditions, the traffic situation on the calculated route or the user’s preferred places.
* In addition to the current GPS position
* If the situation detected is that it is dark and that there is someone moving, the light will be switched on.
* Cars are a prime example: ABS (anti-lock braking system) and ESP (Electronic Stability Program) are integrated in cars and influence their usage in extreme situations.
* These technologies are ubiquitous and have disappeared from the user’s conscious mind.
* the ability of the computer to sense and act upon information about its environment
* also to enable selective responses
* two classes of context were identified, namely personal and environmental context.
* Context is any information that can be used to characterize the situation of an entity.
* pd-net.org
* There is no feature space that is complete and describes all possible option
* for many other sensors there is typically no single and well-understood way for interpreting the sensed information.
* The user’s perception of the surroundings is based on human senses, but relates at the same time to experience and memory.
* The User-Context Perception Model (UCPM) is a model created to help the designer understand the challenge he faces in creating context-aware systems
* If you use it around the area where you live, you may, however, sometimes be surprised about the route it tries to direct you to.
* A prerequisite for creating a minimal awareness mismatch is that the user understands what factors have an influence on the system.
* the user should be made aware of the sensory information that the system uses.
* examples of devices and applications that provide such feedback, e.g. the type of wireless connectivity in a mobile phone and the symbol for GPS reception
* implicit) analysis of the sensory input received from the surroundings and compare this to situations experienced earlier.
* Wide variety of sensors are used to acquire contextual information.
* GPS
* light and vision
* microphones
* accelerometers and gyroscopes
* magnetic field sensors
* proximity and touch sensing
* sensors for temperature and humidity
* physiological context of the user (e.g. galvanic skin response, EEG, and ECG)
* The quality of the information gained may also be improved by using a set of sensors rather than one.
* In order to know how well a context detector works, you need to know the recognition performance for each context.
* This enables the designer to create systems that act differently in different contexts
* the following types of context-awareness:
* take initiative on behalf of the user,
* Proactive
* Adaptive
* functions are triggered based on context
* the basic approach is first to define a set of contexts that are relevant for adaptation
* Designing proactive applications is very difficult because the system has to anticipate what the user wants.
* By making the placement of user interface elements adaptive and the structure of user interface dynamic, we make it harder to learn to use a given user interface.
* Adaptive menus have been available in earlier Microsoft Office versions, and it proved to be a bad idea
* Good designs maintain stability and support the user in memorizing the UI while using context to reduce complexity
* Computers and communication devices are very rude.
* Although technology has changed a lot, some of our behaviour around new technologies are still rooted in an understanding of older technology.
* This behaviour is perhaps rooted in the old model of synchronous telecommunication where phone calls were expensive and important – which is less true nowadays
* ways context can be used to minimize interruptions.
* f we have context available, we could attach meta-information to each word we write
* there is an equally interesting source of data of user-generated information: implicitly user-generated data.
* The basic approach of context-aware resource management is to optimize the operation of a device and its use of resources based on context
* In this case, the whole information on the quality of the network interface, including package loss, delays, SNR, RSS, etc. are represented by five bars, and this abstraction allows the user to reason, even if he does not know much about wireless radios.
* Implicit Human-Computer Interaction (iHCI)
* Implicit Input
* Implicit Output
* Alan Dix used the term incidental interaction
* It is essential that users understand the varying and adaptive behaviour of the application and link it to the situations they are in.
* Location-awareness as a special form of context have become mainstream
* the grand challenge
* create models that allow the individual to control his or her visibility
* Kinect, a motion sensing input device by Microsoft for the Xbox 360 video game console
* , a central challenge is to provide means in the user interface to correct wrong choices made by the system, and in a way where the user feels in control.
* implicitly generated content
* It is our responsibility as system designers to make a better and more interesting world with the tools and technologies we have at our disposal – and context is an extremely powerful one!
* Pervasive Computing


## Reflexiones
Poder adaptar un diseño según el contexto percibido es una ventaja, así podemos optimizar las interfaces para un amplio espectro de contextos.

El contexto históricamente ha sido definido por la ubicación, pero actualmente el contexto es mucho más que eso. En un GPS, además de la información de la ubicación hay otros parámetros de contexto que pueden incluirse  como la hora del día, las condiciones lumínicas, el estado del tráfico...

Los **coches son un ejemplo de adaptación al contexto:** ABS están integrados en los coches e influencian su respuesta en caso de situaciones extremas.

Podemos definir **context-awarenes** como la capacidad de una máquina para percibir y actuar frente a información de su entorno, y también facilitar respuestas seleccionadas.

El **contexto** es cualquier información que puede ser usada en caracterizar la situación de una entidad.

Sobre **User-Context Perception Model** es un modelo creado para ayudar en diseño a entender los retos a los que el usuario se enfrente en sistemas context-aware. Ej. Si usas el GPS en un área que conoces, te sorprenderá a veces la ruta recomendada, sin embargo en una ciudad nueva sentirás que funciona perfectamente.

Para crear un **awareness mismatch** es importante que se entiendan los factores que han influenciado en el sistema para tomar la decisión. Hay muchos ejemplos de dispositivos que ofrecen este feedback, como por ejemplo el tipo de conectividad en los móviles.

**Sistemas de contexto adaptativo**
* Las aplicaciones proactivas toman la iniciativa en lugar del usuario.
* Las aplicaciones adaptativas son similares, la diferencia principal es que las funciones se disparan según el contexto más que en aplicaciones completas. El planteamiento básico es definir un set de contextos que son relevantes para la adaptación.

**Interfaces adaptativas y conscientes del contexto**
* Adaptando los elementos de la interfaz según ciertos parámetros, hacemos más difícil la curva de aprendizaje de uso de la interfaz porque las cosas cambian. Los menús adaptativos de Microsoft Offices han demostrado ser una mala idea.
* El buen diseño debe mantener la estabilidad y ayudar en la memorabilidad de la interfaz mientras hace uso del contexto para reducir la complejidad

**Managing interruptions based on situations**
* Las comunicaciones automáticas son muy rudas, este comportamiento es posible que venga del antiguo modelo de comunicación sincrónica donde las llamadas de teléfono era caras e importantes. Aunque la tecnología ha cambiado mucho, algunos de los comportamientos siguen ancladas en el pasado.
* Apoyarnos en el contexto nos puede ayudar a gestionar estas interrupciones de una mejor manera.

**Gestión de metadastos y contenido generado implícitamente**
* Si tuviésemos contexto, podríamos adjuntar meta información a cada palabra que se escribe
* El interés en los datos generados de forma implícita es también alto:
    * **Implicit Human-Computer Interaction:** la interacción con el entorno y artefactos. El sistema adquiere contenido implicito del usuario y puede presentar un output implicito de vuelta. (*Incidental interaction*)
    * **Implicit Output:** acciones o comportamientos humanos para alcanzar un objetivo que no están considerados como interacción con la máquina pero que se captan e interpretan por el sistema como un input.
    * **Implicit Output:** la respuesta de una máquina que no está directamente relacionado con un input explícito y que está integrado con el entorno y la tarea del usuario.

**Resumen y siguientes pasos**
* Es básico que los usuarios entiendan el comportamiento adaptativo y variante de la aplicación y la conexión con la situación en la que se encuentran.
* Location-awareness es una forma de contexto que es bastante común. El reto mayor es crear modelos que permitan al individuo controlar su visibilidad, a ser posible de forma implícita, con el mínimo esfuerzo posible.
* El reto central es dotar de significado en la interfaz para corregir elecciones incorrectas realizadas por el sistema de una forma que se tenga la sensación de control.
* Es nuestra responsabilidad como system designers hacer unmundo mejor y más interesante con las herramientas y tecnologías que tenemos a nuestra disposición, el contexto es una extremadamente potente.

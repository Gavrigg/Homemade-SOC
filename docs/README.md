
# **Introducción**
Para este proyecto me he servido del vídeo de Zane Ryan, titulado "¿Montar un SOC por componentes o implementar un todo en uno?", donde el ponente explica los servicios de los que se compone un SOC, tanto en su apartado teórico como práctico. Posteriormente, para la implementación más técnica me he servido de otro vídeo de Maurice Frayssinet subido a la plataforma YouTube titulado "Implementación del Centro de operaciones de seguridad (SOC)". En el podemos ver una serie de definiciones más en profundidad, a diferencia del vídeo de Zane Ryan. 

**Esta introducción está en constante cambio, a medida que se añadan recursos y sus fuentes al proyecto se añadirán al apartado actual.**

## **¿Qué es un SOC?**
Un SOC es tradicionalmente una instalación física dentro de una organización, que alberga un equipo de seguridad de la información. Este equipo analiza y supervisa los sistemas de seguridad de la organización. La misión del SOC es proteger a la empresa de las brechas de seguridad mediante la identificación, el análisis y la reacción a las amenazas dax ciberseguridad. Los equipos de SOC están compuestos por gerentes, analistas de seguridad y, a veces, ingenieros de5 seguridad. El SOC trabaja con los equipos de desarrollo y operaciones de TI de la compañía (Frayssinet, 2022).

Se creía que un SOC solo era adecuado para grandes empresas, Hoy en día, muchas organizaciones más pequeñas están estableciendo SOC livianos, como un SOC híbrido, que combina personal interno o a tiempo parcial sin expertos contratados, o un SOC virtual, que no tiene ninguna instalación física en absoluto, y es un equipo de personal interno que también cumple otras funciones (Frayssinet, 2022).

Los SOC son una forma comprobada de mejorar la detección de amenazas, distribuir la probabilidad de violaciones de seguridad y garantizar una respuesta organizacional adecuada cuando ocurren incidentes. Los equipos de SOC aíslan la actividad inusual en servidores, bases de datos, redes, puntos finales, aplicaciones, etc., identifican amenazas de seguridad, las investigan y reaccionan a los incidentes de seguridad a medida que ocurren (Frayssinet, 2022).

### **Funcionamiento del SOC**
Una organización primero debe definir su estrategia de seguridad y luego proprocionar una infraestructura adecuada con la que trabajará en el equipo de SOC. El sistema de información que subyace a la actividad de SOC es un sistema de información de seguridad y gestión de eventos (SIEM), que recopila registros y eventos de cientos de herramientas de seguridad y sistemas organizativos, y genera alertas de seguridad procesables, a las que el equipo de SOC puede analizar y responder.

### **Responsabilidades principales del SOC**

**Mantenimiento de herramientas de monitoreo de seguridad**
El equipo debe mantener y actualizar las herramientas regularmente. Sin las herramientas correctas y más actualizadas, no pueden proteger adecuadamente los sistemas y las redes. Los miembros del equipo deben mantener las herramientas utilizadas en cada parte del proceso de seguridad.

**Mantenimiento de herramientas de monitoreo de seguridad**
El equipo de SOC debe investigar actividades sospechosas y maliciosas dentro de las redes y sistemas. En general, su SIEM o software de análisis emitirá alertas que el equipo luego analizará y examinará, clasificará y descubrirá el alcance de la amenaza.

### **Tipos de SOC**
Existen diferentes enfoques para implementar un Centro de Operaciones de Seguridad (SOC), cada uno con sus ventajas y desventajas según las necesidades y capacidades de la organización. A continuación, se detallan tres opciones principales: construir un SOC por componentes, optar por un SOC todo en uno o externalizar el servicio a un tercero. Cada una presenta distintos niveles de personalización, coste, complejidad e implementación, lo que permitirá a las empresas elegir la solución más adecuada para su contexto.

#### **Opción 1 - Construir un SOC por componentes**

**Desventajas:**
- Comprar piezas de SOC uno por uno
- De distintos fabricantes o incluso del mismo fabricante
- Integrarlos
- Personalizarlos
- Disponer de programadores con experiencia en ciberseguridad
- Reclutar a un equipo de analistas de seguridad
	- Crear un centro de operaciones de seguridad de 24 x 7 x 365
- Formación continua para el equipo de seguridad
- Gestionar e implementar actualizaciones de distintos programas
- Gestionar compras con diferentes fabricantes
- Largo tiempo de implantación y puesta en producción

**Ventajas:**
- Ganar mayor conocimiento y experiencia en el ámbito de ciberseguridad
- Mayor capacidad de personalizar el entorno
- Acabar con un servicio muy ajustado a tus necesidades

___
#### **Opción 2 - Construir un SOC todo en uno**

**Ventajas:**
- No hace falta evaluar un sinfín de productos
- No hace falta integrar diferentes productos
- Sin necesitar un equipo de programadores
- Sin necesidad de preocuparse de problemas de compatibilidad a la hora de hacer actualizaciones
- Puesta en producción rápida
- Escalabilidad ilimitada
- Multi-Tenant Nativo
- No hace falta gestionar compras a múltiples fabricantes
- Tiempo corto de implantación

**Desventajas:**
- Tienes que instalar y mantener el software
- Tienes que montar un SOC
- Tener un equipo de analistas
- Formar y retenerles

___
#### **Opción 3 - Externalizar el servicio a un tercero**

**Ventajas:**
- Eliminas las desventajas de las dos opciones anteriores
- Aprovechas las ventajas de las dos opciones anteriores
- Tendrás la posibilidad de pedir personalizaciones según tus circunstancias
- Coste puede ser menor según la escala de volumen que el MSSP tiene
- Muy corto tiempo de puesta en marcha
- Beneficiar de la experiencia amplia del proveedor del servicio dado que tendrá múltiples clientes

**Desventajas:**
- Dependencia de un tercero
- Sin el beneficio de ganar conocimiento y experiencia por no tener un SOC interno
- Menos posibilidades de personalizaciones
- Coste puede ser mayor


## **Modelos de implementación de SOC**
Existen diversos modelos de implementación de un Centro de Operaciones de Seguridad (SOC), cada uno adaptado a las necesidades y capacidades de la organización. Estos modelos van desde SOC dedicados con personal y recursos internos, hasta opciones más flexibles como SOC virtuales o servicios administrados por terceros (MSSP/MDR). A continuación, se detallan los modelos más comunes, que varían en cuanto a la estructura operativa, el nivel de personalización y la dependencia de recursos externos.

#### **SOC dedicado**
SOC clásico con instalaciones dedicadas, personal dedicado a tiempo completo, operado completamente en casa, operaciones 24x7. Se distingue por su total independencia y autonomía, a diferencia de los demás, ofrece el mayor control y personalización, pero conlleva altos costes y complejidad operativa.


#### **SOC distribuido**
El SOC distribuido se basa en la descentralización de las operaciones de seguridad, utilizando tanto personal a tiempo completo como a tiempo parcial. Este modelo permite que las tareas de monitoreo se dividan geográficamente o por áreas de especialización, lo que optimiza el uso de recursos. Generalmente, su funcionamiento está limitado a un horario laboral estándar de 8x5 en cada región donde opera. Esto puede resultar en una menor cobertura de vigilancia durante las horas no laborales, aunque también reduce costes y facilita la integración en empresas con menos necesidades de seguridad ininterrumpida.

#### **SOC/NOC multifuncional**
Este tipo de SOC combina las funciones de un Centro de Operaciones de Seguridad (SOC) y un Centro de Operaciones de Red (NOC) en una única instalación. Esta integración permite que el equipo dedicado gestione tanto la infraestructura de red como la seguridad, ofreciendo una solución más eficiente y económica. Sin embargo, requiere que el personal posea habilidades especializadas en ambas áreas, lo que puede complicar la contratación y la formación. Este enfoque es ideal para organizaciones que buscan maximizar el uso de sus recursos y mantener una supervisión centralizada de todos los aspectos operativos.

#### **SOC de fusión**
El SOC de fusión representa una evolución del modelo tradicional, añadiendo capacidades avanzadas como la integración de inteligencia de amenazas y la gestión de la seguridad en entornos de tecnología operativa (OT). Esto permite una visión más completa de los riesgos y la capacidad de responder de manera proactiva a amenazas emergentes. Este modelo es particularmente útil para organizaciones que manejan infraestructuras críticas o que desean una seguridad más integrada con sus procesos operativos. No obstante, su implementación requiere una planificación cuidadosa y la adquisición de nuevas competencias técnicas.

#### **Comando SOC/SOC global**
Este modelo actúa como un centro de coordinación centralizado para gestionar y supervisar otros SOC distribuidos dentro de una empresa global. Su función principal es consolidar la inteligencia de amenazas, mantener la conciencia situacional y proporcionar orientación estratégica a los equipos regionales. Este enfoque es ideal para grandes corporaciones multinacionales, ya que permite estandarizar procedimientos y mejorar la respuesta global ante incidentes. Además, facilita la comunicación entre regiones y asegura que las decisiones de seguridad se alineen con los objetivos corporativos.

#### **Virtual SOC**
El SOC virtual destaca por su flexibilidad y bajo coste, ya que no requiere instalaciones físicas ni personal permanente dedicado exclusivamente a las operaciones de seguridad. Este modelo se activa únicamente en respuesta a incidentes de alta prioridad o alertas críticas, lo que lo convierte en una opción eficiente para organizaciones con recursos limitados. Además, el término también se utiliza para describir soluciones proporcionadas por proveedores externos de servicios de seguridad gestionados (MSSP), lo que permite externalizar parcial o totalmente las funciones del SOC.

#### **SOC/MSSP/MDR administrado**
Muchas organizaciones están recurriendo a los proveedores de servicio de seguridad administrados (MSSP) para proporcionar servicios SOC de forma subcontratada. Las ofertas modernas se denominan Managed Detection and Response (MDR). Los SOC administrados se pueden subcontratar por completo o coadministrar con personal de seguridad interno.



### **Tabla organizativa**
La tabla presentada resume las principales opciones y modelos de implementación de un Centro de Operaciones de Seguridad (SOC), destacando sus características clave junto con una evaluación práctica de su complejidad, coste estimado y ejemplos de uso. Incluye desde soluciones altamente personalizables, como los SOC por componentes que requieren recursos significativos, hasta opciones externalizadas como los MSSP, ideales para pequeñas y medianas empresas. También se abarcan combinaciones híbridas y globales que ofrecen flexibilidad para organizaciones con operaciones distribuidas. Esta clasificación tiene como objetivo facilitar la elección del modelo adecuado según las necesidades, capacidades y presupuesto de cada organización.

|             **Opción**             | **Modelos de Implementación**                                                                                                                                                                                                         | **Complejidad** | **Coste Estimado** |                **Ejemplo de Uso**                 |
| :--------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------------: | :----------------: | :-----------------------------------------------: |
| **Opción 1 - SOC por componentes** | - **SOC dedicado**: SOC clásico con instalaciones y personal dedicados, operando 24x7 completamente internas                                                                                                                          |      Alta       |      Muy alto      |      Grandes empresas con recursos internos       |
|   **Opción 2 - SOC todo en uno**   | - **SOC/NOC multifuncional**: Combina funciones de Centro de Operaciones de Red (NOC) y Centro de Operaciones de Seguridad (SOC)<br><br>- **SOC de fusión**: Incorpora inteligencia de amenazas y tecnología operativa (OT)           |      Media      |        Alto        |      Organizaciones con necesidades híbridas      |
|   **Opción 3 - Externalización**   | - **SOC/MSSP/MDR administrado**: Servicios SOC subcontratados a proveedores de seguridad<br><br>- **Virtual SOC**: Equipo reactivo sin instalaciones dedicadas                                                                        |      Baja       |      Variable      |      Pymes que buscan externalizar seguridad      |
|    **Combinaciones Especiales**    | - **SOC distribuido**: Personal a tiempo completo y parcial operando en horarios 8x5 según región<br><br>- **Comando SOC/SOC global**: Coordina SOC a nivel global, proporcionando inteligencia de amenazas y orientación estratégica |   Media-Alta    |        Alto        | Empresas globales con operaciones interconectadas |

## **Funciones y responsabilidades del SOC**

### **Analista de seguridad**
El primero en responder a incidentes. Su respuesta generalmente transcurre en tres etapas:
- Detección de amenazas
- Investigación de amenazas
- Respuesta oportuna

Los analistas de seguridad también deben asegurarse de que se implemente la capacitación correcta y de que le personal pueda implementar políticas y procedimientos. Los analistas de seguridad trabajan junto con el personal interno de IT y los administradores de negocios para comunicar información sobre las ilimitaciones de seguridad y desarrollar documentación.

### **Ingeniero/Arquitecto de seguridad**
Mantiene y sugiere herramientas de monitoreo y análisis. Crean una arquitectura de seguridad y trabajan con los desarrolladores para garantizar que esta arquitectura sea parte del ciclo de desarrollo. Un ingeniero de seguridad puede ser un especialista en software o hardware que presta especial atención a los aspectos de seguridad al diseñar sistemas de información. Desarrollan herramientas y soluciones que permiten a las organizaciones prevenir y responder eficazmente a los ataques. Documentan procedimientos, requisitos y protocolos.

### **Gerente de SOC**
Administra el equipo de SOC e informa al CISO. Supervisan al equipo de seguridad, proporcionan orientación técnica y administran las actividades financieras. El gerente de SOC supervisa la actividad del equipo de SOC, incluida la contratación, capacitación y evaluación del personal. Las responsabilidades adicionales incluyen la creación de procesos, la evaluación de informes de incidentes y el desarrollo e implementación de planes de comunicación de crisis. Escriben informes de cumplimiento, respaldan el proceso de auditoría, miden las métricas de rendimiento de SOC e informan sobre las operaciones de seguridad a los líderes empresariales.

### **CISO**

Define las operaciones de seguridad de la organización. Se comunican con la gerencia sobre problemas de seguridad y supervisan las tareas de cumplimiento. El CISO tiene la última palabra sobre las políticas, estrategias y procedimientos relacionados con la ciberseguridad de la organización. También tienen un papel central en el cumplimiento y la gestión de riesgos, e implementan políticas para satisfacer demandas de seguridad específicas.

___
# **Justificación**

El diseño e implementación de un SOC doméstico tiene como objetivo demostrar mis habilidades y conocimientos adquiridos en el análisis y respuesta ante incidentes de ciberseguridad, especialmente en el rol de analista L1. Este proyecto está estructurado para reflejar las funciones y responsabilidades típicas de un SOC, lo cual me permitirá aplicar de manera práctica los conocimientos obtenidos durante mi aprendizaje. En el caso de un analista de seguridad, que es la figura central de este proyecto, mi enfoque se centrará en la detección, investigación y respuesta ante incidentes de seguridad. El analista L1 es la primera línea de defensa, responsable de detectar amenazas a través de sistemas de monitoreo, investigar alertas y responder de manera adecuada y rápida. Como parte de este proyecto, trabajaré para configurar las herramientas necesarias para identificar amenazas, procesar alertas y documentar incidentes, lo cual simula las responsabilidades diarias de un analista de seguridad.

Aunque el proyecto no abarca las funciones de ingenieros de seguridad o gerentes de SOC, es relevante entender cómo estos roles influyen en la infraestructura y operación del SOC. En este proyecto, me enfocaré principalmente en la configuración de las herramientas, la implementación de sistemas para la recolección y análisis de datos de seguridad, y la mejora continua de estos sistemas, lo que refleja las tareas básicas de un analista de seguridad que trabaja estrechamente con estos otros roles. El **CISO**, aunque no es directamente responsable de las operaciones cotidianas en un SOC pequeño, juega un papel importante en la creación de políticas de seguridad. Este proyecto se alinea con las estrategias de ciberseguridad y cumplimiento definidas por un CISO, ya que la estructura de trabajo y la documentación que genere serán un reflejo de las políticas y procedimientos que un SOC debe seguir.

A través de la simulación de estas funciones y roles dentro de un entorno controlado, este proyecto busca no solo demostrar mis habilidades técnicas, sino también mi capacidad para trabajar en un equipo y colaborar en la identificación y resolución de problemas de seguridad en un contexto práctico, alineado con los objetivos y expectativas de un analista L1 en un entorno profesional de ciberseguridad.

## **Tipo de SOC elegido**
Para el desarrollo de este proyecto, he optado por implementar un **SOC virtual** debido a varias razones que facilitan la creación de un centro de operaciones de seguridad en un entorno doméstico. La principal ventaja de un SOC virtual es la flexibilidad y la reducción de los costes asociados con la infraestructura física, pues al no requerir de instalaciones dedicadas ni un equipo de personal a tiempo completo, puedo gestionar todo el proceso desde un entorno controlado en casa, lo que hace posible adaptar el proyecto a mis capacidades y recursos disponibles.

Además, el SOC virtual ofrece una notable escalabilidad, ya que permite iniciar con una configuración básica e ir añadiendo funcionalidades conforme crecen las necesidades o la experiencia adquirida. Esto lo convierte en una solución práctica para proyectos pequeños como este, entornos domésticos o de aprendizaje, con recursos limitados. Además, su implementación es accesible gracias a la amplia disponibilidad de herramientas de código abierto o de bajo coste, lo que facilita su adopción sin comprometer el presupuesto. Por último, destaca por su rapidez de implementación, evitando los tiempos prolongados asociados a instalaciones físicas y permitiendo que esté operativo en un plazo mucho más corto.

## **Limitaciones del proyecto**
Una de las limitaciones que enfrentaría al optar por un **SOC dedicado** sería la necesidad de gestionar una infraestructura física más compleja, lo cual, además de aumentar los costes, demandaría más tiempo y esfuerzo para el mantenimiento de las herramientas y la configuración de las redes y servidores. Este tipo de implementación también implicaría una mayor complejidad en la contratación de recursos, como analistas de seguridad o programadores, algo poco viable para un proyecto personal en el que se busca una experiencia autodidacta.

## **Ventajas del proyecto**
Por otro lado, al optar por un SOC virtual, no solo optimizo los recursos, sino que puedo integrar herramientas y soluciones de seguridad de manera modular, adaptando las herramientas a mis necesidades y aprendiendo sobre cada componente de forma más práctica y eficiente. Aunque en un SOC virtual se pierde algo de control sobre la infraestructura, la posibilidad de activar herramientas y capacidades solo cuando sea necesario me permite simular un entorno real eficientemente.

En resumen, un **SOC virtual** me permitirá trabajar de forma más flexible y económica, manteniendo el enfoque en la adquisición de conocimientos prácticos sin sobrecargarme de tareas logísticas. Además, este modelo me proporciona la oportunidad de integrar soluciones de seguridad de una manera escalable, lo que resulta ideal para un proyecto como el que estoy llevando a cabo.

___
# **Objetivos del proyecto**

El propósito de este proyecto es diseñar, implementar y documentar un Centro de Operaciones de Seguridad (SOC) funcional en un entorno doméstico, utilizando herramientas accesibles y técnicas adecuadas para desarrollar una experiencia práctica en ciberseguridad. A través de este proceso, se pretende obtener una comprensión más profunda de los principios y prácticas del SOC, y adquirir habilidades que sean relevantes para futuras oportunidades profesionales en el campo de la ciberseguridad.

### **Objetivos Generales**
Diseñar, implementar y documentar un SOC (Centro de Operaciones de Seguridad) funcional en un entorno doméstico, utilizando herramientas y técnicas accesibles, con el propósito de:

1. **Desarrollar habilidades prácticas** en análisis, supervisión y respuesta ante amenazas de ciberseguridad.
2. **Obtener experiencia demostrable** que sea relevante para roles profesionales en el ámbito de ciberseguridad.

### **Objetivos Específicos**

1. **Estudio de Conceptos Fundamentales**
    - Comprender los servicios y funciones clave que componen un SOC, integrando tanto aspectos teóricos como prácticos
    - Investigar y aplicar principios de gestión de eventos e información de seguridad (SIEM)

2. **Implementación Técnica**
    - Configurar un entorno doméstico que simule un SOC funcional, utilizando una arquitectura modular basada en las recomendaciones de Zane Ryan
    - Incorporar herramientas específicas para la recolección, análisis y visualización de datos de seguridad, basándose en la metodología explicada por Maurice Frayssinet

3. **Práctica en Detección y Respuesta**
    - Configurar sistemas para identificar y gestionar alertas generadas por actividades sospechosas
    - Desarrollar habilidades en el análisis de registros, clasificación de incidentes y reacción ante amenazas de seguridad en tiempo real

4. **Documentación y Compartición**
    - Registrar el progreso diario, las decisiones técnicas y los resultados obtenidos para crear un recurso útil para otros interesados en la ciberseguridad
    - Publicar los resultados en un repositorio público como un proyecto demostrativo, demostrando habilidades y conocimiento técnico adquirido

5. **Automatización y Optimización**
    - Implementar soluciones de automatización en el SOC para mejorar la eficiencia en la detección y respuesta ante incidentes.
    - Evaluar y ajustar las herramientas utilizadas según los resultados y las necesidades del entorno.

6. **Preparación para Certificaciones**
    - Alinear la experiencia práctica obtenida con los requisitos teóricos y técnicos de certificaciones relevantes como la **BTL1**.


# **Planificación y ejecución del SOC casero**
### **Disponibilidad y horarios**
En este proyecto, se optará por un modelo 24x7 (24 horas al día, 7 días a la semana), que es lo más adecuado para simular un SOC doméstico funcional que pueda detectar, responder e investigar incidentes en tiempo real. Aunque en un entorno real puede ser costoso contar con un equipo dedicado a tiempo completo, la simulación de este modelo permite cubrir cualquier posible incidencia de seguridad a cualquier hora, lo que es fundamental para garantizar la seguridad en todo momento.

### **Formato**
Este proyecto utilizará un SOC independiente, en lugar de un SOC y NOC integrados. La razón detrás de esto es la intención de concentrarse exclusivamente en las tareas de monitoreo y respuesta ante incidentes de seguridad, sin la necesidad de gestionar la infraestructura de red y servicios. Un SOC independiente permitirá una mayor especialización en el área de ciberseguridad, con el enfoque principal en la protección de activos informáticos.

### **Organización**
En este caso, el proyecto planteará controlar todo en casa. Aunque un modelo de MSSP (Proveedor de Servicios de Seguridad Gestionados) podría ser una opción en entornos empresariales, este proyecto se centrará en la implementación de un SOC casero sin la externalización de servicios. Un MSSP se refiere a un proveedor externo que gestiona y supervisa la seguridad de una organización, ofreciendo servicios como monitoreo, análisis y respuesta ante incidentes. La razón para optar por el modelo "en casa" es aprender de primera mano los procesos involucrados en la gestión de un SOC, como la detección de amenazas, la respuesta a incidentes y la configuración de herramientas.

### **Prioridades y capacidades**
En este proyecto, la seguridad será la principal preocupación. Si bien el cumplimiento con normativas es importante, la prioridad principal será garantizar la protección de los activos informáticos frente a ataques y amenazas cibernéticas. En términos de capacidades, el monitoreo será la principal prioridad. Se configurarán herramientas para detectar intrusiones y anomalías en tiempo real, pero también se incluirán capacidades básicas de hacking ético, como pruebas de penetración y simulación de ataques para evaluar la robustez de la infraestructura de seguridad. Este enfoque integral permitirá cubrir tanto la protección como la evaluación de vulnerabilidades. En cuanto a la nube, el proyecto no priorizará un uso extensivo, ya que se centrará en un entorno local simulado, aunque se considerarán aspectos relacionados con el acceso remoto y las posibles integraciones con servicios en la nube.

### **Entorno**
El entorno será local, sin una infraestructura híbrida o basada exclusivamente en la nube. La razón principal para elegir este enfoque es crear un SOC doméstico funcional que simule un entorno tradicional, utilizando hardware y software locales. Esto permite controlar directamente todos los componentes del SOC, aprender a gestionar las herramientas y realizar ajustes en función de las necesidades del proyecto sin depender de servicios externos. Aunque un entorno híbrido podría ofrecer mayor flexibilidad, en este caso se busca un enfoque más sencillo y directo para la implementación de un SOC en casa.


# **Defensa en profundidad**
En proceso

# Herramientas empleadas
En proceso

___
# **Bibliografía**

Frayssinet, M. (2022). Implementación del Centro de operaciones de seguridad (SOC) "Implementación del Centro de operaciones de seguridad (SOC)". YouTube: https://www.youtube.com/watch?v=QyEGELTFkvU.

Frayssinet, M. (2022). Implementación del Centro de operaciones de seguridad (SOC) con Wazuh. YouTube: https://www.youtube.com/watch?v=frzsfkiEL6A&list=PLzumfvfzw5l9l8LB1mLQpTbH3BTdFaTuO&index=2

Ryan, Z. (2022). # CYBERCLOUDSUMMIT22](https://www.youtube.com/hashtag/cybercloudsummit22): ¿Montar un [#SOC](https://www.youtube.com/hashtag/soc) por componentes o implementar un todo en uno? @Dotforce. Youtube: https://www.youtube.com/watch?v=gM_Y_0zUdmA



Imagen extraída de: https://x.com/Fisher85M/status/1579782478285672449

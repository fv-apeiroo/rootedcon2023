# /Rooted:unlock:CON :two::zero::two::three:
> *Exponer y compartir conocimientos en materia de ciberseguridad entre los diferentes miembros de la comunidad*

No hay mejor frase para describir el propósito principal de esta conferencia de seguridad informática.

## :date: 9 Marzo

### CRIPTORED - KEYNOTE
:man: ***Ponente:*** Alfonso Muñoz Muñoz

:page_facing_up: ***Resumen:*** Se produce la apertura del track de Criptored (organismo colaborador) por parte del ponente. El mismo ya adelanta la brevedad de su discurso y, presenta la agenda de Rooted mencionando temas como la seguridad en la nube, APTs, inteligencia artificial...

Trata el tema del avance descontrolado de la tecnología y todo lo que esto conlleva: necesidad de personal más cualificado y, promover la creación de equipos multidisciplinares en lugar de abordar individualmente las diferentes ramas que influyen en el campo de la seguridad.

Bienvenida y gratitud hacia los asistentes para dar paso al resto de ponencias.

### Estado del arte en Seguridad Blockchain y Smartcontracts
:man: ***Ponente:*** Raúl Riesco Granadino

:page_facing_up: ***Resumen:*** Personalmente, creo que fue la charla que exigía mayor nivel técnico, tanto general (desarrollo, seguridad de la información...), como específico o dirigido a la temática tratada. Sin embargo, fue muy interesante y presentó información de actualidad y diferentes menciones a tecnologías novedosas que necesitarán de muchos profesionales para desarrollarse.

En primer lugar, el ponente expuso su historial profesional vinculado al mundo de la tecnología blockchain y los smartcontracts. Describió esta tecnología y cómo los smartcontracts se nutren de ella y, en forma de tablas comparativas, mostró las ventajas a nivel de seguridad que ofrece blockchain en este tipo de operaciones, frente a las análogas que se dan en la actualidad.

Inversores, organismos importantes del sector... están poniendo sus miradas y apostando cada vez más por estas tecnologías, dejando ver la cantidad de profesionales que serán y son necesarios.

Después de estos apartados informativos introductorios, el autor de la conferencia dio paso a enseñar de manera teórica/práctica diferentes formas de comprometer la tecnología en cuestión. Comentó que, a pesar de la robustez en cuanto a seguridad, blockchain puede terminar presentando fallos propiciados por la complejidad a la hora de incluir software sobre la misma (debido a la vinculación del desarrollo de este con el factor humano). A medida que avanzaba en la explicación de sus laboratorios de ejemplo, señalaba noticias sobre el robo desmesurado de fondos a compañías o instituciones, fruto "hackeos" que aprovechaban las vulnerabilidades que mostraba en las diapositivas.

#### :heavy_plus_sign: INFO EXTRA
El ponente mostró la vulnerabilidad que incluía una función a nivel de código en la cual, después de solicitar la realización de acciones sobre un Smartcontract (interactuar con el mismo), podían repetirse determinadas operaciones para beneficiarse económicamente. Después, mostró la misma función corregida, detallando que el problema recaía en la ausencia de un comprobante que asegurara que dicha operación ya había sido efectuada.

### Ukraine-Russia CyberWar: Telecom Hijack
:man: ***Ponente/s:*** David Marugán Rodríguez, José María Mezcua Cantero

:page_facing_up: ***Resumen:*** Aunque de nuevo la charla requería en ocasiones de un nivel técnico avanzado, resultó muy interesante y las amplias explicaciones de los ponentes unidas a los esquemas de red "dinámicos" (eran representaciones de esquemas de red similares a los hechos con Packet Tracer, donde mostraban con pequeñas animaciones el comportamiento de las comunicaciones), permitieron comprender bastante bien la mayoría de los conceptos expuestos.

El tema principal, se basaba en la "ciberguerra" acontecida entre los territorios rusos y ucranianos durante el período de invasión. Un elemento fundamental dentro de este escenario, es sin duda el secuestro de sesiones BGP y el papel que tienen los operadores de red en este entramado de engaños. Básicamente, cuando se habla de secuestro BGP o BGP Hijacking, se hace referencia al robo de redes a través de enmascararte como el verdadero origen y transmitiendo esta información a tus peers. Los ponentes nos expusieron de forma sútil que, si estos peers no comprueban la legitimidad del origen (o no quieren hacerlo por el motivo que sea :dollar::dollar::dollar:), pensarán que para ir hacia una red concreta deben pasar por dicho operador (FALSO) y, consecuentemente, expondrán datos a entidades desconocidas.

Como conclusión a parte de lo espuexto anteriormente, hicieron la recomendación de elegir operadores de red con buena reputación.

Se habló de la enorme reducción de infraestructuras y mecanismos de comunicación en el territorio ucraniano, buscando aislar y desproveer de internet a los ciudadanos. El papel de StarLink por parte de Elon Musk junto a otras obras de caridad, suavizaron esta situación.

La parte final de la ponencia estuvo enfocada en las acciones y aspectos a tener en cuenta para garantizar la securización de nuestra red. 
- El uso de WAFs que cuenten con la tecnología correcta. Los ponentes remarcaron este punto debido a que no todos estos sistemas de protección en tiempo real cuentan con la capacidad de verificar las rutas que reciben. SI ESTE ES EL CASO, DEBEMOS ENCARGARNOS NOSOTROS MISMOS DE REALIZAR ESTE FILTRADO, PROPONIENDO COMO SOLUCIÓN SENCILLA, RÁPIDA Y EFICAZ, IPTABLES.
- RPKI Servers

#### :heavy_plus_sign: INFO EXTRA
Se trataron numerosos protocolos como el RTR, destinado también a verificar rutas...

:arrow_forward: ***CHARLA LÍNEA DIRECTA***

### ¡Por mis profilings!
:man: ***Ponente/s:*** Santiago Anaya Godoy, Jorge Testa

:page_facing_up: ***Resumen:*** SIN DUDA, DE MIS CHARLAS FAVORITAS.

Todas las ponencias están relacionadas de algún modo con la ciberseguridad y el impacto que genera promoverla para asegurar la integridad de nuestros datos, productos... Sin embargo, esta fue la primera que relacioné directamente con el entorno laboral en el que nos movemos.

Resumiendo, se trató el concepto de "Profilings" que hace referencia a la generación de arquetipos basados en las características del "malo" o adversario digital. De esta manera se responde un poco a las preguntas que surgen cuando un equipo de seguridad debe enfrentarse a un incidente o garantizar directamente la seguridad de un cliente en el tiempo. 

La creación de plantillas sobre el ciberdelincuente, no supone únicamente identificar y poner remedio a la amenaza, sino aplicarlas sobre todas las herramientas que intervienen en el suceso o incidente:

![imagen](https://user-images.githubusercontent.com/109788768/224569188-aefd20c6-0ee7-465e-9e8f-c9f07ba1424f.png)

Los chicos de la ponencia mostraron en directo una herramienta que permitía automatizar la construcción de un perfil específico, de acuerdo a la naturaleza de diferentes aspectos que identificaban al delincuente y que iban siendo introducidos en un formulario.

### Deepfakes: un gran poder conlleva una gran responsabilidad
:woman: ***Ponente:*** Ángela Barriga Rodríguez

:page_facing_up: ***Resumen:*** CHARLA SÚPER INTERESANTE.



# Regiones
AWS tiene el concepto de una región, que es una ubicación física en todo el mundo donde agrupamos los centros de datos. Llamamos a cada grupo de centros de datos lógicos “zona de disponibilidad”. Cada región de AWS consta de varias zonas de disponibilidad aisladas y separadas físicamente dentro de un área geográfica. A diferencia de otros proveedores de nube, que a menudo definen una región como un solo centro de datos, el diseño múltiple de zonas de disponibilidad de cada región de AWS ofrece ventajas para los clientes. Cada zona de disponibilidad tiene alimentación, refrigeración y seguridad física independientes y está conectada a través de redes redundantes de latencia ultrabaja. Los clientes de AWS centrados en la alta disponibilidad pueden diseñar sus aplicaciones para que se ejecuten en múltiples zonas de disponibilidad y lograr una mayor tolerancia a errores. Las regiones de infraestructura de AWS cumplen con los niveles más altos de seguridad, cumplimiento y protección de datos.

AWS proporciona una presencia global más extensa que cualquier otro proveedor de nube, y, para respaldar su presencia global y garantizar que los clientes reciban servicios en todo el mundo, AWS abre nuevas regiones rápidamente. AWS mantiene múltiples regiones geográficas, incluidas las regiones de América del Norte, América del Sur, Europa, China, Asia Pacífico, Sudáfrica y Medio Oriente.

# Zonas de disponibilidad
Una zona de disponibilidad (AZ) es uno o más centros de datos discretos con alimentación, redes y conectividad redundantes en una región de AWS. Las zonas de disponibilidad permiten que los clientes operen bases de datos y aplicaciones de producción con un nivel de disponibilidad, tolerancia a errores y escalabilidad mayor que el que ofrecería un centro de datos único. Todas las zonas de disponibilidad en una región de AWS están interconectadas con redes de alto ancho de banda y baja latencia, a través de una fibra metropolitana exclusiva totalmente redundante que proporciona una red de alto rendimiento y baja latencia entre las zonas de disponibilidad. Todo el tráfico entre las AZ está cifrado. El rendimiento de la red es suficiente como para llevar a cabo la replicación sincrónica entre las zonas de disponibilidad. Las AZ facilitan la partición de las aplicaciones para una alta disponibilidad. Si una aplicación se divide en AZ, las empresas estarán mejor aisladas y protegidas de problemas como cortes de energía, rayos, tornados, terremotos, etc. Las AZ están físicamente separadas entre sí por una distancia significativa de muchos kilómetros, aunque todas están dentro de un rango de 100 km (60 millas) de separación.
AWS Local

# AWS Local Zones
Las zonas locales de AWS ubican el cómputo, el almacenamiento, la base de datos y otros servicios selectos de AWS más cerca de los usuarios finales. Con las zonas locales de AWS, puede ejecutar fácilmente aplicaciones sensibles que requieren latencias de milisegundos de un solo dígito para sus usuarios finales, como la creación de contenido multimedia y de entretenimiento, juegos en tiempo real, simulaciones de depósitos, automatización de diseño electrónico y aprendizaje automático.

Cada ubicación de AWS Local Zone es una extensión de una región de AWS en donde puede ejecutar sus aplicaciones sensibles a la latencia con servicios de AWS tales como Amazon Elastic Compute Cloud, Amazon Virtual Private Cloud, Amazon Elastic Block Store, Amazon File Storage y Amazon Elastic Load Balancing en las proximidades geográficas de sus usuarios finales. Las AWS Local Zones proporcionan una conexión segura con alto ancho de banda entre las cargas de trabajo locales y aquellas que ejecutan en la región de AWS, lo que permite una conexión continua con sus otras cargas de trabajo en ejecución en AWS y a la gama completa de servicios en la región a través de las mismas API y conjuntos de herramientas.

# AWS Wavelength
AWS Wavelength permite a los desarrolladores crear aplicaciones que ofrecen latencias de milisegundos de un solo dígito a dispositivos móviles y usuarios finales. Los desarrolladores de AWS pueden implementar sus aplicaciones en Wavelength Zones, implementaciones de infraestructura de AWS que integran servicios de cómputo y almacenamiento de AWS dentro de los centros de datos de los proveedores de telecomunicaciones en el borde de las redes 5G, y acceder sin problemas a la gran variedad de servicios de AWS en la región. Esto permite a los desarrolladores entregar aplicaciones que requieren latencias de milisegundos de un solo dígito, como el streaming de juegos y de video en directo, inferencia de aprendizaje automático en el borde, y realidad aumentada y virtual (RA/RV). AWS Wavelength lleva los servicios de AWS al borde de la red 5G, lo que minimiza la latencia para conectarse a una aplicación desde un dispositivo móvil. El tráfico de aplicaciones puede llegar a los servidores de aplicaciones que se ejecutan en Wavelength Zones, sin salir de la red del proveedor de telefonía móvil. Esto reduce los saltos adicionales de la red a Internet que pueden producir latencias de más de 100 milisegundos, lo que impide a los clientes aprovechar al máximo el ancho de banda y los avances de latencia de 5G.

# AWS Outposts
AWS Outposts brinda servicios, infraestructura y modelos operativos nativos de AWS a prácticamente cualquier centro de datos, espacio de coubicación o instalación local. Puede usar las mismas API, herramientas e infraestructura de AWS en las instalaciones y en la nube de AWS para ofrecer una experiencia híbrida verdaderamente consistente. AWS Outposts está diseñado para entornos conectados y puede utilizarse para soportar cargas de trabajo que deben permanecer en las instalaciones debido a la baja latencia o las necesidades locales de procesamiento de datos.

# Servicios
AWS ofrece un amplio abanico de productos globales basados en la nube, incluidas aplicaciones de informática, almacenamiento, base de datos, análisis, red, aprendizaje automático e IA, dispositivos móviles, herramientas para desarrolladores, IoT, seguridad, empresariales y muchas más. Nuestra política general consiste en ofrecer servicios, funciones y tipos de instancias de AWS en todas las regiones de AWS en un plazo de 12 meses desde que se anuncia la disponibilidad general según distintos factores como la demanda del cliente, la latencia, la soberanía de los datos y otros factores. Los clientes pueden ponerse en contacto con el representante de ventas de AWS para compartir su interés acerca de la entrega en regiones locales, solicitar información sobre la hoja de ruta del servicio u obtener datos sobre la interdependencia del servicio (conforme al acuerdo de confidencialidad). Debido a las características del servicio, algunos servicios de AWS se entregan de manera global en lugar de en cada región, como sucede con Amazon Route 53, Amazon Chime, Amazon WorkDocs, Amazon WorkMail, Amazon WorkSpaces y Amazon WorkLink.

# Alta disponibilidad
A diferencia de otros proveedores de infraestructura tecnológica, cada región de AWS tiene múltiples AZ. Como bien hemos observado al ejecutar la plataforma tecnológica líder de la infraestructura en la nube desde 2006, los clientes interesados en la disponibilidad y el rendimiento de las aplicaciones desean implementarlas en varias zonas de disponibilidad de la misma región a efectos de tolerancia a fallos y baja latencia. Las zonas de disponibilidad están conectadas entre sí con redes de fibra óptica rápidas y privadas, lo que permite diseñar aplicaciones con facilidad que conmuten por error entre las zonas de disponibilidad sin interrupciones.

El plano de control de AWS (incluidas las API) y la consola de administración de AWS están distribuidos en las regiones de AWS y utilizan una arquitectura multi-AZ dentro de cada región para ofrecer resiliencia y una disponibilidad continua. De este modo, se garantiza que los clientes no dependan exclusivamente de un único centro de datos. AWS puede realizar tareas de mantenimiento sin que ningún servicio crítico quede fuera de servicio temporalmente para ningún cliente.

# Mejora de la continuidad
Además de replicar aplicaciones y datos en varios centros de datos de la misma región de las zonas de disponibilidad, puede optar también por aumentar la redundancia y la tolerancia a fallos mediante la replicación de los datos entre regiones de AWS. Para ello, puede usar las redes privadas de alta velocidad y las conexiones públicas de Internet a fin de ofrecer una capa adicional de continuidad empresarial, o bien ofrecer acceso de baja latencia en todo el mundo.

# Cumplimiento y residencia de datos
Si tiene requisitos de residencia de datos, puede elegir la región de AWS que esté más cerca de su ubicación deseada. Retiene el control y la propiedad plenos sobre la región en que los datos se encuentran físicamente, lo que facilita el cumplimiento de los requisitos regionales de conformidad y residencia de datos. Puede estar tranquilo al saber que AWS no solo cumple con el Reglamento General de Protección de Datos (GDPR), sino que también cuenta con servicios y herramientas para permitir construir una infraestructura que cumpla con el GDPR sobre AWS. Las organizaciones, desde las empresas emergentes hasta las compañías y el sector público, tienen acceso a la infraestructura en su país para aprovechar tecnologías avanzadas que incluyen el análisis, la inteligencia artificial, las base de datos, el Internet de las cosas (IoT), el aprendizaje automático, los servicios móviles, la tecnología sin servidor y más para impulsar la innovación.
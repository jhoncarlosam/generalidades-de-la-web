# Generalidades de la web
## Resumen para la materia Programación Web UFPS - Tendencias en el Desarrollo de Software moderno

Comenzamos con la comparación en la evolución de los **lenguajes de programación** más usados, aquí podemos ver una tendencia al crecimiento de nuevas tecnologías como lo son *Python, Swift, Scala, Go, Kotlin*. Sin embargo, las tecnologías más maduras continuan manteniendose a la cabeza como lo son *JavaScript, Java, C, C#, C++, PHP*.
(se hace una estimación sobre una mayor demanda en el uso del lenguaje que a día de hoy es cierta con lenguajes como *Python, Go, Kotlin, Scala*).

El **desarrollo de software** se divide en **Frontend** y **Backend**, siendo **Frontend** la parte que el usuario ve y con la cual interactua, mientras que Backend viene siendo el conjunto de componentes que el usuario no ve, pero que se encarga de facilitar y asegurar los servicios que el usuario consume de la página. Por razónes de compatibilidad y menor riesgo de bugs entre **Frontend** y **Backend** los desarrolladores han adoptado el modo de operación **FullStack** que no es más que la ejecución de ambas ramas del desarrollo en una sola persona, lo cual hace al desarrollador muy apetecido por las empresas.

Las tecnologías más usadas en el desarrollo **Frontend** son: *HTML/CSS, JavaScript, Boostrapt, Web Design & UI, Mobile App(IOS, Android), SAAS(AngularJS), API REST.*
Las tecnologías más usadas en el desarrollo **Backend** son: *PHP, MySQL, NoSQL, Python, Node.js, JavaEE, Linux, Ruby, .NET.*
Todas estas nos ayudan desarrollar diferentes tipos de proyectos.

### Evolución del desarrollo de software
Se mide según la complejidad de las aplicaciones y su auge es más notorio en diferentes eras:
- **Dark ages**: Lenguajes como Cobol.
- **1984**: Nace el computador personal y con ello las primeras aplicaciones de escritorio.
A día de hoy se siguen usando en negocios de tipo contable. Son tambien llamadas aplicaciones Legacy o aplicaciones heredadas.
- **2001**: Sitios web transaccionales para diferentes empresas de comercio, transporte, bancos, entre otros. Data centers.
- **2008**: Uso de tecnologías AJAX, RIAs(Rich Internet Aplications) ejemplo: Google Drive, Google Docs. SaaS enterprise apps.
- **2015**: Aplicaciones en la Nube(Cloud)

### Cambios relevantes a través de los años
- Ciclos de desarrollo más cortos, gracias a tecnologías como los frameworks.
- Evolución en equipos de trabajo.
- Microservicios.
- Mejora en las interfaces gracias al UX/UI.
- Desarollo con API's.

Lo que usan las web modernas son lenguajes de maquetado y estilo como *HTML5/CSS3*(posiblemente haya un estandar *HTML6*). **Servicios Rest** en formato *JSON* o uso de *GraphQL*. Tendencia a aplicar **arquitecturas con microservicios y Serverless**. Se emplean servicios de redes sociales para la parte de *loggin*. **Cloud Driven**, lo que nos permite su uso descentralizado en todo momento. Luego esta el uso de **Responsive Design** que beneficia el uso de dispositivos *mobile*. Uso de **OAuth**, para autenticación. Las **single page aplication(SPA)** o aplicaciones web de una sola página. **Persistencia políglota**, más vista en microservicios.

Con respecto a la **arquitectura web** se uso mucho el formato **vista/controlador** en el *navegador*, el modelo se usaba aparte en el server.
El **apartado de mobile** llegó gracias a la rápida evolución de tecnologías como *JavaScript, NodeJs* las cuales aportaron de manera importante.

### Formatos de desarrollo de software: 
**Desarrollo de aplicaciones modernas**: scrum, kanban.

**Patrones de desarrollo de apps modernas**: aplicaciones políglotas ligeras, mobile/chatbot, Mircroservicios/serverless, visual/low code.

**Infraestructura para el desarrollo de apps modernas**: Automatizar DevOps, API Management, Monitoreo, Contenedores/Orqustación para portabilidad/ Elasticidad(*Tenemos kubernetes, Docker*), Plataforma Cloud(*Alto desempeño, Alta disponibilidad, IaaS seguro(Procesamiento, bases de datos, VM, VPN, Firewall, Bloques*)).

> ### Si se orienta a Cloud se tendrá un sistemas más robusto.

### Aspectos importantes a tomar de la Arquitectura
- Seleccione la vista aquitectonica.
- Seleccione el Estilo Arquitectonico.
- Seleccione estre una solución Cloud o servidores on-premise.
- Considere Autenticación/Autorización y privacidad.
- Defina reglas de seguridad y protocolo de comunicación(es importante considerar otros protocolos).
- Defina si se necesita balanceo de carga(Nginx), messaging(Kafka, RabbitMQ, JMS, ActiveMQ), etc.
- Hacer una revisión general de cualquier algoritmo crítico que controle el servicio.
- Considerar cuellos de botella y determine soluciones.
- Seleccione Tipos de almacenamiento(SQL o NoSQL)
- Comprender qué datos deben almacenarce en caché y cómo mejorar el rendimiento, la seguridad y la disponibilidad con el almacenamiento en caché(Elasticsearch/Apache Solr).
- Seleccione un sistema de monitoreo(Prometheus/Grafana) y logging(Logstash/Fluentd). Como Gestionar Excepciones y fallos(Netflix Turbine/Hystrix).
- Defina la separación entre áreas públicas y restringidas.

### Otros temas importantes
**WebAPIs**(se recomienda usar Apiary), **SPA**(se recomienda usar Frameworks y librerías: React, Angular, ember, Ajax, NodeJS, jQuery), **Arquitectura de Servidores Ligeros**(User ***Interface/Browser* **(*DOM API, HTML5, CSS, JavaScript/TypeScript*)los cuales hacen conexión a través de *HTTP, XMLHttpRequest, WebSocket*. ** *App Server* **(*Static Recourse Service, RESTful Data Service, WebSocket Server Push, Data Access*)) nos permite una mejor escalabilidad y experiencia de usuario, **PWA**(Aplicaciones web progresivas), **Microservicios**(se recomienda desarrollar con la siguiente ruta: ***DevOps, Microservices & API's, Containers, Scalable Cloud Infrastructure* **) consumidores de microservicios: Netflix, Twitter, Uber, Facebook, Paypal, Amazon, Soundcloud.

### Plataformas y Frameworks para Microservicios
#### Java
- Spring boot
- Dropwizard
- Openshift
- Restexpress
- Spring Cloud
- Netflix OSS
- Qbit
- Jersey
- Play
#### .NET Core
- NancyFx
- WebAPI
- SteelToe
#### Go
- Go-kit/kit
- Mircro/go-micro
- Serverless: Sparta, Apex, Gordon
#### NodeJS
- Express
- SenecaJS
- FeatherJS
- Serverless: ClaudiaJS

**Serverless** es un paradigma de programación en la nube extiende de los *microservicios*, nos permite ejecutar respuestas a eventos, no se ejecuta a menos que sea necesario, lo cual nos beneficia porque se paga por llamada y no por servicio completo. Es ofrecido por *AWS Lambda*.
### Tendencias
**Containerización, blockchain, AI-First Software Development, DevOps First, Multiplataform UI Development(Flutter,  React Native, Xamarin).**

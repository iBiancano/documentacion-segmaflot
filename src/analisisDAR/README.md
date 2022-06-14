# Analisis DAR

# Introducción

Con el avance tecnológico el desarrollo de software día con día integra nuevas opciones para realizarlo, estas opciones traen consigo mejoras que facilitan el uso del lenguaje optimizando tiempo y esfuerzo.

En el presente documento utilizaremos el análisis DAR el cual pertenece al modelo CMMI y tiene como propósito analizar las posibles opciones utilizando un proceso de evaluación formal que evalúa alternativas identificadas contra los criterios establecidos.

El objetivo evaluar las diferentes opciones tanto para la gestión de base de datos, frameworks de FRONTEND al igual que de BACKEND definiendo qué herramientas son las más óptimas para el desarrollo del proyecto SEGMAFLOT.



# Front-End

## La importancia del frontend

La importancia de esta parte es vital porque se trata de la encargada de interactuar con tus usuarios.

Que tengas un buen frontend es fundamental para que tus usuarios lleguen a tu página, tengan una buena experiencia y, como consecuencia, de esto se queden y vuelvan en el futuro.

Se trata de la conexión perfecta. Se coge la información de las bases de datos del backend y se pasan al interfaz del sitio que en realidad se trata del propio perfil del usuario. Un buen frontend también es importante porque ayuda a posicionar de manera orgánica tu negocio.

Si Google detecta que los usuarios pasan tiempo en tu web y que carga rápido, entonces comenzarán a colocarlo entre los primeros puestos de los resultados.

Otro aspecto a valorar es la funcionalidad en los dispositivos móviles.

En la actualidad, casi todo el mundo tiene un smartphone por el que navega en Internet y visita sitios webs como el tuyo.

Un buen frontend es aquel que configura también el diseño visible para estos dispositivos con el fin de que sea accesible tanto desde un ordenador como desde un móvil.

## Características de los frameworks para el desarrollo frontend

* Modularidad
* Reactividad
* Componentes web
* Virtual DOM
* Curva de aprendizaje
* Facilidad de implementación
* Funcionalidades intuitivas, modernas y fáciles de utilizar.
* Posee una extensión para Chrome que permite ver la jerarquía de componentes, registro de eventos y estado global de la aplicación.
* Comunidad activa y amplia documentación.
* Solución ligera.
* Usabilidad y accesibilidad;
* Posicionamiento en buscadores o SEO;
* Rendimiento web y compatibilidad del navegador.

## Análisis de decisiones y resolución (DAR)

### Establecer las guías para el análisis de decisiones

*  Si se trata de un framework conocido es posible que encontrar información, módulos y herramientas sea sencillo y agilice el proceso de desarrollo.

*  Aporta seguridad gracias a los métodos de verificación.

*  Los frameworks cuentan con comunidades de desarrolladores que pueden ayudar a despejar dudas acerca del software.

*  El proceso de desarrollo es mucho más fluido y fácil para el desarrollador, esto se debe a que el framework representa un esqueleto o patrón de trabajo que determinará la evolución de la aplicación.

### Establecer los criterios de evaluación

Los criterios de evaluación se basan en algunas características y ventajas que poseen algunos frameworks, dentro del desarrollo de la búsqueda se encontraron diferentes criterios importantes para la selección, a continuación, se presentan los puntos más importantes:

1. Instalación
2. Curva de aprendizaje
3. Documentación
4. Disponibilidad de recursos de aprendizaje
5. Patrones de diseño
6. ORM
7. Versatilidad
8. Accesibilidad
9. Popularidad
10. Usabilidad
11. Escalabilidad
12. Soporte de navegadores
13. Facilidad de integración (con otras bibliotecas)
14. Comunidad
15. Actualizaciones
16. Extensiones

En la tabla se presentan las características a evaluar anteriormente mencionadas, estableciendo la ponderación del valor a tomar, siendo en una escala de 1 a 5, donde cinco es la ponderación máxima y 1 la mínima.

<img :src="$withBase('/img/caracteristicas.png')">

Realizando una búsqueda sobre la problemática presentada, se deben identificar los frameworks más utilizados por parte del frontend.

<img  :src="$withBase('/img/estadisticas.png')">

En el siguiente link se muestra el ranking de los diferentes índices de satisfacción, interés, uso y conocimiento de dichos frameworks.

https://2020.stateofjs.com/en-US/technologies/front-end-frameworks/

### REACT JS

#### Características

* Las variantes
* Programación reactiva
* Se basa en componentes
* Tiene una gran comunidad
* Evolución y actualización
* Código estable y seguro
* Flexibilidad en la web y móvil
* Enlace de datos unidireccional
* DOM virtual
* Rendimiento y velocidad mejorados
* Facilidad para expandirse y aprender
* Altamente compatible con vastas bibliotecas
* JSX: JavaScript Syntax Extension
* La depuración es más rápida y sencilla

#### Ventajas

Como principal ventaja podemos señalar que resulta más sencillo de comprender respecto a Angular, ya que su sintaxis es más simple. Los desarrolladores no necesitarán aprender TypeScript en profundidad.

Cuenta con un DOM virtual que permite organizar documentos en diferentes formatos y, al ser una biblioteca de código abierto, recibe actualizaciones y mejoras a diario por parte de desarrolladores de todo el mundo.

* React utiliza DOM virtual que mejora la experiencia del usuario.
* Hace que el trabajo del desarrollador sea menos complejo.
* JSX se usa en ReactJS, que es muy simple y fácil de aprender.
* Es una biblioteca de código abierto en constante desarrollo.
* Proporciona una solución móvil que se conoce como React Native.
* React es más rápido para renderizar en comparación con otros marcos web.
* Tiene un gran kit de herramientas para desarrolladores.
* La curva de aprendizaje comparativamente larga.

#### Desventajas

El inconveniente fundamental lo encontramos en la gran documentación que existe, y la inexistencia hasta la fecha de una fuente oficial que ofrezca un discurso unificado. Ante esta situación, los desarrolladores pueden perderse en un mar de opiniones.

* Necesita bibliotecas adicionales para enrutamiento, administración de estado e interacción API.
* ReactJS es una biblioteca de gran tamaño.
* El ritmo de desarrollo es muy alto.
* ReactJS solo cubre la parte de la interfaz de usuario, nada más.
* Debido a un ritmo de desarrollo muy alto, la documentación de ReactJS está mal mantenida.
* La curva de aprendizaje comparativamente larga

### VUE JS

#### Características

* Accesible.
* Fácil de aprender.
* Versátil
* Escalable por el mismo tema de la versatilidad.
* Reactivo.
* Comunidad.
* Licencia MIT.
* DOM virtual.
* Transiciones y animaciones CSS integradas.
* Enlace de datos mediante v-bind.
* Plantillas basadas en HTML.
* Tamaño pequeño (mayor compatibilidad).
* Sintaxis e integración sencillas.
* Ofrece documentación organizada.
* Vue-router (realiza la navegación entre páginas).

#### Ventajas

Teniendo conocimientos de JavaScript y HTML, el desarrollador o desarrolladora que utilice Vue.js tendrá una curva de aprendizaje reducida ya que Vue.js incluye documentación adaptada que permite ahorrar tiempo al equipo.

Además, presenta similitudes con los anteriores frameworks en cuanto a arquitectura y diseño. Pesa poco, pero mantiene su velocidad y flexibilidad.

* Tamaño pequeño.
* Componente de un solo archivo y legibilidad.
* Sistema de herramientas sólidas.
* Documentación extensa y detallada.
* Simplicidad y claridad
* Extensiones de herramientas de desarrollo del navegador
* Reutilización de código e integración simple
* Ofrece mayor flexibilidad y menos restricciones
* Gran escalado.

#### Desventajas

En comparación con Angular y ReactJS, Vue.js todavía cuenta con una cuota de mercado bastante reducida, especialmente si lo comparamos con ReactJS, lo que se traduce en escasa documentación disponible ante la resolución de problemas que podamos tener al integrarlo en nuestros proyectos. Pero, debemos tener en cuenta que este framework cada vez cuenta con más adeptos, por lo que ya se están generando nuevos materiales.

* Complejidad de la reactividad.
* Barrera lingüística.
* Riesgos de exceso de flexibilidad.
* Comunidad de desarrolladores reducida.
* La flexibilidad conduce a irregularidades en el código.

### SVELTE

#### Características

* Sencillo desde la perspectiva del programador
* Compilación rápida de componentes
* Consola ágil
* Sintaxis simple
* CSS por componentes o en modo global
* Componentes reactivos
* Hot reloading
* HTML, CSS y Javascript en un mismo fichero
* Sapper disponible
* Sin virtual DOM
* Sin Typescript
* Ayuda con markup inaccesible
* Comunidad pequeña

#### Ventajas
Entre sus características principales, destacan:
* Es un compilador
* No utiliza Virtual DOM
* Reactividad
* Encapsula el CSS en los componentes
* Marco escalable
* Es liviano, simple y utiliza las bibliotecas de JavaScript predominantes.
* El más nuevo de todos
* Más rápido que cualquier otro marco, a saber, React o Angular
* Encapsula el CSS en los componentes

#### Desventajas
* Hay muchos códigos duplicados en algunos casos
* Queda por ver el rendimiento en grandes aplicaciones
* Capacidad abstracta débil
* Falta de apoyo
* Todavía no es muy popular
* Comunidad menor
* Falta de herramientas

### JQUERY

#### Características

* Selección de elementos DOM.
* Interactividad y modificaciones del árbol DOM, incluyendo soporte para CSS 1-3.
* Eventos.
* Manipulación de la hoja de estilos CSS.
* Efectos y animaciones.
* Animaciones personalizadas.
* AJAX.
* Soporta extensiones.
* Utilidades varias como obtener información del navegador, operar con objetos y vectores, funciones para rutinas comunes, etc.
* Compatible con los navegadores
* Se usa ampliamente debido a su facilidad de uso y simplicidad.
* Intuitivo y fácil de aprender, ya que la biblioteca está construida con códigos más cortos y simples.
* Compatibilidad entre navegadores
* Una sintaxis limpia, potente y sencilla facilita la elección de los elementos DOM
* La biblioteca jQuery es liviana y esbelta
* Biblioteca de código abierto
* Efectos y animaciones geniales
* Altamente extensible y las páginas se cargan más rápido
* jQuery es compatible con SEO y facilita el contenido dinámico

#### Ventajas

* Incluye, listos para usar, elementos como botones, barras de herramientas, formularios, listas y tipografías especialmente optimizadas y estilizadas para aplicaciones móviles. Además, cuenta con un sistema de bloques ideal para construir plantillas.
* Nos permite construir aplicaciones aptas para todo tipo de plataformas casi sin esfuerzo, evitándose preocupaciones por problemas de compatibilidad.
* Es muy fácil de aprender y utilizar.
* Tiene soporte para Ajax.
* No requiere del uso de programas especiales.
* Permite hacer operaciones del DOM con pocas líneas de código.
* Tiene una gran cantidad de plugins para descargar.
* Es fácil de aprender y utilizar.
* Tiene soporte para AJAX, lo que permite enviar peticiones al servidor y, en base a la respuesta, modificar una parte de la web sin tener la necesidad de recargar toda la página.
* La transmisión de solicitudes HTTP está optimizada
* Document Object Model (DOM) es flexible para acumular o eliminar los componentes
* Las solicitudes HTTP se simplifican
* Simplifica el contenido dinámico

#### Desventajas
* Las funciones que ofrece son muchas, pero resultan difíciles de personalizar. Su aspecto visual es estandarizado y no se integra con el de la plataforma. En algunos casos, no queda otra opción que usar JavaScript simple para adaptar la aplicación a nuestras necesidades.
* Como es necesario invocar a un archivo para utilizar sus funciones, ralentiza levemente la carga de la página.
* Su manejo de CSS suele resultar innecesariamente complejo. A veces cuesta saber qué clases utilizar.
* No existen muchas plantillas prediseñadas sobre las cuales empezar a construir nuestra aplicación.
* Ofrece muchas funcionalidades que probablemente no se necesiten.
* Ralentiza la carga de nuestra app debido a tu peso de 93Kb.
* Gestionar estilos de CSS con jQuery es bastante complicado.
* Numerosos sustitutos progresivos están disponibles además de jQuery
* Las API del modelo de objetos de documento (DOM) están desactualizadas
* Capacidad de trabajo razonablemente lenta


#### Tabla comparativa

<img :src="$withBase('/img/comparativa.png')">


### Seleccionar los métodos de evaluación

A partir de la tabla 1, se crea una tabla en donde se indica la presencia o ausencia de las características descritas, determinando los niveles de importancia, así:

<img :src="$withBase('/img/metodos.png')">

### Evaluar las soluciones alternativas

En la tabla 4 se evalúan las soluciones, para realizar esta evaluación, se usó un método matemático, el cual determina cuantitativamente cuál framework es el más indicado según la descripción y calificación de sus características, esta evaluación se realizó mediante la siguiente fórmula:

<img :src="$withBase('/img/formula.png')">

El peso es la ponderación que se asignó a las características evaluadas, y el valor 1 o 0 si posee o no la característica descrita en la tabla número 3.

<img :src="$withBase('/img/puntaje.png')">

Como se puede observar en la tabla anterior, los frameworks React y Vue fueron los que obtuvieron mayor valoración, la decisión será tomada según los siguientes criterios:

* Todos los frameworks poseen de una fácil instalación.
* Poseen de una curva de aprendizaje, pero en ocasiones React lleva un poco más de tiempo en conocer todas las funcionalidades.
* Los 4 tienen una buena documentación, en el caso de Svelte, al ser un framework más nuevo, carece de documentación en la página oficial.
* Una vez más, Svelte no posee tantas herramientas de aprendizaje para su desarrollo o práctica.
* Todos los frameworks poseen patrones de diseño.
* Vue y React poseen la facilidad de manejar ORM gracias a las bibliotecas que manejan.
* Los 4 tienen una buena versatilidad, accesibilidad, popularidad y usabilidad.
* Vue y React tienen mayor escalabilidad para sus proyectos.
* Todos tienen un buen soporte para navegadores.
* Todos tienen una facilidad de integración con otras bibliotecas.
* Todos, a excepción de Svelte, poseen una gran comunidad de desarrolladores.
* Los 4 están en constante actualización.
* Vue y React son los frameworks que tienen mayor cantidad de extensiones.

Las siguientes gráficas muestran la clasificación de la satisfacción, el interés, el uso y la conciencia de los frameworks más populares en los últimos años.

<img :src="$withBase('/img/graf1.png')">

Como podemos observar, Svelte, encabeza el framework de mayor satisfacción del año 2020.

<img :src="$withBase('/img/graf2.png')">

En la tabla anterior, se observa que Svelte, nuevamente encabeza el primer lugar de interés por parte de los desarrolladores, seguido de Vue y React.

<img :src="$withBase('/img/graf3.png')">

En la tabla se muestra el uso de los frameworks con mayor uso.

<img :src="$withBase('/img/graf4.png')">

En esta tabla se muestra, el nivel de conciencia.
Opiniones sobre las tecnologías encuestadas, en el tiempo.

<img :src="$withBase('/img/graf5.png')">

Este gráfico se divide en experiencias positivas ("quiero aprender", "volvería a usar") vs. negativas ("no me interesa", "no volvería a usar") en ambos lados de un eje central.

El grosor de la barra representa el número de encuestados que conocen una tecnología.

<img :src="$withBase('/img/graf6.png')">

Medición de la popularidad del marco.

<img :src="$withBase('/img/graf7.png')">

<img :src="$withBase('/img/graf8.png')">

Lo que hace especial a Vue con respecto a otros frameworks, es que la comunidad de desarrollo ha sabido estudiar características muy importantes de otros frameworks, e implementarlas, por otro lado, ha realizado una labor de depuración, reduciendo el código innecesario.

Esto supone que, por un lado, el tamaño de la aplicación se reduzca y por otro lado, disminuye la dificultad de aprendizaje, permitiendo al desarrollador tomar el control de la aplicación, permitiendo el desarrollo ad hoc de nuevas funciones.

En esta tabla vemos el tamaño de cada framework frontend, donde se aprecia el tamaño de cada una de las aplicaciones:

<img :src="$withBase('/img/tabla.png')">

En cuanto a la curva de aprendizaje React es más fácil de aprender, pero su sintaxis puede resultar compleja para ciertas personas con conocimientos básicos o medios. Si quieres ampliar la información.

Vue, es más sencillo de aprender, su sintaxis no resulta compleja y tiene una curva de aprendizaje muy asequible, por lo que para adentrarnos en el mundo del desarrollo frontend, es uno de los recomendados por multitud de expertos.

### Seleccionar las soluciones

El resultado de selección se basará en la tabla de puntuación obtenida por el modelo matemático, la evaluación de la alternativa, y la información proporcionada por las encuestas y tablas de ranking que se observaron.

Dando así que el framework con mejores aspectos de aprendizaje y desarrollo es vue ya que posee una alta experiencia de desarrollo.

Las funcionalidades de Vue abarcan casi todas las expectativas de los profesionales y aplicaciones web. Además, ofrece cierta libertad a la hora de organizar el código de los proyectos y mantener las cosas simples.

Su curva de aprendizaje es muy corta por lo que no requiere grandes esfuerzos para aprender e invertir demasiado tiempo en el mismo.

Posee mucha flexibilidad, y un buen rendimiento de las aplicaciones, inclusive mayor que otras alternativas de frameworks populares. A todo esto, debemos añadir que Vue presenta una entusiasta comunidad de desarrolladores y una excelente documentación.

## Referencias

* Eseme, S. (2021, 12 agosto). 10 cosas que debes saber sobre Vue.js Frontend Framework. Kinsta. Recuperado 28 de marzo de 2022, de https://kinsta.com/es/blog/vue-js/#ventajas-y-desventajas-de-vuejs

* ROOTSTACK. (2021, 26 julio). VueJS: Ventajas y desventajas de este framework. Recuperado 29 de marzo de 2022, de https://www.rootstack.com/es/blog/vuejs-ventajas-desventajas/

* Rosa Moncayo, J. M. (2017, 26 septiembre). ¿Qué es Vue.js? OpenWebinars. Recuperado 29 de marzo de 2022, de https://openwebinars.net/blog/que-es-vuejs/

* Introducción a Vue JS ≫ Qué es y sus características. (2019, 3 noviembre). Coding Potions - Blog de programación y desarrollo web. https://codingpotions.com/que-es-vue

* VueJS. (2015, 12 abril). Vue.js - The Progressive JavaScript Framework | Vue.js. Vue.Js. Recuperado 28 de abril de 2022, de https://vuejs.org/
React. (2022, 12 febrero). Empezando –. Recuperado 29 de marzo de 2022, de https://es.reactjs.org/docs/getting-started.html

* Introducción a Vue JS ≫ Qué es y sus características. (2019, 3 noviembre). Coding Potions - Blog de programación y desarrollo web. https://codingpotions.com/que-es-vue

* Affdu. (2019, 22 agosto). Características de React JS: principales ventajas y desventajas. Recuperado 28 de marzo de 2022, de https://www.affdu.com/es/react-js-features.html

* AFFDE. (2021, 17 agosto). React.js Vs React Native: diferencias, ventajas y desventajas de ambas plataformas. Recuperado 28 de marzo de 2022, de https://www.affde.com/es/reactjs-vs-react-native.html

* Svelte. (s. f.). Svelte docs. Recuperado 31 de marzo de 2022, de https://svelte.dev/docs

* S. (2019, 12 noviembre). Svelte js: 13 características del framework del momento. Suma TD. https://sumatd.com/blog/svelte-caracteristicas/

* Bluuweb. (s. f.). Fundamentos | Svelte (bluuweb - youtube). Svelte (Guía bluuweb). Recuperado 31 de marzo de 2022, de https://bluuweb.github.io/svelte-youtube/01-bases/

* Svelte-más que rápido - programador clic. (2020, 23 mayo). Programador clic. Recuperado 31 de marzo de 2022, de https://programmerclick.com/article/3370912932/

# Back-End

## Características de frameworks para BACKEND

* Los controladores: Se adaptan muy bien a las exigencias del proyecto que administran los eventos.
* Internacionalización: Esto se debe a que permiten la integración de diferentes lenguajes en un proyecto de desarrollo de una aplicación.
* Autenticación: Se accede al framework mediante la autenticación de usuario y contraseña. Esto ayuda a limitar la entrada y los tipos de permiso.
* Fácil acceso a datos: en archivos de como txt, xml por ejemplo mediante interfaces que integran las bases de datos.
* Abstracción de urls y sesiones: El framework se encarga de controlar y gestionar las urls y sesiones.

## Analisis DAR

### Establecer las guías para el análisis de decisiones

* Permiten construir aplicaciones de manera fácil y rápida, así como una fácil integración de las dependencias y puesta en producción.
* Es un framework popular, su comunidad es amplia y con una documentación extensa, capaz de cubrir las necesidades del proyecto
* Garantiza seguridad y escalabilidad.
* Cuenta con una gran compatibilidad con otras tecnologías.
* Es un framework que se actualiza constantemente, con un buen soporte y es de software libre.

### Establecer las guías para el análisis de decisiones

Los criterios de evaluación se basan en características esenciales de las tecnologías para el backend, las cuales se presentan en el siguiente listado:

1. Velocidad
2. Gratuito
3. Escalabilidad
4. Curva de aprendizaje alta
5. Multiplataforma
6. Integración sencilla de las dependencias
7. Seguridad
8. Resistente
9. Simplicidad
10. Facilidad de instalar y configurar
11. Amplia comunidad y documentación
12. Compatibilidad

En la siguiente tabla se asignan pesos y ponderaciones en un rango de 1 al 5.

<img :src="$withBase('/img/tablab.png')">

### Identificar las soluciones alternativas

Basados en una evaluación e investigación, de acuerdo a sus características  se llegó a la conclusión de que los siguientes frameworks son los más apropiados para el desarrollo del sistema:

#### Spring boot
Spring boot es una tecnología que permite crear aplicaciones autocontenidas, con esto nos podemos olvidar de la arquitectura y enfocarnos únicamente en desarrollo, delegando a Spring Boot labores como configuración de dependencias, desplegar nuestro servicio o aplicación a un servidor de aplicaciones y enfocarnos únicamente en crear nuestro código.

#### JHipster 
 JHipster es una plataforma de desarrollo para generar, desarrollar e implementar rápidamente aplicaciones web modernas y arquitecturas de microservicios. Admite muchas tecnologías frontend, incluidas Angular, React y Vue. Incluso soporte para aplicaciones móviles para Ionic y React Native en el backend, admite Spring Boot (con Java o Kotlin), Micronaut, Quarkus, Node.js y .NET. Para la implementación, opta por los principios nativos de la nube con Docker y Kubernetes. Existe soporte de implementación para AWS, Azure, Cloud Foundry, Google Cloud Platform, Heroku y OpenShift.

#### VertX 
VertX es un framework para el desarrollo de aplicaciones reactivas que se ejecutan en la máquina virtual de Java, enfocadas a la programación asíncrona,  que permiten escalabilidad y la eficiencia de recursos

#### Node js/ Express
Node js/ Express es un entorno que trabaja en tiempo de ejecución, de código abierto, multi-plataforma, que permite a los desarrolladores crear toda clase de herramientas de lado servidor y aplicaciones en JavaScript. Express es el framework web más popular de Node, y es la librería subyacente para un gran número de otros frameworks web de Node populares. 

#### Laravel
Laravel es un popular framework de PHP, permite el desarrollo de aplicaciones web totalmente personalizadas de elevada calidad, es uno de los más utilizados y de mayor comunidad en el mundo de Internet.

### Seleccionar los métodos de evaluación

A partir de lo anterior, nace la siguiente tabla, en la cual se indica la presencia o ausencia de as características descritas en la tabla 1, determinando los niveles de importancia, como se muestra a continuación:

<img :src="$withBase('/img/tabla2b.png')">

### Evaluar las soluciones alternativas

En la siguiente tabla se evalúan soluciones, para realizar esta evaluación se usó un método matemático, el cual determina cuantitativamente cuál framework es el más indicado según la descripción y calificación de sus características y así ser implementado en el desarrollo del proyecto SEGMAFLOT, esta evaluación se realizó mediante la siguiente fórmula:

<img :src="$withBase('/img/formula.png')">

Siendo:

Peso: La ponderación que se asignó a las características evaluadas
Valor: Calificación 1 o 0 si posee o no la característica descrita en la tabla de ponderación

<img :src="$withBase('/img/tablarb.png')">

1. La mayoría de los frameworks brindan una velocidad destacada, resaltando Vertx.
2. Todos los frameworks de acuerdo a la investigación permiten la escalabilidad
3. La mayoría de los frameworks cuenta con con una buena curva de aprendizaje a excepción de Vertx.
4. Todos los frameworks son multiplataforma.
5. Todas los los frameworks brindan una manera sencilla de integrar las dependencias sobresaliendo.
6. Todos los frameworks brindan una buena seguridad.
7. Spring boot, Jhipster laravel y node destacan por su simplicidad, excepto vertX.
8. Todos los frameworks destacan por su fácil configuración.
9. Todos los frameworks destacan por su amplia documentación y comunidad a excepción de VertX.
10. Todos los frameworks destacan por su compatibilidad.

### Seleccionar las soluciones

La selección de la solución se basa en la puntuación obtenida en el modelo matemático, debido a 10 características consideradas para el framework.

Al analizar los resultados nos encontramos con una solución viable, debido a que cumple con requerimientos como son la velocidad, escalabilidad, la sencilla integración de dependencias y su compatibilidad.

El resultado matemático obtenido se puede concluir con empate entre Spring boot y JHipster, Laravel y Node js/Express, que según el análisis realizado cumple con las características, basado en CMMI Análisis DAR.

## Referencias

* Get started | Eclipse Vert.x. (s. f.). Vertx.Io. https://vertx.io/get-started/

* Introduction to Vert.x and Reactive | Eclipse Vert.x. (s. f.). Vertx.Io. https://vertx.io/introduction-to-vertx-and-reactive/

* Programación Reactiva. (s. f.). Ferestrepoca. http://ferestrepoca.github.io/paradigmas-de-programacion/reactive/reactive_teoria/index.html

* Documentation | Eclipse Vert.x. (s. f.). Vertx.Io. https://vertx.io/docs/#testing

* Gracia, L. (2013, 4 junio). ¿Qué es vert.x? Un poco de Java. https://unpocodejava.com/2013/06/04/que-es-vert-x/#:%7E:text=x%20es%20un%20framework%20para,%2C%20Groovy%2C%20Ruby%20o%20Python.

* Webb, P. D. S. (s. f.). Spring Boot Reference Documentation. Spring.Io. https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#build-tool-plugins

* Caules, C. Á. (2022, 11 enero). ¿Qué es Spring Boot? Arquitectura Java. https://www.arquitecturajava.com/que-es-spring-boot/

* Spring Blog. (2022, 31 marzo). Spring. https://spring.io/blog

* JHipster: una completa suite para el desarrollo de aplicaciones web. (2022, 18 marzo). IONOS 

* Digitalguide. https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/jhipster/

* Creating an application. (s. f.). Jhipster.Tech. https://www.jhipster.tech/creating-an-app/

* Video tutorial. (s. f.). Jhipster.Tech. https://www.jhipster.tech/video-tutorial/

* Glosario de Express. (s. f.). expressjs.com. https://expressjs.com/es/resources/glossary.html

# Data-Bases

## Características de los sistemas gestores de bases de datos

* Son responsables de administrar adecuadamente los datos, evitan que usuarios y programas de comprender la ubicación física de los datos.
* Pueden administrar diferentes tipos de bases de datos, como bases de datos relacionales  y orientadas a objetos.
* Debe garantizar la seguridad de los datos que serán almacenados.
* Acceso concurrente de múltiples usuarios autorizados a los datos, realizando operaciones de actualización y consulta.
* Consistencia de datos.

## Analisis DAR

### Establecer las guías para el análisis de decisiones

* El sistema gestor de base de datos debe ser multiplataforma facilitando el trabajo por parte del equipo sin importar el sistema operativo con el que se trabaje.
* Autenticación de usuarios.
* Debe contar con un abanico de posibles lenguajes compatibles.
* Acepta consultas complejas.
* Cuenta con documentación y soporte en caso de requerirse.

### Establecer los criterios de evaluación

Los criterios de evaluación se basan en características esenciales de los sistemas gestores de base de datos, las cuales se presentan en el siguiente listado:

1. Velocidad.
2. Gratuito.
3. Escalabilidad horizontal.
4. Escalabilidad vertical.
5. Multiplataforma.
6. Nosql.
7. Permiten la autenticación de usuarios.
8. Almacenamiento sin límites.
9. Soporte gratuito.
10. Potente sintaxis permitiendo consultas complejas.
11. Replicación.
12. Permite transacciones.
13. Simplicidad.
14. Facilidad de instalación y configuración.
15. Herramienta gráfica.

En la siguiente tabla se asignan pesos y ponderaciones en un rango de 1 al 5.

<img :src="$withBase('/img/tablabd.png')">

### Identificar las soluciones alternativas

Basados en los resultados obtenidos por una encuestra realizada por StackOverFlow acerca de la tecnología más usada para base de datos nos encontramos con lo siguiente:

<img :src="$withBase('/img/graficabd.png')">

Como podemos apreciar en la figura anterior, MySQL lidera la encuesta seguida por PostgreSQL, del listado anterior tomaremos 4 herramientas que consideramos relevantes añadiendo a Firebase para proceder a conceptualizarlos y realizar la evaluación de características.

#### Firebase
Firebase se trata de una plataforma móvil creada por Google, cuya principal función es desarrollar y facilitar la creación de apps de elevada calidad de una forma rápida, con el fin de que se pueda aumentar la base de usuarios y ganar más dinero. La plataforma está subida en la nube y está disponible para diferentes plataformas como iOS, Android y web. Contiene diversas funciones para que cualquier desarrollador pueda combinar y adaptar la plataforma a medida de sus necesidades.

#### MySQL
MySQL es un sistema de gestión de bases de datos relacionales (RDBMS) de código abierto respaldado por Oracle y basado en el lenguaje de consulta estructurado (SQL). MySQL funciona prácticamente en todas las plataformas, incluyendo Linux, UNIX y Windows. Aunque puede utilizarse en una amplia gama de aplicaciones, MySQL se asocia más a menudo con las aplicaciones web y la publicación en línea.

#### PostgreSql
PostgreSql es un sistema de código abierto de administración de bases de datos del tipo relacional, aunque también es posible ejecutar consultas que sean no relaciones. En este sistema, las consultas relacionales se basan en SQL, mientras que las no relacionales hacen uso de JSON.

#### Microsoft SQL Server (SQL server)
Microsoft SQL Server (SQL server) es un sistema de gestión de bases de datos relacionales (RDBMS) que admite una amplia variedad  de aplicaciones de procesamiento de transacciones, inteligencia empresarial y análisis en entornos informáticos corporativos. Microsoft SQL Server es una de las tres tecnologías de bases de datos líderes del mercado, junto con Oracle Database y DB2 de IBM.

#### MongoDB
MongoDB es un sistema de base de datos NoSQL orientado a documentos de código abierto y escrito en C++, que en lugar de guardar los datos en tablas lo hace en estructuras de datos BSON (similar a JSON) con un esquema dinámico. Al ser un proyecto de código abierto, sus binarios están disponibles para los sistemas operativos Windows, GNU/Linux, OS X y Solaris y es usado en múltiples proyectos o implementaciones en empresas como MTV Network, Craigslist, BCI o Foursquare

### Seleccionar los métodos de evaluación

A partir de lo anterior, nace la siguiente tabla, en la cual se indica la presencia o ausencia de as características descritas en la tabla 1, determinando los niveles de importancia, como se muestra a continuación:

<img :src="$withBase('/img/tabladb2.png')">

En la siguiente tabla se evalúan soluciones, para realizar esta evaluación se usó un método matemático, el cual determina cuantitativamente cuál gestor de base de datos en el más indicado según la descripción y calificación de sus características y así ser implementado en el desarrollo del proyecto SEGMAFLOT, esta evaluación se realizó mediante la siguiente fórmula:

<img :src="$withBase('/img/formula.png')">

Siendo:

Peso: La ponderación que se asignó a las características evaluadas
Valor: Calificación 1 o 0 si posee o no la característica descrita en la tabla de ponderaciones

<img :src="$withBase('/img/trablarsdb.png')">

1. La mayoría cuentan con velocidad considerable, destacando MongoDB y MySQL
2. La mayoría de las opciones son de versión gratuita a excepción de Firebase quien cuenta con paquetes que se adaptan a las necesidades del usuario, lo mismo pasa con MongoDb con su versión Mongo Atlas.
3. Los gestores NoSQL por excelencia aceptan escalabilidad horizontal. 
4. Todos los gestores aceptan escalabilidad vertical.
5. Todos los gestores de base de datos, son multiplataforma
6. Firebase y Mongo son gestores noSql, aunque en algunos gestores se permiten la creación de bases de datos híbridas.
7. La autenticación de usuarios Firebase la permite de manera nativa, integrando la opción de autenticación con redes sociales
8. La mayoría de los gestores que no se encuentran en la nube cuentan con almacenamiento ilimitado.
9. Algunos gestores de base de datos ofrecen el soporte bajo licencia o suscripción.
10. Todos aceptan sintaxis complejas de consultas permitiéndonos obtener resultados más complejos.
11. Todos los gestores de base de datos permiten la replicación.
12. Todos los gestores de base de datos permiten transacciones.
13. La mayoría de los gestores de bases de datos son fáciles de utilizar, algunos un poco más complejos que otros.
14. Todos son fáciles de instalar y configurar.
15. Cuentan con una parte gráfica donde se muestra la información de manera más fácil de comprender.

### Seleccionar las soluciones

La selección de la solución se basa en la puntuación obtenida en el modelo matemático, debido a 15 características consideradas para el gestor de base de datos.

Al analizar los resultados nos encontramos con una solución viable, debido que cumple con requerimientos como son la compatibilidad, que no represente gastos por su uso y licencia, así como un potente gestor que nos permita realizar la maquetación de una base de datos nosql aceptando documentos como registros y obteniendo consultas fiables acorde a nuestras necesidades.

El resultado matemático obtenido se puede concluir con el gestor de base de datos MongoDB, que según el análisis realizado cumple con las características, basado en CMMI Análisis DAR.

## Referencias

* Firebase Pricing. (2022). Firebase. https://firebase.google.com/pricing

* Primeros pasos con Cloud Firestore | Firebase Documentation. (2021). Firebase. https://firebase.google.com/docs/firestore/quickstart?hl=es-419#web-version-9

* Mora, S. L. (2020, 27 mayo). Firebase: qué es, para qué sirve, funcionalidades y ventajas. DIGITAL55. https://www.digital55.com/desarrollo-tecnologia/que-es-firebase-funcionalidades-ventajas-conclusiones/

* MongoDB. (s. f.). Comparando Firebase Y. https://www.mongodb.com/es/firebase-vs-mongodb#:%7E:text=MongoDB%20is%20a%20more%20robust,purely%20a%20cloud%20database%20service

* MongoDB. (s. f.-c). MongoDB: The Application Data Platform. https://www.mongodb.com/

* MySQL: ¿Qué es? Características, Ventajas y Desventajas. (2019, 24 enero). hostingpedia.net. https://hostingpedia.net/mysql.html

* PostgreSQL: About. (s. f.). The PostgreSQL Global Development Group. https://www.postgresql.org/about/

* Stack Overflow Developer Survey 2021. (s. f.). Stack Overflow. https://insights.stackoverflow.com/survey/2021/#most-popular-technologies-database

* O. (2017, 7 marzo). Escalabilidad Horizontal y Vertical. Oscar Blancarte - Software Architecture. https://www.oscarblancarteblog.com/2017/03/07/escalabilidad-horizontal-y-vertical/

* Beneficios de la Replicación de Base de Datos. (s. f.). blog.powerdata. https://blog.powerdata.es/el-valor-de-la-gestion-de-datos/beneficios-de-la-replicacion-de-base-de-datos

* Cardona, M. P. (2020, 8 enero). Firebase, qué es y para qué sirve la plataforma de Google. Thinking for Innovation. https://www.iebschool.com/blog/firebase-que-es-para-que-sirve-la-plataforma-desarroladores-google-seo-sem/

* de TechTarget, C. (2021, 23 abril). MySQL. ComputerWeekly.es. https://www.computerweekly.com/es/definicion/MySQL

* Borges, S. (2019, 19 noviembre). Servidor PostgreSQL. Infranetworking. https://blog.infranetworking.com/servidor-postgresql/

* Cardona, M. P. (2020, 8 enero). Firebase, qué es y para qué sirve la plataforma de Google. Thinking for Innovation. https://www.iebschool.com/blog/firebase-que-es-para-que-sirve-la-plataforma-desarroladores-google-seo-sem/

* Robledano, A. (2021, 26 agosto). Qué es MongoDB. OpenWebinars.net. https://openwebinars.net/blog/que-es-mongodb/

# Data-Bases

## Características de los sistemas gestores de bases de datos

* Son responsables de administrar adecuadamente los datos, evitan que usuarios y programas de comprender la ubicación física de los datos.
* Pueden administrar diferentes tipos de bases de datos, como bases de datos relacionales  y orientadas a objetos.
* Debe garantizar la seguridad de los datos que serán almacenados.
* Acceso concurrente de múltiples usuarios autorizados a los datos, realizando operaciones de actualización y consulta.
* Consistencia de datos.

## Analisis DAR

### Establecer las guías para el análisis de decisiones

* El sistema gestor de base de datos debe ser multiplataforma facilitando el trabajo por parte del equipo sin importar el sistema operativo con el que se trabaje.
* Autenticación de usuarios.
* Debe contar con un abanico de posibles lenguajes compatibles.
* Acepta consultas complejas.
* Cuenta con documentación y soporte en caso de requerirse.

### Establecer los criterios de evaluación

Los criterios de evaluación se basan en características esenciales de los sistemas gestores de base de datos, las cuales se presentan en el siguiente listado:

1. Velocidad.
2. Gratuito.
3. Escalabilidad horizontal.
4. Escalabilidad vertical.
5. Multiplataforma.
6. Nosql.
7. Permiten la autenticación de usuarios.
8. Almacenamiento sin límites.
9. Soporte gratuito.
10. Potente sintaxis permitiendo consultas complejas.
11. Replicación.
12. Permite transacciones.
13. Simplicidad.
14. Facilidad de instalación y configuración.
15. Herramienta gráfica.

En la siguiente tabla se asignan pesos y ponderaciones en un rango de 1 al 5.

<img :src="$withBase('/img/tablabd.png')">

### Identificar las soluciones alternativas

Basados en los resultados obtenidos por una encuestra realizada por StackOverFlow acerca de la tecnología más usada para base de datos nos encontramos con lo siguiente:

<img :src="$withBase('/img/graficabd.png')">

Como podemos apreciar en la figura anterior, MySQL lidera la encuesta seguida por PostgreSQL, del listado anterior tomaremos 4 herramientas que consideramos relevantes añadiendo a Firebase para proceder a conceptualizarlos y realizar la evaluación de características.

#### Firebase
Firebase se trata de una plataforma móvil creada por Google, cuya principal función es desarrollar y facilitar la creación de apps de elevada calidad de una forma rápida, con el fin de que se pueda aumentar la base de usuarios y ganar más dinero. La plataforma está subida en la nube y está disponible para diferentes plataformas como iOS, Android y web. Contiene diversas funciones para que cualquier desarrollador pueda combinar y adaptar la plataforma a medida de sus necesidades.

#### MySQL
MySQL es un sistema de gestión de bases de datos relacionales (RDBMS) de código abierto respaldado por Oracle y basado en el lenguaje de consulta estructurado (SQL). MySQL funciona prácticamente en todas las plataformas, incluyendo Linux, UNIX y Windows. Aunque puede utilizarse en una amplia gama de aplicaciones, MySQL se asocia más a menudo con las aplicaciones web y la publicación en línea.

#### PostgreSql
PostgreSql es un sistema de código abierto de administración de bases de datos del tipo relacional, aunque también es posible ejecutar consultas que sean no relaciones. En este sistema, las consultas relacionales se basan en SQL, mientras que las no relacionales hacen uso de JSON.

#### Microsoft SQL Server (SQL server)
Microsoft SQL Server (SQL server) es un sistema de gestión de bases de datos relacionales (RDBMS) que admite una amplia variedad  de aplicaciones de procesamiento de transacciones, inteligencia empresarial y análisis en entornos informáticos corporativos. Microsoft SQL Server es una de las tres tecnologías de bases de datos líderes del mercado, junto con Oracle Database y DB2 de IBM.

#### MongoDB
MongoDB es un sistema de base de datos NoSQL orientado a documentos de código abierto y escrito en C++, que en lugar de guardar los datos en tablas lo hace en estructuras de datos BSON (similar a JSON) con un esquema dinámico. Al ser un proyecto de código abierto, sus binarios están disponibles para los sistemas operativos Windows, GNU/Linux, OS X y Solaris y es usado en múltiples proyectos o implementaciones en empresas como MTV Network, Craigslist, BCI o Foursquare

### Seleccionar los métodos de evaluación

A partir de lo anterior, nace la siguiente tabla, en la cual se indica la presencia o ausencia de as características descritas en la tabla 1, determinando los niveles de importancia, como se muestra a continuación:

<img :src="$withBase('/img/tabladb2.png')">

En la siguiente tabla se evalúan soluciones, para realizar esta evaluación se usó un método matemático, el cual determina cuantitativamente cuál gestor de base de datos en el más indicado según la descripción y calificación de sus características y así ser implementado en el desarrollo del proyecto SEGMAFLOT, esta evaluación se realizó mediante la siguiente fórmula:

<img :src="$withBase('/img/formula.png')">

Siendo:

Peso: La ponderación que se asignó a las características evaluadas
Valor: Calificación 1 o 0 si posee o no la característica descrita en la tabla de ponderaciones

<img :src="$withBase('/img/trablarsdb.png')">

1. La mayoría cuentan con velocidad considerable, destacando MongoDB y MySQL
2. La mayoría de las opciones son de versión gratuita a excepción de Firebase quien cuenta con paquetes que se adaptan a las necesidades del usuario, lo mismo pasa con MongoDb con su versión Mongo Atlas.
3. Los gestores NoSQL por excelencia aceptan escalabilidad horizontal. 
4. Todos los gestores aceptan escalabilidad vertical.
5. Todos los gestores de base de datos, son multiplataforma
6. Firebase y Mongo son gestores noSql, aunque en algunos gestores se permiten la creación de bases de datos híbridas.
7. La autenticación de usuarios Firebase la permite de manera nativa, integrando la opción de autenticación con redes sociales
8. La mayoría de los gestores que no se encuentran en la nube cuentan con almacenamiento ilimitado.
9. Algunos gestores de base de datos ofrecen el soporte bajo licencia o suscripción.
10. Todos aceptan sintaxis complejas de consultas permitiéndonos obtener resultados más complejos.
11. Todos los gestores de base de datos permiten la replicación.
12. Todos los gestores de base de datos permiten transacciones.
13. La mayoría de los gestores de bases de datos son fáciles de utilizar, algunos un poco más complejos que otros.
14. Todos son fáciles de instalar y configurar.
15. Cuentan con una parte gráfica donde se muestra la información de manera más fácil de comprender.

### Seleccionar las soluciones

La selección de la solución se basa en la puntuación obtenida en el modelo matemático, debido a 15 características consideradas para el gestor de base de datos.

Al analizar los resultados nos encontramos con una solución viable, debido que cumple con requerimientos como son la compatibilidad, que no represente gastos por su uso y licencia, así como un potente gestor que nos permita realizar la maquetación de una base de datos nosql aceptando documentos como registros y obteniendo consultas fiables acorde a nuestras necesidades.

El resultado matemático obtenido se puede concluir con el gestor de base de datos MongoDB, que según el análisis realizado cumple con las características, basado en CMMI Análisis DAR.

## Referencias

* Firebase Pricing. (2022). Firebase. https://firebase.google.com/pricing

* Primeros pasos con Cloud Firestore | Firebase Documentation. (2021). Firebase. https://firebase.google.com/docs/firestore/quickstart?hl=es-419#web-version-9

* Mora, S. L. (2020, 27 mayo). Firebase: qué es, para qué sirve, funcionalidades y ventajas. DIGITAL55. https://www.digital55.com/desarrollo-tecnologia/que-es-firebase-funcionalidades-ventajas-conclusiones/

* MongoDB. (s. f.). Comparando Firebase Y. https://www.mongodb.com/es/firebase-vs-mongodb#:%7E:text=MongoDB%20is%20a%20more%20robust,purely%20a%20cloud%20database%20service

* MongoDB. (s. f.-c). MongoDB: The Application Data Platform. https://www.mongodb.com/

* MySQL: ¿Qué es? Características, Ventajas y Desventajas. (2019, 24 enero). hostingpedia.net. https://hostingpedia.net/mysql.html

* PostgreSQL: About. (s. f.). The PostgreSQL Global Development Group. https://www.postgresql.org/about/

* Stack Overflow Developer Survey 2021. (s. f.). Stack Overflow. https://insights.stackoverflow.com/survey/2021/#most-popular-technologies-database

* O. (2017, 7 marzo). Escalabilidad Horizontal y Vertical. Oscar Blancarte - Software Architecture. https://www.oscarblancarteblog.com/2017/03/07/escalabilidad-horizontal-y-vertical/

* Beneficios de la Replicación de Base de Datos. (s. f.). blog.powerdata. https://blog.powerdata.es/el-valor-de-la-gestion-de-datos/beneficios-de-la-replicacion-de-base-de-datos

* Cardona, M. P. (2020, 8 enero). Firebase, qué es y para qué sirve la plataforma de Google. Thinking for Innovation. https://www.iebschool.com/blog/firebase-que-es-para-que-sirve-la-plataforma-desarroladores-google-seo-sem/

* de TechTarget, C. (2021, 23 abril). MySQL. ComputerWeekly.es. https://www.computerweekly.com/es/definicion/MySQL

* Borges, S. (2019, 19 noviembre). Servidor PostgreSQL. Infranetworking. https://blog.infranetworking.com/servidor-postgresql/

* Cardona, M. P. (2020, 8 enero). Firebase, qué es y para qué sirve la plataforma de Google. Thinking for Innovation. https://www.iebschool.com/blog/firebase-que-es-para-que-sirve-la-plataforma-desarroladores-google-seo-sem/

* Robledano, A. (2021, 26 agosto). Qué es MongoDB. OpenWebinars.net. https://openwebinars.net/blog/que-es-mongodb/


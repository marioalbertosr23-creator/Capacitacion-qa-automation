MARIO ALBERTO SOTO RUBIO

Modulo-01-introduccion

Automatización de pruebas en QA
La automatización nació como una forma de mejorar la eficiencia y la productividad en distintos procesos de trabajo. Su principal objetivo es reducir las tareas repetitivas, disminuir los errores ocasionados por la intervención humana y optimizar el uso de los recursos disponibles. Además, permite que las empresas mantengan una mejor calidad en sus productos y servicios, al mismo tiempo que pueden responder con mayor rapidez a los cambios del mercado y a las necesidades de los clientes.

Beneficios de la automatización frente a las pruebas manuales
Después de analizar el tema, se puede observar que la automatización de pruebas ofrece varias ventajas sobre las pruebas manuales, especialmente cuando se trabaja con proyectos de software que requieren actualizaciones frecuentes.
Uno de los beneficios más importantes es la rapidez con la que se ejecutan las pruebas. Mientras que una persona puede tardar horas o incluso días en revisar todos los casos de prueba, un conjunto de pruebas automatizadas puede completarse en cuestión de minutos. Además, estas pruebas pueden ejecutarse de manera continua y en diferentes entornos al mismo tiempo.
Otro aspecto relevante es la reducción de errores humanos. Como las pruebas siguen instrucciones previamente definidas, los resultados son consistentes y disminuye la posibilidad de cometer equivocaciones durante la ejecución.
La automatización también permite ampliar considerablemente la cobertura de pruebas. Es posible validar miles de escenarios, diferentes combinaciones de datos y casos poco comunes que manualmente requerirían demasiado tiempo o resultan difíciles de ejecutar.
Finalmente, muchas herramientas de automatización generan reportes detallados y en tiempo real, facilitando el seguimiento de los resultados y la detección de fallos durante el desarrollo del software.

¿Cuándo es indispensable automatizar?
Existen situaciones en las que realizar pruebas manuales deja de ser suficiente. Esto sucede principalmente cuando la cantidad de pruebas aumenta y el tiempo disponible para liberar nuevas versiones del software es muy reducido.
Uno de los casos más comunes son las pruebas de regresión en sistemas ya consolidados. Cada vez que se incorpora una nueva funcionalidad existe el riesgo de afectar partes del sistema que ya funcionaban correctamente. Automatizar estas pruebas permiten comprobar rápidamente que los cambios no generaron nuevos errores.
Otro escenario importante son las pruebas de rendimiento y carga. Simular miles de usuarios utilizando una aplicación al mismo tiempo solo es posible mediante herramientas especializadas de automatización.
También resulta fundamental automatizar las pruebas de APIs, donde se deben validar numerosas combinaciones de datos y verificar que las respuestas del sistema sean correctas en cada caso.
En metodologías de desarrollo modernas, como aquellas que utilizan integración y despliegue continuo (CI/CD), la automatización es prácticamente obligatoria. Cada modificación realizada por los desarrolladores debe ser validada automáticamente antes de llegar al entorno de producción.
Las pruebas unitarias representan otro ejemplo claro, ya que normalmente se desarrollan de forma automatizada para verificar que cada componente del sistema funcione correctamente desde las primeras etapas del desarrollo.
Por último, las llamadas pruebas de humo permiten confirmar inmediatamente después de un despliegue que las funciones críticas del sistema, como el inicio de sesión o el procesamiento de pagos, continúan operando correctamente.

¿Cuándo siguen siendo necesarias las pruebas manuales?
Aunque la automatización aporta muchas ventajas, las pruebas manuales siguen siendo indispensables en determinadas situaciones. Hay aspectos que requieren la experiencia y el criterio de una persona para ser evaluados correctamente.
Las pruebas exploratorias son un buen ejemplo. En ellas, el tester analiza el sistema libremente, buscando comportamientos inesperados o errores que no fueron contemplados durante el diseño de los casos de prueba.
La evaluación de la experiencia de usuario (UX) también depende en gran medida de la observación humana. Aspectos como la facilidad de uso, la claridad de los mensajes o la comodidad durante la navegación no pueden medirse completamente mediante scripts automatizados.
Durante el desarrollo de nuevas funcionalidades o versiones beta, donde los cambios son constantes, automatizar todas las pruebas puede resultar poco práctico, ya que estas deberán modificarse continuamente.
Asimismo, aunque existen herramientas que ayudan a detectar problemas de accesibilidad, todavía es necesario que una persona valide la experiencia real utilizando tecnologías como lectores de pantalla o diferentes métodos de navegación.
Por estas razones, las pruebas manuales y las automatizadas no deben verse como alternativas que compiten entre sí, sino como actividades complementarias que, al combinarse, permiten obtener un proceso de aseguramiento de la calidad mucho más completo.

Flujo para implementar la automatización de pruebas
La implementación de pruebas automatizadas generalmente sigue una serie de pasos bien definidos.
Selección de la herramienta: El primer paso consiste en elegir una herramienta de automatización que sea compatible con la tecnología utilizada por la aplicación y que se adapte tanto al presupuesto como a la experiencia del equipo de desarrollo.
Definición del alcance: Después, es importante determinar qué pruebas realmente conviene automatizar. No todas las pruebas ofrecen el mismo beneficio, por lo que establecer prioridades ayuda a obtener un mejor retorno de la inversión.
Diseño y desarrollo: En esta etapa se configura el entorno de trabajo, se diseña el marco de automatización y se desarrollan los scripts que ejecutarán las pruebas.
Ejecución de las pruebas: Una vez implementados los scripts, estos pueden ejecutarse automáticamente de manera programada o integrarse al proceso de desarrollo para validar continuamente el funcionamiento del sistema.
Mantenimiento: Finalmente, la automatización requiere un mantenimiento constante. Conforme el software evoluciona, los casos de prueba también deben actualizarse para seguir siendo útiles y garantizar resultados confiables a lo largo del tiempo.

Modulo-02-terminal

La terminal es una herramienta que permite comunicarse directamente con el sistema operativo mediante la escritura de órdenes. En lugar de utilizar ventanas, iconos o botones como en una interfaz gráfica, la terminal funciona a través de texto. Gracias a ella es posible realizar muchas tareas, como crear y organizar archivos, ejecutar programas, instalar aplicaciones o administrar el sistema de una forma más rápida y precisa.

Por otro lado, una línea de comandos es la instrucción que el usuario escribe dentro de la terminal para indicar al sistema qué acción debe realizar. Cada comando tiene una función específica y, en muchos casos, puede ir acompañado de opciones o parámetros para modificar su comportamiento. Por ejemplo, un comando puede servir para mostrar el contenido de una carpeta, copiar un archivo o eliminar un documento.

En resumen, la terminal es el programa o entorno donde se escriben las órdenes, mientras que la línea de comandos es cada una de las instrucciones que se introducen en ese entorno para que el sistema las ejecute. Aunque hoy en día la mayoría de usuarios utilizan interfaces gráficas, la terminal sigue siendo una herramienta muy útil, especialmente para tareas de administración, programación y automatización.

Los comandos de navegación permiten desplazarse por las carpetas del sistema y gestionar el contenido desde la terminal sin necesidad de utilizar el explorador de archivos.

cd (Change Directory): se utiliza para cambiar de carpeta o directorio. Es uno de los comandos más usados, ya que permite moverse entre las distintas ubicaciones del sistema. Por ejemplo, al escribir cd Documentos, la terminal accederá a la carpeta llamada Documentos.
dir: muestra el contenido del directorio en el que nos encontramos. Al ejecutarlo aparece una lista con las carpetas y los archivos disponibles, lo que facilita saber qué elementos hay en esa ubicación.
cd ..: sirve para retroceder un nivel en la estructura de carpetas. Es decir, permite salir de la carpeta actual y volver a la carpeta superior. Es un comando muy útil cuando se necesita regresar rápidamente al directorio anterior.
cls (Clear Screen): limpia la pantalla de la terminal eliminando el historial visible de los comandos ejecutados, aunque no borra los archivos ni afecta al funcionamiento del sistema. Su objetivo es mantener la consola ordenada y facilitar la lectura de los nuevos comandos.

En conjunto, estos comandos son los más básicos para moverse por el sistema desde la terminal y constituyen la base para trabajar de forma eficiente con la línea de comandos.

Los comandos de manejo de archivos y carpetas permiten crear, modificar, consultar y eliminar elementos del sistema directamente desde la terminal, sin necesidad de utilizar una interfaz gráfica.

mkdir (Make Directory): se utiliza para crear una nueva carpeta o directorio. Solo hay que escribir el comando seguido del nombre de la carpeta que se desea crear. Por ejemplo, mkdir Proyectos creará una carpeta llamada Proyectos.
echo: permite mostrar un mensaje en la pantalla o escribir texto dentro de un archivo. Es un comando muy útil para crear archivos de texto sencillos o añadir información rápidamente desde la terminal.
type: sirve para visualizar el contenido de un archivo de texto directamente en la terminal. De esta forma, es posible leer lo que contiene un archivo sin necesidad de abrir un editor de texto.
del (Delete): se utiliza para eliminar uno o varios archivos. Una vez ejecutado el comando, los archivos seleccionados se borran del sistema, por lo que conviene utilizarlo con cuidado para evitar eliminar información importante.
rmdir (Remove Directory): permite borrar una carpeta. Normalmente, la carpeta debe estar vacía para que el comando funcione correctamente. Si contiene archivos o subcarpetas, será necesario eliminarlos antes o utilizar opciones adicionales.

Estos comandos son fundamentales para gestionar archivos y carpetas desde la terminal y permiten realizar tareas de organización de forma rápida y eficiente.

Los comandos de red permiten obtener información sobre la conexión a Internet, comprobar si un equipo puede comunicarse con otro y acceder a recursos disponibles en la red. Son herramientas muy útiles para detectar y solucionar problemas de conectividad.

ping: se utiliza para comprobar si un dispositivo o una página web es accesible desde el equipo. El comando envía pequeños paquetes de datos al destino y mide el tiempo que tardan en responder. Si hay respuesta, significa que existe comunicación entre ambos equipos.
ipconfig: muestra la configuración de red del ordenador. Con este comando es posible conocer datos como la dirección IP, la puerta de enlace o la máscara de subred. También dispone de opciones para renovar la dirección IP o vaciar la memoria caché del sistema relacionada con la resolución de nombres.
curl: permite realizar solicitudes a páginas web o servidores directamente desde la terminal. Se utiliza para descargar archivos, consultar el contenido de una página web o probar el funcionamiento de servicios y aplicaciones que trabajan a través de Internet.

En conjunto, estos comandos ayudan a comprobar el estado de la conexión, conocer la configuración de la red y comunicarse con servidores de forma rápida desde la línea de comandos.

Modulo-03-localizadores

Los localizadores son direcciones o rutas que permiten identificar y encontrar un recurso dentro de un sistema o en Internet. Estos recursos pueden ser archivos, carpetas, páginas web o cualquier otro elemento al que se quiera acceder. Gracias a los localizadores, el sistema sabe exactamente dónde se encuentra la información solicitada.

Son esenciales porque facilitan el acceso a los recursos de forma rápida y organizada, evitando tener que buscarlos manualmente. En el caso de Internet, por ejemplo, un localizador como una URL indica al navegador la ubicación exacta de una página web para poder cargarla correctamente. Del mismo modo, en un sistema operativo, la ruta de un archivo permite localizarlo sin importar en qué carpeta esté almacenado.

En resumen, los localizadores son fundamentales porque hacen posible acceder a la información de manera precisa y eficiente, tanto en un ordenador como en una red o en Internet.

Los selectores CSS son reglas que permiten indicar a qué elementos de una página web se les aplicarán determinados estilos. Gracias a ellos, es posible modificar la apariencia de uno o varios elementos de forma sencilla y organizada.

Selector por clase (.clase): se utiliza para aplicar el mismo estilo a varios elementos. Los elementos que comparten una misma clase reciben el mismo formato, por lo que es uno de los selectores más utilizados.
Selector por ID (#id): sirve para seleccionar un único elemento de la página, ya que cada ID debe ser exclusivo. Se emplea cuando se quiere aplicar un estilo específico a un elemento concreto.
Selector por atributo ([atributo]): permite seleccionar elementos que contienen un determinado atributo o un valor concreto en ese atributo. Es útil para aplicar estilos según las características de un elemento, sin depender de su clase o ID.
Selectores jerárquicos: se utilizan para seleccionar elementos según su posición dentro del documento HTML. Por ejemplo, es posible aplicar un estilo a todos los párrafos que estén dentro de una sección determinada o a los elementos que sean hijos directos de otro.
Selectores múltiples: permiten seleccionar varios elementos diferentes al mismo tiempo utilizando una sola regla CSS. De esta manera, varios elementos pueden compartir los mismos estilos sin necesidad de escribir varias reglas independientes.

En conjunto, los selectores CSS hacen posible aplicar estilos de forma precisa y organizada, facilitando el diseño y el mantenimiento de las páginas web.

XPath es un lenguaje que se utiliza para localizar y seleccionar elementos dentro de un documento XML o HTML. Es muy empleado en el desarrollo web, las pruebas automatizadas y el web scraping, ya que permite encontrar elementos de forma precisa.

XPath absoluto: indica la ruta completa desde la raíz del documento hasta el elemento que se quiere localizar. Es muy preciso, pero también más frágil, ya que cualquier cambio en la estructura de la página puede hacer que deje de funcionar.
XPath relativo: comienza la búsqueda desde cualquier parte del documento, sin necesidad de indicar toda la ruta. Es más flexible y resistente a los cambios en la estructura de la página, por lo que suele ser el más utilizado.
XPath por texto: permite localizar un elemento según el texto que contiene. Es útil cuando un elemento no tiene un identificador o una clase específica, pero sí un texto que lo distingue de los demás.
XPath combinado: consiste en utilizar varios criterios al mismo tiempo, como atributos, texto y relaciones entre elementos. De esta forma, se consigue una búsqueda más precisa y se reducen las posibilidades de seleccionar un elemento incorrecto.

En resumen, XPath ofrece diferentes formas de localizar elementos en un documento. La elección entre un XPath absoluto, relativo, por texto o combinado dependerá de la estructura de la página y de la precisión que se necesite en cada caso.

Los IDs y los atributos únicos son formas de identificar elementos concretos dentro de una página web. Se utilizan con frecuencia en desarrollo web y en herramientas de automatización, ya que permiten localizar elementos de forma rápida y precisa.

IDs: un ID es un identificador que debe ser único dentro de una página HTML. Esto significa que solo puede existir un elemento con ese mismo ID. Cuando un elemento dispone de un ID estable, suele ser el mejor localizador, ya que es fácil de identificar y normalmente no cambia con frecuencia.
Atributos únicos: además del ID, algunos elementos cuentan con otros atributos que también pueden servir para identificarlos, como name, data-testid, title o aria-label. Si estos atributos tienen un valor único, también son buenos localizadores, especialmente cuando el elemento no dispone de un ID.
¿Cuándo preferir cada tipo de localizador?

Siempre que sea posible, es recomendable utilizar un ID, ya que es el método más directo, rápido y fiable para localizar un elemento. Si el elemento no tiene un ID o este cambia con frecuencia, lo mejor es recurrir a un atributo único que permanezca estable. En cambio, los localizadores basados únicamente en la posición del elemento o en rutas muy largas, como algunos XPath absolutos, deberían evitarse porque pueden dejar de funcionar si cambia la estructura de la página.

En resumen, la mejor práctica es utilizar primero un ID, después un atributo único y, solo cuando no exista ninguna de estas opciones, emplear otros tipos de localizadores como selectores CSS o XPath.Los IDs y los atributos únicos son formas de identificar elementos concretos dentro de una página web. Se utilizan con frecuencia en desarrollo web y en herramientas de automatización, ya que permiten localizar elementos de forma rápida y precisa.

IDs: un ID es un identificador que debe ser único dentro de una página HTML. Esto significa que solo puede existir un elemento con ese mismo ID. Cuando un elemento dispone de un ID estable, suele ser el mejor localizador, ya que es fácil de identificar y normalmente no cambia con frecuencia.
Atributos únicos: además del ID, algunos elementos cuentan con otros atributos que también pueden servir para identificarlos, como name, data-testid, title o aria-label. Si estos atributos tienen un valor único, también son buenos localizadores, especialmente cuando el elemento no dispone de un ID.
¿Cuándo preferir cada tipo de localizador?

Siempre que sea posible, es recomendable utilizar un ID, ya que es el método más directo, rápido y fiable para localizar un elemento. Si el elemento no tiene un ID o este cambia con frecuencia, lo mejor es recurrir a un atributo único que permanezca estable. En cambio, los localizadores basados únicamente en la posición del elemento o en rutas muy largas, como algunos XPath absolutos, deberían evitarse porque pueden dejar de funcionar si cambia la estructura de la página.

En resumen, la mejor práctica es utilizar primero un ID, después un atributo único y, solo cuando no exista ninguna de estas opciones, emplear otros tipos de localizadores como selectores CSS o XPath.

Modulo-04-pepinillo

Gherkin es un lenguaje de escritura sencillo y fácil de entender que se utiliza para describir el comportamiento esperado de una aplicación. Su principal característica es que emplea un lenguaje muy cercano al lenguaje natural, por lo que puede ser leído tanto por desarrolladores como por testers, analistas o clientes, incluso aunque no tengan conocimientos de programación.

En la metodología BDD (Behavior-Driven Development) o Desarrollo Guiado por el Comportamiento, Gherkin sirve para definir de forma clara cómo debe comportarse una aplicación en diferentes situaciones. De esta manera, todos los miembros del equipo comparten una misma comprensión de los requisitos antes de comenzar el desarrollo o las pruebas.

Los escenarios en Gherkin suelen escribirse utilizando palabras clave como Feature (Funcionalidad), Scenario (Escenario), Given (Dado), When (Cuando) y Then (Entonces). Esta estructura permite describir las condiciones iniciales, la acción que realiza el usuario y el resultado esperado de una forma ordenada y fácil de seguir.

En resumen, Gherkin es una herramienta fundamental en BDD porque facilita la comunicación entre todas las personas involucradas en el proyecto y permite convertir los requisitos del negocio en escenarios de prueba claros, comprensibles y fáciles de automatizar.

La sintaxis de Gherkin utiliza una serie de palabras clave que permiten escribir escenarios de prueba de una forma estructurada y fácil de entender. Cada una de ellas tiene una función específica dentro de la descripción del comportamiento de una aplicación.

Feature (Funcionalidad): se utiliza para indicar la funcionalidad o característica que se quiere describir. Normalmente incluye una breve explicación de qué parte del sistema se va a probar.
Scenario (Escenario): define un caso concreto dentro de una funcionalidad. Cada escenario representa una situación que se quiere comprobar y describe un comportamiento específico de la aplicación.
Given (Dado): establece las condiciones iniciales del escenario, es decir, el estado en el que se encuentra el sistema antes de realizar una acción. Sirve para indicar el contexto de la prueba.
When (Cuando): describe la acción que realiza el usuario o el evento que ocurre durante el escenario. Es el paso donde se indica qué sucede en la prueba.
Then (Entonces): define el resultado esperado después de realizar la acción. Se utiliza para comprobar si el comportamiento de la aplicación es el correcto.
And (Y): permite añadir más pasos relacionados con el contexto, las acciones o los resultados, evitando tener que repetir palabras clave como Given, When o Then.

Scenario Outline y Examples son elementos de Gherkin que permiten crear escenarios parametrizados, es decir, realizar la misma prueba varias veces utilizando diferentes datos sin tener que escribir un escenario nuevo para cada caso.

Scenario Outline (Esquema del escenario): se utiliza cuando un escenario tiene la misma estructura, pero necesita probar distintos valores. En lugar de escribir varias veces los mismos pasos, se utilizan variables entre símbolos de menor y mayor (< >) que después serán sustituidas por los datos de la tabla de ejemplos.
Examples (Ejemplos): contiene la información que se utilizará para reemplazar las variables del Scenario Outline. Los datos se organizan en una tabla, donde cada fila representa una ejecución diferente del escenario.

En Gherkin, existen elementos adicionales que ayudan a organizar mejor los escenarios y hacer que los archivos de pruebas sean más claros y fáciles de mantener.

Background (Contexto): se utiliza para definir pasos comunes que deben ejecutarse antes de todos los escenarios de una misma funcionalidad. De esta forma, se evita repetir las mismas instrucciones en cada Scenario. Por ejemplo, si todos los escenarios necesitan que el usuario esté registrado o que se abra una página concreta, esos pasos pueden colocarse en un Background.
@Tags (Etiquetas): son etiquetas que se escriben utilizando el símbolo @ y sirven para clasificar y organizar escenarios o funcionalidades. Permiten seleccionar qué pruebas se quieren ejecutar, por ejemplo, pruebas de inicio de sesión, pruebas críticas o pruebas de una determinada sección de la aplicación.
Comentarios: se utilizan para añadir aclaraciones dentro del archivo Gherkin sin que afecten a la ejecución de las pruebas. Normalmente se escriben comenzando la línea con el símbolo #. Son útiles para explicar partes del código, añadir notas o facilitar la comprensión del equipo.

Modulo-05-git-github

Git y GitHub están relacionados, pero cumplen funciones diferentes dentro del desarrollo de software.

Git: es un sistema de control de versiones que se instala en el ordenador y permite registrar los cambios realizados en un proyecto. Gracias a Git, los desarrolladores pueden guardar diferentes versiones de sus archivos, volver a estados anteriores, trabajar en ramas diferentes y controlar la evolución de un proyecto.
GitHub: es una plataforma online que utiliza Git para almacenar y compartir repositorios en Internet. Permite trabajar en equipo, guardar copias de seguridad de los proyectos, revisar cambios realizados por otros usuarios y colaborar en el desarrollo de software.

En resumen, Git es la herramienta que controla las versiones de un proyecto, mientras que GitHub es un servicio web donde se pueden alojar y compartir esos proyectos utilizando Git.

Instalación y configuración de Git

Para empezar a utilizar Git, primero es necesario instalarlo en el equipo. Una vez instalado, se recomienda realizar una configuración inicial indicando la identidad del usuario que aparecerá asociada a los cambios realizados en los proyectos.

Los dos comandos principales son:

git config --global user.name
Permite establecer el nombre del usuario que aparecerá en los registros de Git.
git config --global user.email
Sirve para configurar el correo electrónico asociado a la cuenta de Git. Normalmente se utiliza el mismo correo que está vinculado a la cuenta de GitHub.

Los comandos básicos de Git permiten crear un repositorio, controlar los cambios realizados en los archivos y guardar diferentes versiones de un proyecto. Son las herramientas principales para trabajar con el control de versiones.

git init (Inicializar): crea un nuevo repositorio Git en una carpeta determinada. A partir de ese momento, Git comienza a registrar los cambios realizados en los archivos del proyecto.
git status (Estado): muestra información sobre el estado actual del repositorio. Permite saber qué archivos han sido modificados, cuáles están preparados para guardarse y si existen cambios pendientes de registrar.
git add (Añadir): prepara los archivos para ser incluidos en el próximo guardado de cambios. Este paso se conoce como añadir archivos al área de preparación (staging area). Por ejemplo, git add archivo.txt añade un archivo concreto, mientras que git add . añade todos los cambios realizados.
git commit (Confirmar cambios): guarda de forma permanente los cambios que estaban preparados con git add. Cada commit representa una versión del proyecto en un momento concreto y suele incluir un mensaje que explica qué se ha modificado.
git log (Historial): muestra el historial de commits realizados en el repositorio. Permite consultar qué cambios se han guardado, cuándo se hicieron y quién los realizó.
git revert (Revertir): crea un nuevo commit que deshace los cambios realizados en otro commit anterior. Es una forma segura de volver atrás sin eliminar el historial del proyecto.

Las ramas (branches) y otras herramientas de Git permiten trabajar de forma más organizada, especialmente cuando un proyecto tiene varias funcionalidades en desarrollo o participan varios usuarios.

git branch (Rama): permite crear, mostrar o gestionar ramas dentro de un repositorio. Una rama es una línea independiente de desarrollo que permite realizar cambios sin afectar al código principal. Por ejemplo, se puede crear una rama para desarrollar una nueva función y mantener la versión estable separada.
git checkout -b (Crear y cambiar de rama): sirve para crear una nueva rama y cambiar automáticamente a ella en un solo paso. Es muy utilizado cuando se empieza a trabajar en una nueva característica o modificación. Por ejemplo:
git checkout -b nueva-funcionalidad
git merge (Fusionar ramas): permite unir los cambios de una rama con otra. Normalmente se utiliza para incorporar una funcionalidad terminada a la rama principal del proyecto.
git stash (Guardar cambios temporalmente): permite guardar modificaciones que todavía no están listas para hacer un commit y retirarlas temporalmente del área de trabajo. Es útil cuando se necesita cambiar de rama rápidamente sin perder los cambios actuales. Más adelante, esos cambios pueden recuperarse.
.gitignore (Ignorar archivos): es un archivo de configuración que indica a Git qué archivos o carpetas no deben ser incluidos en el control de versiones. Se suele utilizar para evitar subir archivos temporales, configuraciones privadas, archivos generados automáticamente o dependencias que no son necesarias en el repositorio.

GitHub es una plataforma que permite alojar repositorios de Git en Internet y facilita la colaboración entre diferentes personas en un mismo proyecto. A través de GitHub se pueden compartir cambios, revisar código y trabajar de manera organizada utilizando repositorios remotos.

Repositorio remoto: es una copia de un proyecto almacenada en un servidor online, como GitHub. Permite guardar el código fuera del ordenador local y sincronizar los cambios con otros colaboradores.
git push (Subir cambios): se utiliza para enviar los commits realizados en el repositorio local hacia el repositorio remoto en GitHub. De esta forma, los cambios quedan almacenados en la plataforma y pueden ser vistos por otros usuarios.
git pull (Actualizar cambios): permite descargar los cambios que existen en el repositorio remoto y combinarlos con la versión local. Se suele utilizar antes de comenzar a trabajar para tener la versión más reciente del proyecto.
git clone (Clonar repositorio): crea una copia completa de un repositorio remoto en el ordenador. Permite descargar un proyecto existente desde GitHub para poder modificarlo o trabajar con él localmente.
fork (Bifurcación): consiste en crear una copia de un repositorio de otro usuario dentro de la propia cuenta de GitHub. Se utiliza principalmente cuando se quiere modificar un proyecto sin afectar al repositorio original o cuando se desea colaborar en proyectos externos.
Pull Request (PR): es una solicitud para incorporar cambios de una rama o repositorio a otro. Permite que otros miembros del equipo revisen el código, hagan comentarios y aprueben las modificaciones antes de integrarlas en el proyecto principal.
Resolución de conflictos

Un conflicto en Git aparece cuando dos cambios diferentes afectan a la misma parte de un archivo y Git no puede decidir automáticamente cuál debe conservar. Esto suele ocurrir cuando varias personas modifican la misma línea de código o cuando una rama tiene cambios diferentes a otra.

Para resolver un conflicto, normalmente se siguen estos pasos:

Identificar los archivos con conflictos mediante git status.
Abrir los archivos afectados y revisar las diferencias marcadas por Git.
Elegir qué cambios conservar o combinar manualmente.
Guardar los archivos corregidos.
Añadir los cambios con git add.
Crear un nuevo commit para finalizar la resolución.

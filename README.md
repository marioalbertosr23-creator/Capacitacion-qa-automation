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



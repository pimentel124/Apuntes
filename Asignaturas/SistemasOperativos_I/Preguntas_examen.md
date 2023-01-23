---
title: Preguntas examen Sistemas Operativos 1
description: Recopilación Preguntas resueltas examen Sistemas Operativos 1
layout: ../../../layouts/MainLayout.astro
---

- [Preguntas examen Sistemas Operativos 1](#preguntas-examen-sistemas-operativos-1)
  - [Tema 1](#tema-1)
    - [Qué conducta, en las Interrupciones Múltiples, es más eficiente?](#qué-conducta-en-las-interrupciones-múltiples-es-más-eficiente)
    - [Cuáles son las características fundamentales de una Memoria?](#cuáles-son-las-características-fundamentales-de-una-memoria)
    - [Sobre la Memoria Caché, cuál de estas afirmaciones es cierta?](#sobre-la-memoria-caché-cuál-de-estas-afirmaciones-es-cierta)
    - [Cuándo puede ocurrir un error en una lista Pila?](#cuándo-puede-ocurrir-un-error-en-una-lista-pila)
    - [El Ciclo de Instrucción con Interrupciones](#el-ciclo-de-instrucción-con-interrupciones)
    - [¿Cuál de estos métodos de E/S es el más eficiente para sistemas de multiprogramación?](#cuál-de-estos-métodos-de-es-es-el-más-eficiente-para-sistemas-de-multiprogramación)
    - [A medida que se desciende en la jerarquía de memoria](#a-medida-que-se-desciende-en-la-jerarquía-de-memoria)
    - [¿Cuáles de estos son registros visibles para el usuario?](#cuáles-de-estos-son-registros-visibles-para-el-usuario)
    - [Relacionado con DMA, cuál de estas sentencias es verdadera](#relacionado-con-dma-cuál-de-estas-sentencias-es-verdadera)
    - [¿Cuál de estas opciones es una estrategia para implementar múltiples instrucciones?](#cuál-de-estas-opciones-es-una-estrategia-para-implementar-múltiples-instrucciones)
    - [¿Cuál de estas opciones no es una técnica de comunicación de E/S?](#cuál-de-estas-opciones-no-es-una-técnica-de-comunicación-de-es)
    - [Relacionado con la jerarquía de memoria, cuál de estas sentencias es falsa?](#relacionado-con-la-jerarquía-de-memoria-cuál-de-estas-sentencias-es-falsa)
  - [Tema 2](#tema-2)
    - [¿Cuáles eran los principales problemas de las máquinas previas a los Sistemas Operativos (aquellas que utilizaban procesos en serie)?](#cuáles-eran-los-principales-problemas-de-las-máquinas-previas-a-los-sistemas-operativos-aquellas-que-utilizaban-procesos-en-serie)
    - [¿Cuáles son los posibles problemas de los procesos?](#cuáles-son-los-posibles-problemas-de-los-procesos)
    - [¿Que es la memoria virtual?](#que-es-la-memoria-virtual)
    - [¿Cómo funcionan los sistemas en lotes multiprogramados o multitarea?](#cómo-funcionan-los-sistemas-en-lotes-multiprogramados-o-multitarea)
    - [Además de la estrategia round-robin, que otra estrategia puede seguir el dispatcher a la hora de elegir un proceso que se encuentra en la cola a corto plazo?](#además-de-la-estrategia-round-robin-que-otra-estrategia-puede-seguir-el-dispatcher-a-la-hora-de-elegir-un-proceso-que-se-encuentra-en-la-cola-a-corto-plazo)
    - [Que significa el termino simétrico en la técnica de multiprocesamiento simétrico (SMP)?](#que-significa-el-termino-simétrico-en-la-técnica-de-multiprocesamiento-simétrico-smp)
    - [En que cuatro categorías se pueden agrupar de forma genérica el trabajo en seguridad y protección relacionado con los sistemas operativos?](#en-que-cuatro-categorías-se-pueden-agrupar-de-forma-genérica-el-trabajo-en-seguridad-y-protección-relacionado-con-los-sistemas-operativos)
    - [En multiprogramación, en que consiste la técnica de tiempo compartido?](#en-multiprogramación-en-que-consiste-la-técnica-de-tiempo-compartido)
    - [Un S.O. Importante evolucionará en el tiempo por](#un-so-importante-evolucionará-en-el-tiempo-por)
    - [Sobre instrucciones privilegiadas en sistemas de lotes sencillos](#sobre-instrucciones-privilegiadas-en-sistemas-de-lotes-sencillos)
    - [Algunas de las responsabilidades del S.O. para garantizar un control eficiente y ordenado de asignación de recursos en un entorno de computación que permita programación modular y uso flexible de datos son](#algunas-de-las-responsabilidades-del-so-para-garantizar-un-control-eficiente-y-ordenado-de-asignación-de-recursos-en-un-entorno-de-computación-que-permita-programación-modular-y-uso-flexible-de-datos-son)
    - [Las capas de un sistema de computación en orden de la superior a la más baja son](#las-capas-de-un-sistema-de-computación-en-orden-de-la-superior-a-la-más-baja-son)
  - [Tema 3](#tema-3)
    - [Un proceso, mientras esté ejecutándose, en cualquier instante puede caracterizar por una serie de elementos que pueden ser](#un-proceso-mientras-esté-ejecutándose-en-cualquier-instante-puede-caracterizar-por-una-serie-de-elementos-que-pueden-ser)
    - [Una razón por la cual se termina un proceso puede ser](#una-razón-por-la-cual-se-termina-un-proceso-puede-ser)
    - [Para que el sistema operativo pueda manejar un proceso](#para-que-el-sistema-operativo-pueda-manejar-un-proceso)
    - [Cuando se crea un proceso para con el siguiente órden](#cuando-se-crea-un-proceso-para-con-el-siguiente-órden)
    - [¿Cual de las siguientes no es una característica de los procesos suspendidos?](#cual-de-las-siguientes-no-es-una-característica-de-los-procesos-suspendidos)
    - [¿Que significa la expulsión de un proceso?](#que-significa-la-expulsión-de-un-proceso)
    - [¿Cual de estas no es una categoría general de información que hay en el bloque de control de proceso?](#cual-de-estas-no-es-una-categoría-general-de-información-que-hay-en-el-bloque-de-control-de-proceso)
    - [¿Cual de los siguientes no es uno de los pasos que realiza el S.O. para la creación de un proceso?](#cual-de-los-siguientes-no-es-uno-de-los-pasos-que-realiza-el-so-para-la-creación-de-un-proceso)
    - [En los cambios de proceso](#en-los-cambios-de-proceso)
    - [Los pasos a seguir para cambiar el estado de un proceso son](#los-pasos-a-seguir-para-cambiar-el-estado-de-un-proceso-son)
    - [En una interrupción de reloj](#en-una-interrupción-de-reloj)
    - [Al crear un proceso. ¿Cual de estas opciones no es correcta?](#al-crear-un-proceso-cual-de-estas-opciones-no-es-correcta)
  - [Tema 4](#tema-4)
    - [Qué es un hilo?](#qué-es-un-hilo)
    - [Principales estados de los hilos](#principales-estados-de-los-hilos)
    - [Cuantas operaciones básicas relacionadas con los hilos están relacionadas con el cambio de estado del hilo](#cuantas-operaciones-básicas-relacionadas-con-los-hilos-están-relacionadas-con-el-cambio-de-estado-del-hilo)
    - [Características para el diseño de sistemas operativos multiprocesador](#características-para-el-diseño-de-sistemas-operativos-multiprocesador)
    - [Dentro de un proceso puede haber uno o más hilos cada uno con](#dentro-de-un-proceso-puede-haber-uno-o-más-hilos-cada-uno-con)
    - [Cual de estos es un beneficio de la organización micronúcleo](#cual-de-estos-es-un-beneficio-de-la-organización-micronúcleo)
    - [Los hilos a nivel de usuario (ULT)](#los-hilos-a-nivel-de-usuario-ult)
    - [Los hilos a nivel de núcleo (KLT)](#los-hilos-a-nivel-de-núcleo-klt)
    - [Sobre la arquitectura micronúcleo](#sobre-la-arquitectura-micronúcleo)
    - [En un modelo de proceso multihilo](#en-un-modelo-de-proceso-multihilo)
    - [A que se refiere el concepto multihilo](#a-que-se-refiere-el-concepto-multihilo)
    - [Que permite la arquitectura micronúcleo sobre la gestión de E/S e interrupciones](#que-permite-la-arquitectura-micronúcleo-sobre-la-gestión-de-es-e-interrupciones)
  - [Tema 5](#tema-5)
    - [Los temas centrales del diseño de sistemas operativos, relacionados con la gestión de procesos e hilos son](#los-temas-centrales-del-diseño-de-sistemas-operativos-relacionados-con-la-gestión-de-procesos-e-hilos-son)
    - [Señala la opción falsa](#señala-la-opción-falsa)
    - [Indica cuál de éstas definiciones corresponde con el término de interbloqueo](#indica-cuál-de-éstas-definiciones-corresponde-con-el-término-de-interbloqueo)
    - [Indica cuál no es un requisito para la exclusión mutua](#indica-cuál-no-es-un-requisito-para-la-exclusión-mutua)
    - [Indica cuál es una desventaja del uso de una instrucción máquina especial para conseguir exclusión mutua](#indica-cuál-es-una-desventaja-del-uso-de-una-instrucción-máquina-especial-para-conseguir-exclusión-mutua)
    - [¿Cual es el principio fundamental del semáforo?](#cual-es-el-principio-fundamental-del-semáforo)
    - [¿Que hace un semWait y un semSignal?](#que-hace-un-semwait-y-un-semsignal)
    - [¿Si tenemos tres procesos usando un recurso(contador semáforo está = -2) y un proceso sale y hace un semSignal (contador semáforo = -1), y tenemos varios procesos en la cola de bloqueados del semáforo, como y cuando pueden entrar a usar el recurso que han dejado disponible?](#si-tenemos-tres-procesos-usando-un-recursocontador-semáforo-está---2-y-un-proceso-sale-y-hace-un-semsignal-contador-semáforo---1-y-tenemos-varios-procesos-en-la-cola-de-bloqueados-del-semáforo-como-y-cuando-pueden-entrar-a-usar-el-recurso-que-han-dejado-disponible)
    - [¿Cual es la diferencia entre un semáforo fuerte y uno debil?](#cual-es-la-diferencia-entre-un-semáforo-fuerte-y-uno-debil)
    - [¿Como actua el semáforo, para solucionar el problema del productor/consumidor?](#como-actua-el-semáforo-para-solucionar-el-problema-del-productorconsumidor)
    - [Cómo hace un programa para entrar en el monitor?](#cómo-hace-un-programa-para-entrar-en-el-monitor)
    - [Como se consigue la sincronización entre procesos usando un monitor, es decir cómo puede informar a otro proceso bloqueado que un recurso está disponible?](#como-se-consigue-la-sincronización-entre-procesos-usando-un-monitor-es-decir-cómo-puede-informar-a-otro-proceso-bloqueado-que-un-recurso-está-disponible)
    - [En el caso de semáforos para asegurar exclusión mutua sobre varios recursos se necesitan tantos como recursos se quieran proteger. En el caso de un monitor cómo se consigue?](#en-el-caso-de-semáforos-para-asegurar-exclusión-mutua-sobre-varios-recursos-se-necesitan-tantos-como-recursos-se-quieran-proteger-en-el-caso-de-un-monitor-cómo-se-consigue)
    - [Que sucede cuando un proceso que está dentro del monitor ejecuta un signal sobre una variable condicional](#que-sucede-cuando-un-proceso-que-está-dentro-del-monitor-ejecuta-un-signal-sobre-una-variable-condicional)
    - [Con qué implementación de paso de mensajes no tienen que esperar el emisor ni el receptor?](#con-qué-implementación-de-paso-de-mensajes-no-tienen-que-esperar-el-emisor-ni-el-receptor)
    - [En qué tipo de direccionamiento en los mensajes entre procesos se refiere al mailbox como port?](#en-qué-tipo-de-direccionamiento-en-los-mensajes-entre-procesos-se-refiere-al-mailbox-como-port)
    - [Una forma de implementar la cola de mensajes es con un FIFO, pero si algunos mensajes pueden ser más urgentes que otros una opción es](#una-forma-de-implementar-la-cola-de-mensajes-es-con-un-fifo-pero-si-algunos-mensajes-pueden-ser-más-urgentes-que-otros-una-opción-es)
    - [Cuál de los siguientes elementos NO se encuentra en la cabecera un mensaje típico](#cuál-de-los-siguientes-elementos-no-se-encuentra-en-la-cabecera-un-mensaje-típico)
  - [Tema 6](#tema-6)
    - [En qué categorias se pueden dividir los recursos?](#en-qué-categorias-se-pueden-dividir-los-recursos)
    - [De las listas siguientes, en cual de ellas todos los recursos son reutilizables?](#de-las-listas-siguientes-en-cual-de-ellas-todos-los-recursos-son-reutilizables)
    - [Cuales son los métodos generales para hacer frente al interbloqueo?](#cuales-son-los-métodos-generales-para-hacer-frente-al-interbloqueo)
    - [Señala que opción es correcta](#señala-que-opción-es-correcta)
    - [Cual de las siguientes afirmaciones es falsa?](#cual-de-las-siguientes-afirmaciones-es-falsa)
    - [En qué consiste la prevencion del interbloqueo?](#en-qué-consiste-la-prevencion-del-interbloqueo)
    - [Que tipos de tuberias existen en UNIX?](#que-tipos-de-tuberias-existen-en-unix)
    - [De cuales de los siguientes elementos no consta un semáforo?](#de-cuales-de-los-siguientes-elementos-no-consta-un-semáforo)
    - [Qué condiciones debe haber para que, siempre, se produzca un interbloqueo?](#qué-condiciones-debe-haber-para-que-siempre-se-produzca-un-interbloqueo)
    - [Cual de las siguientes afirmaciones sobre las tuberías es falsa?](#cual-de-las-siguientes-afirmaciones-sobre-las-tuberías-es-falsa)
    - [Cual de los siguientes tipos de semaforos no existe?](#cual-de-los-siguientes-tipos-de-semaforos-no-existe)
    - [Elije la opción correcta](#elije-la-opción-correcta)

# Preguntas examen Sistemas Operativos 1

## Tema 1

#### Qué conducta, en las Interrupciones Múltiples, es más eficiente?

a) Cuando se recibe una interrupción se para completamente el proceso actual y se procesa la Interrupción.  
<u>b) Cuando se recibe una interrupción más prioritaria que el proceso actual, se para el proceso y se sigue con la Interrupción.</u>  
c) Se deja en espera la Interrupción hasta que se haya acabado el proceso actual.  
d) Ningún caso anterior es cierto.  

#### Cuáles son las características fundamentales de una Memoria?

<u>a) Cantidad, Velocidad y Coste.</u>  
b) Coste, Tipo (HD o Flash), Cantidad.  
c) Cantidad.  
d) Ninguna de las anteriores es cierta.  

#### Sobre la Memoria Caché, cuál de estas afirmaciones es cierta?

a) La Memoria Caché es una memoria barata, de tipo RAM.  
b) Es un dispositivo de memoria muy rápido que es usado por la CPU, donde se carga parte del código que se va a ejecutar.  
c) Puede ser una parte reservada de la Memoria Principal.  
<u>d) B y C son correctas.</u>  

#### Cuándo puede ocurrir un error en una lista Pila?

a) Cuando intentemos sacar la cima de la Pila.  
b) Cuando intentemos meter un elemento en el Fondo de la Pila en una Pila Vacía.  
<u>c) Cuando intentemos meter un elemento en una Pila Llena.</u>  
d) Cuando intentemos sacar un elemento del Fondo de la Pila.  

#### El Ciclo de Instrucción con Interrupciones

a) Se realiza íntegramente por el hardware del ordenador.  
b) Consta de dos Fases.  
<u>c) Consta de tres Fases.</u>
d) Ninguna de las anteriores.  

#### ¿Cuál de estos métodos de E/S es el más eficiente para sistemas de multiprogramación?

<u>a) DMA.</u>  
b) Basado en interrupciones.  
c) Programada.  
d) Polling.  

La DMA es la más eficiente porque transfiere bloques de datos, palabra a palabra, hacia/desde la memoria sin pasar por el procesador (involucrado solamente al principio y al final de la transferencia)  

#### A medida que se desciende en la jerarquía de memoria

a) Aumenta el coste por bit.  
<u>b) Aumenta el tiempo de acceso.</u>  
c) Disminuye la capacidad.  
d) Ninguna de las anteriores.  

Cuanto mayor es la capacidad de la memoria (más abajo de la jerarquía se encuentra). Por esto, la velocidad de acceso es menor y por lo tanto, el tiempo de acceso es mayor.

#### ¿Cuáles de estos son registros visibles para el usuario?

a) Puntero de Pila, Registro de Instrucción y Puntero de Segmento.  
b) Registro de instrucción, Contador de Programa y Puntero de Pila.  
c) Registro Índice, Puntero de Segmento y Registro de Instrucción.  
<u>d) Puntero de Pila, Registro Índice y Puntero de Segmento.</u>  

Los registros visibles por el usuario son los Registros de Datos, el Registro Índice, el Puntero de Segmento y el Puntero de Pila. Algunos otros, como el Contador de Programa o el Registro de Instrucción son registros de control que solo son visibles por el programador.

#### Relacionado con DMA, cuál de estas sentencias es verdadera

a) La tasa de Transferencia de E/S no está limitada por la velocidad con la que el procesador puede comprobar el estado de un dispositivo y ofrecerle un servicio.  
b) El procesador puede no estar involucrado en la gestión de E/S.  
<u>c) Se deben ejecutar varias instrucciones para cada transferencia de E/S.</u>  
d) Ninguna es correcta.  

Para una transferencia de E/S, se necesitan algunas instrucciones, como lo que se desea leer o escribir, entre otras.  

#### ¿Cuál de estas opciones es una estrategia para implementar múltiples instrucciones?

a) Utilizar contadores.  
<u>b) Establecer prioridades.</u>  
c) Semáforos  
d) Ninguna de las anteriores.  

Las estrategias para implementar múltiples instrucciones son por Prioridades o por Interrupciones.

#### ¿Cuál de estas opciones no es una técnica de comunicación de E/S?

a) Programada.  
b) Dirigida por Interruciones.  
<u>c) Semáforos.</u>  
d) DMA.  

El uso de semáforos no es una técnica de comunicación de E/S, sino de uso de los recursos del sistema.

#### Relacionado con la jerarquía de memoria, cuál de estas sentencias es falsa?

a) A menor tiempo de acceso, mayor coste por bit.  
b) A mayor capacidad, menor coste por bit.  
c) A mayor capacidad, menor velocidad de acceso.  
<u>d) A menor tiempo de acceso, menor velocidad de acceso.</u>  

Si se reduce el tiempo de acceso, al ser inversamente proporcional a la velocidad de acceso, esta última aumentaría.

## Tema 2

#### ¿Cuáles eran los principales problemas de las máquinas previas a los Sistemas Operativos (aquellas que utilizaban procesos en serie)?

a) Planificación y salida en la impresora.  
b) Programación a nivel físico y coste.  
<u>c) Planificación y tiempo de configuración.</u>  
d) Tiempo de configuración y dificultad de localizar los errores.  

Planificación: muy frecuente malgastar tiempo de procesamiento del computador.  
Tiempo de configuración: carga en memoria del compilador, lenguaje de alto nivel del programa, enlace al programa objeto y funciones comunes; todo a base de montar y desmontar cintas en el computador.

#### ¿Cuáles son los posibles problemas de los procesos?

a) Inanición, sincronización incorrecta e interbloqueo.  
<u>b) Sincronización incorrecta, violación de la exclusión mutua, funcionamiento no determinista e interbloqueo.</u>  
c) Violación de la exclusión mutua y no ejecución.  
d) Sincronización incorrecta, funcionamiento determinista e interbloqueo.  

La respuesta A no puede ser porque la inanición no es un problema por si solo, sino que viene dentro de la violación de la exclusión mutua.  
La respuesta C no puede ser porque es incompleta i, además, la no ejecución es inanición y se da el mismo caso que en la respuesta A.  
La respuesta D no puede ser porque que un proceso funcione de manera determinista no es un problema, es correcto.  

#### ¿Que es la memoria virtual?

<u>a) Es un mecanismo accesible para todos los procesos que permite direccionar memoria sin importar la cantidad de memoria física.</u>  
b) El conjunto de la memoria secundaria y la memora auxiliar.  
c) Memoria de procesos subdividida en páginas en las que el acceso a estas no es transparente para el programador.  
d) Es un concepto prácticamente inédito sobre el que se esta investigando.  

La respuesta B no puede ser porque la memoria virtual no es el conjunto de esas memorias.  
La respuesta C no puede ser porque el acceso a las páginas SI es transparente para el programador.  
La respuesta D no puede ser porque la memoria virtual se utiliza desde hace tiempo.  

#### ¿Cómo funcionan los sistemas en lotes multiprogramados o multitarea?

a) Bloquea cualquier ejecución menos la del programa que esta ejecutándose hasta que este acabe.  
<u>b) Permite la ejecución de diversos programas a la vez (ejecución en paralelo), mejorando la eficiencia al ejecutar un programa durante el tiempo de espera de otro.</u>  
c) Permite la ejecución de programas en serie, uno detrás de otro.  
d) Permite la ejecución de hasta dos programas en paralelo.  

La respuesta A no puede ser porque la multitarea no bloquea al resto de programas.  
La respuesta C no puede ser porque la multitarea ejecuta los procesos en paralelo.  
La respuesta D no puede ser porque permite la ejecución de más de dos programas en paralelo.  

#### Además de la estrategia round-robin, que otra estrategia puede seguir el dispatcher a la hora de elegir un proceso que se encuentra en la cola a corto plazo?

a) FILO. El primero que ha entrado en la cola sera el último en salir de ella.  
<u>b) Asignar niveles de prioridad.</u>  
c) Ninguna es correcta.  
d) LIFO. El último en entrar en la cola sera el primero en salir.  

La estrategia común del dispatcher (o planificador) es la técnica conocida como roundrobin o turno rotatorio; pero además de esta, hay otra estrategia que consiste en asignar niveles de prioridad a los distintos procesos, siendo el planificador el encargado de elegir los procesos en el orden de prioridad.

#### Que significa el termino simétrico en la técnica de multiprocesamiento simétrico (SMP)?

a) Que el computador tiene un número par de procesadores.  
b) Que cada proceso está formado por dos únicos hilos.  
<u>c) Que todos los procesadores pueden realizar las mismas funciones.</u>  
d) Todas las opciones anteriores son ciertas.  

Una de las características del SMP y que además da el nombre de simétrico, es que todos los procesadores pueden realizar las mismas funciones, es decir, que todos los procesadores comparten el acceso a memoria.

#### En que cuatro categorías se pueden agrupar de forma genérica el trabajo en seguridad y protección relacionado con los sistemas operativos?

a) Disponibilidad, confidencialidad, integridad de los datos y autenticidad.  
b) Confidencialidad, unicidad, autenticidad y soporte a la programación modular.  
c) Disponibilidad, integridad de los datos, unicidad y eficiencia.  
d) Unicidad, disponibilidad, integridad de los datos y seguridad.  

La mayoría del trabajo en seguridad y protección relacionado con los sistemas operativos se puede agrupar de forma genérica en cuatro categorías: Disponibilidad, Confidencialidad, Integridad de los datos y Autenticidad.

#### En multiprogramación, en que consiste la técnica de tiempo compartido?

a) En compartir el tiempo de procesador entre múltiples procesos.  
<u>b) En compartir el tiempo de procesador entre múltiples usuarios.</u>  
c) En compartir el tiempo de procesador entre todos los recursos.  
d) Ninguna de las anteriores es correcta.  
La multiprogramación también se puede utilizar para gestionar múltiples trabajos interactivos, en este caso, la técnica se denomina tiempo compartido, porque comparte el tiempo de procesador entre múltiples usuarios  

#### Un S.O. Importante evolucionará en el tiempo por

a) Resolución de fallos.  
b) Actualizaciones del hardware.  
<u>c) Todas son correctas.</u>  
d) Nuevos servicios.  
c) Todas son correctas.  

Son las tres razones de la evolucion de los sistemas operativos importantes.  

#### Sobre instrucciones privilegiadas en sistemas de lotes sencillos

a) Solamente pueden ser ejecutadas en modo de “SuperUsuario”.  
b) Son ejecutadas directamente por el monitor.  
<u>c) Permite que un programa de usuario realice operaciones de E/S.</u>  
d) Ninguna es correcta.  
c) Sabiendo que las instrucciones de E/S son privilegiadas y deben ser ejecutadas por el monitor, si el programa de usuario desea realizar operaciones de E/S, debe solicitar al monitor que realice las operaciones por él.  

B → NO, son ejecutadas por el programa usuario y cuando ven que son instrucciones privilegiadas mediante un error se transfiere la instrucción al monitor.

#### Algunas de las responsabilidades del S.O. para garantizar un control eficiente y ordenado de asignación de recursos en un entorno de computación que permita programación modular y uso flexible de datos son

a) Soporte a la programación modular.  
<u>b) Todas son correctas.</u>  
c) Aislamiento de procesos.  
d) Almacenamiento a largo plazo.  
b) Son tres de las cinco responsabilidades estudiadas.  

#### Las capas de un sistema de computación en orden de la superior a la más baja son

a) Utilidades, Sistema Operativo, Hardware del computador.  
b) Utilidades, Firmware, Sistema Operativo, Hardware del computador.  
c) Utilidades, Programas de aplicación, Sistema Operativo, Hardware del computador.  
<u>d) Programas de aplicación, Utilidades, Sistema Operativo, Hardware del computador.</u>  

## Tema 3

#### Un proceso, mientras esté ejecutándose, en cualquier instante puede caracterizar por una serie de elementos que pueden ser

a) Identificador, Estado, Prioridad y número de líneas de código.  
b) Identificador, Estado, Ubicación en el sistema, Permisos de ejecución.  
<u>c) Identificador, Prioridad, Datos de contexto y información de estado de E/S</u>  
d) Nombre, Identificador, Prioridad y contador de programa.  

#### Una razón por la cual se termina un proceso puede ser

a) Por exceder un tiempo límite.  
b) Que el sistema no disponga de suficiente memoria.  
c) Porque el proceso padre decide finalizarlo.  
<u>d) Todas las anteriores son correctas.</u>  

#### Para que el sistema operativo pueda manejar un proceso

<u>a) Necesita muchísima información del proceso.</u>  
b) Es suficiente con el ID, los registros y el puntero de la pila.  
c) Es suficiente con el ID y la información de estado del procesador.  
d) El SO puede acceder a todos los datos necesarios a través del ID.  

#### Cuando se crea un proceso para con el siguiente órden

a) Reservar memoria, asignar un ID, inicializar el BCP y ejecutarlo.  
<u>b) Asignar un ID, reservar memoria, inicializar el BCP, establecer los enlaces y creación de estructura de datos.</u>  
c) Reservar memoria, asignar un ID, inicializar BCP, inicializar enlaces y expandir otras estructuras de datos.  
d) Reservar memoria, asignar un ID, establecer enlaces, inicializaciones y ejecución.  

#### ¿Cual de las siguientes no es una característica de los procesos suspendidos?

a) El proceso no está inmediatamente disponible para su ejecución.  
b) El proceso puede estar o no a la espera de un evento.  
<u>c) El proceso siempre estará disponible una vez pasado un determinado tiempo.</u>  
d) El proceso no puede ser recuperado de este estado hasta que el agente explícitamente así lo indique.  

La respuesta correcta es la “c”, ya que si el agente no indica lo contrario, un proceso puede estar suspendido durante un tiempo indefinido.

#### ¿Que significa la expulsión de un proceso?

a) Un proceso es expulsado cuando ha finalizado.  
<u>b) Un proceso es expulsado cuando estando en ejecución es sustituido por otro que estaba bloqueado, el cual es de prioridad superior, cuando se produce el evento esperado.</u>  
c) Un proceso es expulsado cuando estando en ejecución es sustituido por otro.  
d) Es cuando se finaliza un proceso debido a un exceso de procesos.  

La respuesta “b” es la correcta, ya que es la definición completa de proceso expulsado.

#### ¿Cual de estas no es una categoría general de información que hay en el bloque de control de proceso?

a) Identificación del proceso.  
b) Información de estado del procesador.  
<u>c) Identificación del procesador.</u>  
d) Información de control del proceso.  

La respuesta “c” es la correcta ya que no existe en un bloque de control de proceso.

#### ¿Cual de los siguientes no es uno de los pasos que realiza el S.O. para la creación de un proceso?

<u>a) Eliminar algún proceso suspendido.</u>  
b) Reservar espacio para el proceso.  
c) Inicializar el bloque de control del proceso.  
d) Establecer los enlaces apropiados.  

No es necesario eliminar ningún otro proceso para crear uno nuevo, por lo tanto la
respuesta correcta es la “a”.

#### En los cambios de proceso

a) La interrupción y el cepo son lo mismo.  
b) El cepo es originado por un proceso externo e independiente.  
c) El cepo es generado por una excepción de un proceso externo e independiente.  
<u>d) La interrupción es generada por un proceso externo e independiente, como por ejemplo la culminación de una operación E/S</u>  

El cepo es generado por una excepción sólo del proceso en curso, las interrupciones siempre son generadas por procesos externos.

#### Los pasos a seguir para cambiar el estado de un proceso son

a) Salvar contexto del procesador, seleccionar otro proceso para ejecución, restaurar el contexto del procesador.  
<u>b) Salvar contexto del procesador, actualizar el bloque de control del proceso, mover bloque de control del proceso a la cola apropiada, seleccionar otro proceso para ejecución, actualizar el bloque de control del proceso seleccionado, actualizar el bloque de estructuras de datos de gestión de memoria y restaurar el contexto del procesador</u>  
c) No existen unos pasos predefinidos.  
d) Seleccionar otro proceso para ejecución, restaurar el contexto del procesador.  

#### En una interrupción de reloj

a) El sistema operativo determina exactamente que se ha producido una acción de E/S.  
<u>b) El sistema operativo determina si el proceso que está en ejecución ha estado ejecutando durante la fracción máxima de tiempo permitida.</u>  
c) El proceso genera la interrupción porque ha acabado.  
d) El sistema operativo determina que se ha producido un error.  

Como su nombre indica, esta interrupción es en relación al tiempo asignado al proceso.

#### Al crear un proceso. ¿Cual de estas opciones no es correcta?

a) Se debe asignar espacio para el proceso.  
b) Se deben establecer los enlaces apropiados.  
c) Puede haber otras estructuras de datos que crear o ampliar.  
<u>d) Hay que asignar cualquier identificador al proceso.</u>  

El identificador debe ser único

## Tema 4

#### Qué es un hilo?

a) Un proceso.  
<u>b) Conjunto de instrucciones de un proceso.</u>  
c) La primera instrucción de un programa.  
d) Todas las anteriores son correctas.  

Por definición  

#### Principales estados de los hilos

a) Creado, Bloqueado, Desbloqueado  
b) Listo, Bloqueado, Finalizado  
<u>c) Ejecutando, Listo, Bloqueado</u>  
d) Creado, Finalizado  

Las otras contienen operaciones del estado de un hilo.  

#### Cuantas operaciones básicas relacionadas con los hilos están relacionadas con el cambio de estado del hilo

a) 2  
b) 3  
<u>c) 4</u>  
d) 5  

Creación, Bloqueo, Desbloqueo, Finalización.  

#### Características para el diseño de sistemas operativos multiprocesador

<u>a) Procesos simultáneos concurrentes, posibilidad de planificar múltiples hilos del mismo proceso simultáneamente en múltiples procesadores, el sistema operativo no debe degradarse en caso de fallo de un procesador.</u>  
b) El mismo hilo se ejecuta simultáneamente en múltiples procesadores usando el sistema el de tiempo más reducido.  
c) Todos los procesos de núcleo se ejecutan en un procesador y los de usuario en otro.  
d) Todas las respuestas son correctas  

#### Dentro de un proceso puede haber uno o más hilos cada uno con

a) Estado de ejecución, contexto del procesador, pila de ejecució, acceso a memoria y recursos del proceso  
b) Estado de ejecución, contexto del procesador y pila de ejcución  
c) Contexto del procesador, pila de ejecución y espacio para variables locales.  
<u>d) Estado de ejecución, contexto del procesador, pila de ejecución, espacio para variables, acceso a memoria y recursos del proceso.</u>  

Las otras son incompletas  

#### Cual de estos es un beneficio de la organización micronúcleo

a) Interfaces multiformes.  
<u>b) Flexibilidad.</u>  
c) Soporte de sistemas centralizados.  
d) Todas son incorrectas  

La b) es correcta porque las otras son beneficios negados.  

#### Los hilos a nivel de usuario (ULT)

a) El núcleo gestiona todo el trabajo de los hilos.  
b) Una aplicación empieza a la vez en múltiples hilos.  
c) a) y b) son correctas.  
<u>d) El núcleo no es consciente de la existencia de los hilos.</u>  

La a) es incorrecta porque el núcleo NO gestiona todo el trabajo de los hilos.  
La b) es incorrecta porque una aplicación empieza en un UNICO hilo.  

#### Los hilos a nivel de núcleo (KLT)

<u>a) Se pueden planificar simultáneamente múltiples hilos de un solo proceso en múltiples procesadores.</u>  
b) La aplicación gestiona todo el trabajo de los hilos.  
c) Se pueden ejecutar en cualquier sistema operativo.  
d) Pocas llamadas al sistema.  

La b) y la c) serian de ULT y en KLT se hacen muchas llamadas recursivas.

#### Sobre la arquitectura micronúcleo

a) Consiste en un núcleo por capas donde el núcleo controla todos los recursos.  
<u>b) El micronúcleo es la pequeña parte central del sistema operativo que proporciona las bases para extensiones modulares.</u>  
c) Tiene una estructura vertical.  
d) Los procesos necesitan diferenciar entre servicios a nivel de núcleo y a nivel de usuario.  

En la a) estaríamos hablando de arquitectura por capas, el micronúcleo tiene una estructura horizontal y no se necesitan diferenciar los servicios.

#### En un modelo de proceso multihilo

a) Mientras un proceso se ejecuta, los registros del procesador se controlan por este proceso.  
b) Cuando no se ejecuta el hilo se almacenan los registros.  
<u>c) El valor de los registros del hilo se almacenan en un BCP.</u>  
d) Ninguna de las anteriores es correcta.  

La a) y la b) corresponden al modelo monohilo.

#### A que se refiere el concepto multihilo

a) A la ejecución de un mismo hilo varias veces  
<u>b) Capacidad de un sistema operativo de dar soporte a múltiples hilos de ejecución en un solo proceso.</u>  
c) Capacidad de un sistema operativo de dar soporte a múltiples procesos de ejecución en un solo hilo.  
d) Ninguna de las anteriores es correcta.  

Definición de multihilo

#### Que permite la arquitectura micronúcleo sobre la gestión de E/S e interrupciones

<u>a) Manejar las interrupciones hardware como mensajes e incluir los puertos de E/S en los espacios de memoria</u>  
b) Manejar las interrupciones hardware y E/S como mensajes  
c) Manejar las interrupciones hardware y E/S como espacios de memoria  
d) Manejas las interrupciones hardware como espacios de memoria y los puertos E/S como mensajes  

Definición de gestión de E/S e interrupciones con arquitectura micronúcleo.

## Tema 5

#### Los temas centrales del diseño de sistemas operativos, relacionados con la gestión de procesos e hilos son

a) Paso de mensajes, proceso concurrente y recurso crítico.  
<u>b) Multiprocesamiento, multiprogramación y procesamiento distribuido.</u>  
c) Paso de mensajes, multiprocesamiento y recurso crítico.  
d) Multiprogramación, paso de mensajes y procesamiento distribuido.  

#### Señala la opción falsa

a) Podemos encontrar la concurrencia en múltiples aplicaciones, aplicaciones estructuradas y en la estructura del sistema operativo.  
b) La concurrencia abarca aspectos como la comunicación entre procesos y la compartición de recursos.  
c) La multiprogramación fue ideada para permitir compartir dinámicamente el tiempo de procesamiento entre varias aplicaciones activas.  
<u>d) Toda aplicación puede ser programada de manera eficaz como un conjunto de procesos concurrentes.</u>  

#### Indica cuál de éstas definiciones corresponde con el término de interbloqueo

a) Situación en la cual un proceso preparado para avanzar es soslayado indefinidamente por el planificador, aunque es capaz de avanzar, nunca se le escoge.  
b) Requisito de que cuando un proceso esté en una sección crítica que accede a recursos compartidos, ningún otro proceso pueda estar en una sección crítica que acceda a ninguno de estos recursos compartidos.  
<u>c) Situación en la cual dos o más procesos son incapaces de actuar porque cada uno está esperando que alguno de los otros haga algo.</u>  
d) Situación en la cual dos o más procesos cambian continuamente su estado en respuesta a cambios en los otros procesos, sin realizar ningún trabajo útil.  

#### Indica cuál no es un requisito para la exclusión mutua

a) Un proceso permanece dentro de su sección crítica sólo por un tiempo finito.  
<u>b) Un proceso que se pare en su sección no crítica puede interferir en otros procesos.</u>  
c) No debe ser posible que un proceso que solicite acceso a una sección crítica sea postergado indefinidamente: ni interbloqueo ni inanición.  
d) No se hacen suposiciones sobre las velocidades relativas de los procesos ni sobre el número de procesadores.  

#### Indica cuál es una desventaja del uso de una instrucción máquina especial para conseguir exclusión mutua

<u>a) Posibilidad de inanición.</u>  
b) Posibilidad de círculo vicioso.  
c) Posibilidad de condición de carrera.  
d) Dificultad de verificación.  

#### ¿Cual es el principio fundamental del semáforo?

<u>a) Es un recurso compartido de UNIX, en el cual dos o mas procesos pueden cooperar por medio de señales, tales que un proceso pueda ser obligado a parar en un lugar especifico hasta que haya recibido una señal especifica.</u>  
b) Es un recurso compartido que hace que los procesos se ejecuten de forma más rapida y en orden aleatorio.  
c) Es un recurso compartido de UNIX, el cual hace que todos los procesos se ejecuten en un recurso a la vez.  
d) Todas son falsas.  

#### ¿Que hace un semWait y un semSignal?

a) Dan paso al proceso dentro del recurso y lo hacen salir del recurso respectivamente.  
b) Se usa en otros recursos compartidos de UNIX.  
<u>c) Decrementa el semáforo antes de entrar en el recurso, y lo incremente justo cuando lo acaba de usar respectivamente.</u>  
d) No sirven para nada, els SO controla totalmente los procesos.  

#### ¿Si tenemos tres procesos usando un recurso(contador semáforo está = -2) y un proceso sale y hace un semSignal (contador semáforo = -1), y tenemos varios procesos en la cola de bloqueados del semáforo, como y cuando pueden entrar a usar el recurso que han dejado disponible?

a) El mismo proceso en cola se metera en el recurso cuando el último haya hecho un semSignal.  
b) No va entrar hasta que el semáforo sea igual o mayor que 0.  
c) Aunque el semáforo este en negativo, el SO coge un proceso de la cola de bloqueados del semáforo cuando un proceso hace un semSignal. Y va a ser lo primero que haga el SO, ya que la cola de bloqueados de los semáforos tienen prioridad absoluta en todos los SO.  
<u>d) Aunque el semáforo este en negativo, el SO coge un proceso de la cola de bloqueados del semáforo cuando un proceso hace un semSignal. Y va a tardar dependiendo de las politicas del SO.</u>  

#### ¿Cual es la diferencia entre un semáforo fuerte y uno debil?

a) No existen los semáforos debiles ni fuertes.  
<u>b) Los semáforos fuertes son los que tienen una politica FIFO (los primero que han entrado son los primeros que saldran), mintras que un semáforo debil es aquel que no sigue esta politica.</u>  
c) Ninguna de las otras es correcta.  
d) Los semáforo fuertes son los que tiene mas prioridad delante semáforos debiles.  

#### ¿Como actua el semáforo, para solucionar el problema del productor/consumidor?

<u>a) El problema del productor/consumidor, solo admite un productor (puede haber varios) o un consumidor usar el buffer de datos, no puede haber más procesos a la vez, por tanto usando un semáforo binario.</u>  
b) El problema del productor/rconsumidor no necesita semáforos.  
c) El problema del productor/consumidor es un problema visto en empresa de primero de GEIN, no tiene nada que ver con SO I.  
d) El problema del productor/consumidor, solo acepta varios(dependiendo del semáforo que se haya definido) procesos productores o varios procesos consumidores coger del buffer de datos.  

#### Cómo hace un programa para entrar en el monitor?

a) Haciendo un wait sobre el semáforo del monitor.  
b) Haciendo un signal sobre el semáforo del monitor.  
c) El monitor invoca al programa para que entre.  
<u>d) Invocando un método del monitor.</u>.  

Un monitor es un módulo de software distinto a un semáforo que implementa unas funciones internas de forma que la exclusión mutua se consigue evitando que un método del mismo sea utilizado por dos procedimientos a la vez.

#### Como se consigue la sincronización entre procesos usando un monitor, es decir cómo puede informar a otro proceso bloqueado que un recurso está disponible?

a) Con un signal del semáforo del monitor.  
<u>b) Utilizando variables condicionales.</u>  
c) Por paso de mensajes.  
d) Invocando a un método especifico del monitor que cumple dicho objetivo.  

Con el uso de semáforos el mismo semáforo actúa como un sistema de sincronización, es decir que si el semáforo está disponible entonces el recurso está disponible. En el caso del monitor lo que se protege es un método (programación orientada a objetos) de forma que al terminar la ejecución del método no se puede asegurar que el recurso está disponible, sin embargo como el método solo lo puede utilizar un proceso a la vez entonces al introducir una variable condicional dentro del procedimiento se puede indicar a otro proceso de que puede continuar.  

#### En el caso de semáforos para asegurar exclusión mutua sobre varios recursos se necesitan tantos como recursos se quieran proteger. En el caso de un monitor cómo se consigue?

<u>a) Creando tantas variables condicionales como recursos haya que proteger.</u>  
b) Creando funciones internas propias para cada recurso.  
c) Creando tantos monitores como recursos haya que proteger.  
d) Con el paso de mensajes.  

Como la variable condicional es utilizada por el monitor para conseguir la sincronización entre procesos, entonces al utilizar varias variables se consigue que un proceso se bloque en diferentes colas que representarían las colas de los recursos.  

#### Que sucede cuando un proceso que está dentro del monitor ejecuta un signal sobre una variable condicional

a) Todos los procesos que están esperando por entrar en el monitor lo hacen.  
b) Se activan todos los procesos que están en la cola de espera de la variable condicional.  
<u>c) Dependiendo de la implementación el proceso actual se bloquea en el monitor o termina su ejecución.</u>  
d) Ninguna de las anteriores.  
Cuando el proceso actual realiza un signal podría continuar su ejecución mientras no se active ningún otro proceso, o podría bloquearse dentro del monitor para que entre otro proceso (no necesariamente un proceso de la cola de la variable condicional) ya que en ambos casos se sigue cumpliendo la exclusión mutua.  

#### Con qué implementación de paso de mensajes no tienen que esperar el emisor ni el receptor?

a) Blocking send, nonblocking receive.  
<u>b) Nonblocking send, nonblocking receive.</u>  
c) Nonblocking send, blocking receive.  
d) Blocking send, blocking receive.  

#### En qué tipo de direccionamiento en los mensajes entre procesos se refiere al mailbox como port?

<u>a) Many to one.</u>  
b) One to one.  
c) One to many.  
d) Many to many.  

#### Una forma de implementar la cola de mensajes es con un FIFO, pero si algunos mensajes pueden ser más urgentes que otros una opción es

a) Que el receptor asigne un campo de prioridad a los mensajes.  
b) Que el emisor decida la prioridad del mensaje según el contenido del mensaje.  
c) Que el receptor decida la prioridad del mensaje según el contenido del mensaje.  
<u>d) Que el receptor pueda inspeccionar la cola de mensajes y elegir cual quiere recibir.</u>  

#### Cuál de los siguientes elementos NO se encuentra en la cabecera un mensaje típico

a) Tipo de mensaje.  
b) ID de la fuente.  
<u>c) Prioridad del mensaje.</u>  
d) Información de control.  

## Tema 6

#### En qué categorias se pueden dividir los recursos?

a) Reutilizables y no reutilitzables.  
<u>b) Reutilizables y consumibles.</u>  
c) Necesarios, no reutilitzables y consumibles.  
d) Necesarios, consumibles y destruibles.  

Tan solo existen los recursos reutilitzables y los consumibles.  

#### De las listas siguientes, en cual de ellas todos los recursos son reutilizables?

<u>a) Procesadores, canales de E/S y bases de datos.</u>  
b) Buffers de E/S, memoria principal y semáforos.  
c) Procesadores, interrupciones y memoria principal.  
d) Memoria principal y secundaria, interrupciones y seméaforos.  

Los recursos reutilitzables son aquellos que pueden ser usados con seguridad por un proceso y no se agota con el uso. Como ejemplos de recursos reutilizables se tienen los procesadores, canales de E/S, memoria principal y secundaria, dispositivos y estructuras de datos tales como archivos, bases de datos y semáforos.  

#### Cuales son los métodos generales para hacer frente al interbloqueo?

a) Prevención, andlisis y estructuración.  
<u>b) Prevención, deteccién y predicción. (X)</u>  
c) Prevención, deteccion y estructuración.  
d) Comprobación, captaci6n y predicción.  

Los métodos generales para hacer frente al interbloqueo son tres: prevención, detección y predicción.  

#### Señala que opción es correcta

a) Un estado seguro es aquel estado capaz de llegar hasta el final sin generar interbloqueo.  
b) Un estado seguro es aquel estado capaz de llegar hasta el final generando interbloqueo.  
c) Un estado seguro es un estado en el cual no existe ningún orden en el que todos los procesos puedan ejecutar hasta el final sin generar un interbloqueo.  
<u>d) Un estado seguro es un estado en el cual existe al menos un orden en el que todos los procesos puedan ejecutar hasta el final sin generar un interbloqueo.</u>  

#### Cual de las siguientes afirmaciones es falsa?

a) Una señal es un mecanismo de software que informa a un proceso de la existencia de eventos asincronos.  
b) Las señales pueden ser enviadas tanto por procesos como por el núcleo.  
<u>c) Un proceso siempre tiene que responder una señal.</u>  
d) Las señales tienen todas la misma prioridad y se le presentan al proceso una detras de otra.  

Un proceso puede responder a una señal (ya sea realizando alguna accion por defecto o ejecutando una función de manejo de la señal) o simplemente ignorarla.  

#### En qué consiste la prevencion del interbloqueo?

a) Se permiten las tres condiciones necesarias del interbloqueo pero se toman decisiones razonables para evitarlo.  
b) Mirar los procesos detectando algun indicio de interbloqueo.  
<u>c) Diseñar el sistema de tal manera que se excluya la posibilidad de interbloqueo.</u>  
d) Detecta el interbloqueo y lo soluciona como lo requiera el problema.  
La prevención de un interbloqueo se basa en diseñar un sistema donde no exista la posibilidad de interbloqueo.  

#### Que tipos de tuberias existen en UNIX?

a) Las de 64B, de 128B y de 264B.  
<u>b) Con nombre y sin nombre.</u>  
C) Las débiles, las medianas y las fuertes.  
d) Las que aceptan varios procesos a la vez y las que solo aceptan uno.  

Existen las que tienen nombre, que pueden ser compartidas por cualquier proceso, y las que no tienen nombre que pueden ser compartidas únicamente por procesos relacionados entre si.  

#### De cuales de los siguientes elementos no consta un semáforo?

a) El valor actual del semáforo.  
b) El número de procesos en espera de que el valor del semáforo sea 0.  
<u>c) El identificador de los procesos que estan a la espera.</u>  
d) El identificador del último proceso que operó con el semáforo.  

Un semáforo puede indicar el número de procesos que desean acceder al recuso y esta asociado a una cola de procesos bloqueados, pero no tiene el identificador de los procesos en cola.  

#### Qué condiciones debe haber para que, siempre, se produzca un interbloqueo?

<u>a) Exclusión mutua, retención y espera, sin expropiación y espera circular.</u>  
b) Exclusón mutua, prevención y sin expropiación.  
c) Exclusión mutua, retención y espera, y sin expropiación.  
d) Exclusión mutua, retención y espera, y asignación de recursos.  

Las condiciones necesarias para que exista la posibilidad de que haya interbloqueo son exclusión mutua, retenci6n y espera y sin expropiación, pero incluso con estas tres condiciones puede no producirse el interbloqueo, para que siempre haya interbloqueo, hay que añadir una cuarta condición, la espera circular.  

#### Cual de las siguientes afirmaciones sobre las tuberías es falsa?

a) Un proceso que intenta leer mas bytes de los que están en la tuberia, se bloquea.  
b) Una tubería es un buffer circular que permite que dos procesos se comuniquen siguiendo el modelo productor-consumidor. Por tanto, se establece una cola de tipo que el primero en entrar en la tuberia, es el primero en salir.  
<u>c) Una tuberia puede ser accedida por mas de un proceso simultaneamente.</u>  
d) Cuando un proceso intenta escribir en la tubería, la petición de escritura se ejecuta inmediatamente siempre y cuando haya espacio en la tubería, en caso
contrario se bloquea el proceso. En cada momento sólo puede acceder a una tubería, un único proceso.  

#### Cual de los siguientes tipos de semaforos no existe?

a) Semaforos con contador.  
b) Semaforos de lectura - escritura.  
<u>c) Semaforos de E/S (Entrada / Salida).</u>  
d) Semaforos binarios.  

Los semaforos de Entrada/Salida no existen.  

#### Elije la opción correcta

a) Los procesos no pueden enviar sejiales entre si.  
b) La forma mas rápida de comunicacién entre procesos son las tuberías.  
c) Un mensaje entre procesos, nunca podra provocar un bloqueo de algún proceso.  
<u>d) La forma mas rápida de comunicacién entre procesos es la memoria compartida.</u>  

Los procesos pueden enviar señales entre si, la forma mas rápida de comunicación entre procesos es la memoria compartida, Un mensaje entre procesos, puede provocar un bloqueo de algín proceso, si se intenta enviar un mensaje a una cola llena o si se intenta leer un mensaje de una cola vacía.  

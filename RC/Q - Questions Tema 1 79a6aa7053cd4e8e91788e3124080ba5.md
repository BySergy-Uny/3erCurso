# Q - Questions Tema 1

### Parte I

- Concepto de red

    Debido a que la comunicación es una necesidad básica y la información es el sustento del conocimiento se buscó una manera sencilla de transmitirla a las personas de todo el mundo y de ahí nació la red como medio de comunicación

    Modelo de sistema de comunicaciones:

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled.png)

- Tipos de datos vs Tipo de transmisión

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%201.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%201.png)

- Modelo físico de comunicación de datos

    Las funciones que realiza son interfaz, sincronización, formato de los mensajes, detección/corrección de errores, control de flujo, ...

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%202.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%202.png)

- Perturbaciones de las transmisiones
    - Atenuación

        La atenuación es una pérdida de energía de la señal producida por la distancia, su unidad es dB y la atenuación es mayor con la frecuencia

    - Distorsión

        La distorsión se debe a que la velocidad de propagación de las componentes de frecuencia de la señal es diferente, limita la velocidad de transmisión y si la señal es digital aumenta la tasa de bits erróneos

    - Ruido

        El ruido es cualquier señal no deseada que se inserta en algún punto entre el emisor y el receptor, es el factor de mayor importancia en un sistema de comunicación, la calidad de la señal se mide mediante la relación señal/ruido (SNR) que es la proporción entre las potencias de las señales y la potencia del ruido, medido en dB.

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%203.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%203.png)

    - Errores de transmisión

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%204.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%204.png)

- Ancho de banda

    El ancho de banda es el rango permitido de frecuencias del contenido de la señal sin perdida significativa de energía o atenuacion

- Capacidad de un canal de transmisión

    La capacidad es la velocidad de transmisión maxima, medida en bps a la que se transmite los datos, hay dos aproximaciones para su cálculo:

    - Teorema de Nyquist - para canales sin ruido

        La limitación de la velocidad esta impuesta por el ancho de banda y para señales binarias, M=2 en un ancho de banda B, la capacidad  maxima es de 2B

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%205.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%205.png)

    - Teorema de Shannon - para canales con ruido

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%206.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%206.png)

        A mayor ancho de banda  → mayor velocidad de transmisión y la capacidad del canal aumenta con la potencia de la señal y disminuye con el ruido

- Tecnicas de transmisión de datos

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%207.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%207.png)

    - Transmisión serie vs paralelo

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%208.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%208.png)

    - Transmision asíncrona

        Los datos se transmiten de forma intermitente carácter a carácter, además se le añade un bit al principio que corresponde al inicio del mensaje con un cero y en el caso de que el estado de envió este en reposo se enviara un 1. No se dejara de enviar datos.

    - Transmision síncrona

        Una transmisión síncrona conlleva un reloj, por tanto, los dos equipos deberán estar sincronizados para ello se utiliza una información de sincronismo llamados flags, hay delimitador preámbulo al inicio de la trama y delimitador final para acabar el mensaje

- Topología básica de línea

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%209.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%209.png)

    Se estudian mas tarde

- Velocidades y tiempos + Cronogramas

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2010.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2010.png)

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2011.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2011.png)

- Equipos de red
    - Sistemas finales o hosts o ETD o DTE - son equipos de origen o destino donde están las apps de usuario
    - Nodo - equipo para la conmutación de datos y donde se realiza el enrutamiento de la información
- Estructura de red

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2012.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2012.png)

### Parte II

- Noción de arquitectura de comunicaciones

    La arquitectura de comunicaciones está estructurada mediante un conjunto de protocolos que permiten el intercambio de información entre equipos, únicamente de especificación funcional y sus componentes, no se define la implementación de la arquitectura, por tanto, constituye el marco de trabajo del proceso de normalización.

- Modelo de capas de arquitectura

    Los modelos de capas son la forma de describir las arquitecturas de kas redes, ya que permiten abstraer los diferentes problemas en más sencillos.

    - Principios
        - La capa N ofrece servicios a la N+1, y la N+1 utiliza los servicios de la capa N
        - La capa N se comunica con las capa N de otro sistema mediante el mismo protocolo de la capa N
    - La comunicación entre capas adyacentes se realiza a traves de la interfaz de
    - El conjunto de protocolos que interoperan en todos los niveles se llama pila de protocolos
- Protocolo comunicación

    los protocolos están formados por reglas y formatos entre las funciones más importantes son el control de flujo y de errores, y la fragmentación y el reensamblado

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2013.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2013.png)

- Protocolo del modelo OSI
    - Jerarquía

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2014.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2014.png)

    - Servicios

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2015.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2015.png)

    - Función de encapsulación

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2016.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2016.png)

- Arquitectura OSI

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2017.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2017.png)

    - Comunicacion entre sistemas finales

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2018.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2018.png)

    - Encapsulación

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2019.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2019.png)

- Arquitectura TCP/IP

    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2020.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2020.png)

    - Capa de interfaz de red

        La capa de interfaz de red es responsable de enviar y recibir señales entre dos hosts comunicados entre interfaces de red, la capa incluye drivers y NIC, tarjeta de interfaz de red.

        - El controlador de dispositivos o interfaz de red se compone de Sw que se comunica con el Sw TCP/IP y NIC
        - La tarjeta de interfaz de red implementa el nivel físico
        - Subcapa de nivel físico en cable

            ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2021.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2021.png)

        - Subcapa de nivel físico en inalámbrico

            ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2022.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2022.png)

        - Subcapa de nivel de enlace

            ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2023.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2023.png)

    - Capa de red

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2024.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2024.png)

    - Funciones de la capa IP

        Las funciones de la capa IP es la comunicación P2P no orientada a la conexión, son independientes de las redes y sin garantía de llegada de paquetes, otras son direccionamiento lógico, almacenamiento y reenvió de datagramas, segmentación y reensamblado.

        - Datagrama IP

            Para encaminar hay que añadir cabecera por lo que el datagrama IP se compone de cabecera y carga util, su tamaño varía entre 20-64KB, 20KB de cabecera.

    - Capa de transporte

        El protocolo de trasporte permite la comunicación lógica entre programas y proceso de apps que se ejecutan en diferentes hosts.

        La información de transporte se transmite como segmentos (TCP) o datagramas (UDP) se dirige a la app remota gracias a la especificación del puerto, la información generada por la capa de transporte son datagrama IP se encaminan independientemente por la red. El Hw o Sw de la cap de transporte que se encarga del trabajo se llama Entidad de transporte. Se localiza en el kernel.

    - Protocolos TCP vs. UDP

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2025.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2025.png)

    - Los puertos

        Los puertos dan sus servicios al nivel de app a traves de los SAPs específicos denominados ports, cada puerto de nivel de transporte ofrece a las aplicaciones una interfaz de acceso a la red de comunicaciones, permitiendo dialogar con otra aplicación situada en otro puerto en una maquina remota.

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2026.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2026.png)

    - Capa de aplicación
        - Modelo C/S vs P2P

            ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2027.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2027.png)

        - C/S

            El servidor es cualquier programa que ofrezca un servicio, que acepte peticiones del servicio y emita el resultado. Las principales características del servidor son que siempre está en ejecución, su IP es permanente y están situados en centros de datos para su escalabilidad.

            El cliente envía peticiones al servidor esperando la respuesta, es el que interacciona con el usuario. Las características del cliente son que se comunican con los servidores, esta conectados de forma intermitente, pueden tener IP dinámica y no se comunican directamente con los clientes.

        - P2P

            La arquitectura extrema a extremo se caracteriza porque no hay servidor siempre en ejecución, los sistemas interaccionan entre ellos uno toma el rol de cliente el que solicita un servicio y el otro el rol de servidor el que ofrece un servicio, pero se van alternando según sus necesidades, estos sistemas facilitan la autoescalabilidad y los miembros tendrán una IP dinámica, su gestion es compleja.

        - Protocolos especificados

            ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2028.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2028.png)

        - FTP, File Transport Protocol

            ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2029.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2029.png)

        - DNS, Domain Name System

            una de las formas para aumentar la eficiencia y la productividad de la red es añadiendo nombres organizados de manera jerárquica ,que conformen un sistema de dominios que se llama DNS, esto permite obtener la información asociada a cualquier nombre. Este tipo de sistemas son como una base de datos distribuidas.

            - Jerarquía DNS

                ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2030.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2030.png)

        - Protocolo HTTP, Hyper Text Transfer Protocol

            ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2031.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2031.png)

        - Protocolo modelo OSI
            - Problema inicial

                Cuando un emisor es más rápido que el receptor se puede producir desbordamiento, la solución que se ha adoptado es incorporar un control deflujo que permita al receptor regular el flujo para que no se sobrecargue la cantidad excesiva de datos.

            - Funciones de Control de flujo

                ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2032.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2032.png)

                - Canal sin errores

                    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2033.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2033.png)

                    ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2034.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2034.png)

                - X-ON/X-OFF

                    Se aplica en conexiones asíncronas. Cuando el receptor quiere detener ya que detecta sobrecarga envía el carácter X-OFF

                - Parada y Espera, stop&wait

                    El receptor indica cuál es su estado mediante mensajes ACK o de confirmación

                    - Canal Sin errores

                        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2035.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2035.png)

                - Mecanismo de Ventana

                    El receptor indica al emisor se disponibilidad, regulando el número de tramas pendientes de confirmación, el tamaño fijo es X-25 y el variable TCP/IP

                    - Canal sin errores

                        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2036.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2036.png)

                    - Transmision continuada

                        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2037.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2037.png)

        - Función de Control de errores

            El control de errores de un protocolo son los mecanismos necesarios para la detección y corrección de errores a la hora del envió de PDUs

            - Mecanismos de control
                - Descarte (en Frame relay y ATM)

                    Consiste en renunciar a la corrección con la eliminación de la PDU errónea

                - Solución de repetición automática, ARQ, Automatic Repeat Request

                    Una vez que se detecta el error se recupera con retrasmisión. El objetivo es convertir conexiones no fiables en fiables.

                    - Con parada y espera

                        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2038.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2038.png)

                    - Con vuelta atrás

                        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2039.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2039.png)

                - Corrección de errores hacia delante, FEC, Forward Error Correction

                    Cuando no se dispone de retransmisiones. En ese caso se recurre, para corregir errores, exclusivamente a los bits redundantes recibidos en la trasnmision

        ![Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2040.png](Q%20-%20Questions%20Tema%201%2079a6aa7053cd4e8e91788e3124080ba5/Untitled%2040.png)
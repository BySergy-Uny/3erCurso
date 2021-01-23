# Q - Questions T3

## Parte I

- Tipos de redes
    - PAN (Red de area personal)
    - LAN (Red de area local)
    - MAN (Red de area metropolitana)
    - WAN (Red de area extensa)
- Concepto de WAN, Wide area network

    Red que cubre una extensa area geografica que requiere atravesar rutas de acceso publico y utiliza circuitos proprcionados por una entidad proveedora de servicios de telecomunicaion. Se caracteriza por tener alta velocidadm, medios de transmision diversos sobre todos los satelites, soporta multiples servicios de transmision de datos, voz y video, tiene tasa de error superior a las LAN y aunque puede ser privada la mayoria esta contratada por compañias tecnologicas.

    - Alcance

        Conectar ordenadores de cualquier localizacion del mundo

    - Conexion

        Linea telefonica, fibra optica, satelites, inalambrica terrestre, ...

    - Redes Publicas

        Los medios de conexion de las lineas utilizadas son propiedades de empresas de telecomunicaciones que las alquilan al publico y a compañias en  general

- Clasificacion

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled.png)

- Tipos de servicios de  comunicacion WAN
    - Lineas dedicadas

        Elenlace dedicado permanentemente con un caudal reservado, se une o no.

    - Conmutacion de circuitos

        La conexion solo se establece cuando se necesita, pero mientras hay conexion el caudal esta reservado al usuario tanto si lo usa como si no.

    - Conmutacion de paquetes

        El ancho de banda disponible es compartido por diversos circuitos, de forma que se multiplexa trafico de diferentes usuarios, la infraestructura se aprovecha de manera optima.

- Lineas dedicadas

    Conexiones P2P, conectan dispositivos de red que necesitan intercambio de informacion con un flujo de transmision constante y garantizado, el costo proporcional a la distancia y la capacidad (Tarifa plana), las principales velocidades son 64, 128, 256 y 512 Kb/s, 2 y 34 Mb/s y las caracteristicas tecnicas del servicio son enlaces con soporte multiprotocolo, variedad de interfaces de entrega del servicio y la velocidad garantizada y posibilidad de aumento de velocidades.

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%201.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%201.png)

- Redes de conmutacion de circuitos

    Adecuadas para conexiones de poco tiempo, coste proporcional al tiempo y tecnologias como RTB (Red de telefonia basica) y RDSI (Red digital de servicios integrados)  o ISDN

    - Inconvenientes

        La capacidad del canal se desaprovecha cuando no se envian datos, origen y destino deben de transmitir a la misma velocidad, riesgo de congestion de red, el numero de canales es limitado y cada conexion consume muchos recursos.

- Redes de conmutacion de paquetes

    Aprovecha mejor los recursos, posibilidad de crear circuitos virtuales (CV) de dos tipos : 

    - Conmuados - SVCs (Switched Virtual Circuits)
    - Permanentes - PVCs (Permanent Virtual Circuits)
    - Mediante circuito virtual

        ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%202.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%202.png)

        ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%203.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%203.png)

## Parte II

- Red Digital de servicios integrados

    Las caracteristicas de este tipo de res son que son conexiones digitales entre abonados, integracion de voz y datos a traves de la misma interfaz, entre bentanas de la RSDI se encuantran :

    - La posibilidad de conectar inteligentemente varios dispositivos a una misma linea
    - La posibilidad de obtener varios canales de 64 Kbps segun lo demanden las necesidades

    Los tipos de canales / tipos de acceso : 

    - Canal B - a 64 Kbps para voz y datos. Puede haber un numero variable segun el tipo de interfaz.
    - Canal D - a 16 a 64 Kbps para señalizacion
    - Acceso Basico (BRI, Basic Rate Interface) - formando por 2 canales B y uno D (2B + D)
    - Acceso primario (PRI, Primary Rate Interface)
- RDSI-BA /  ATM

    ATM es la ecnologia de los cuale implementa las redes B-ISDN, los objetivos son aplicar el principio de aprovechamiento de la conmutacio de paquetes a todo tipo de trafico. Las caracteristicas son :

    - Protocolo CONS, por tanto se garantiza el orden de llegada
    - Proporciona multiples canales en la linea mediante MDT
    - Transmision mediante CV de unidades de datos de tamaño fijo
    - Parecido a Frame Relay con mas velocidad y muchas mas posibilidades de control de trafico. Pensando para ofrecer calidad de servicio.
    - Minima capacidad de control de errores y fliujo lo que reduce el cosdte de prodesamiento de las celdas.
- Multiplexacion MDT

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%204.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%204.png)

    - Asincrona

        ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%205.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%205.png)

- Celda ATM

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%206.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%206.png)

- Interfaz de la red ATM

    Los conmutadores ATM soportan dos tipos primarios de interfaces:

    - UNI (User to Network Interface) - La interfaz UNI conecta sistemas finales ATM (Tales como servidores y routers a un conmutador ATM)
    - NNI (Network to Network Interface) - Conecta dos conmutadores ATM
- Niveles ATM

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%207.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%207.png)

- Nivel Fisico

    Envio de datos por el medio fisico: codificacion y sincronizacion de señales, con una velocidad de transmision 155 / 622 Mbps, necesidad de especificar la estructura de transmision para el traporte de la carga util, el encvio directamente por fibra optica o par trenzado o sobre otro sistema portador y la capa fisica se subdivide : 

    - Subcapa PMD (Physical Madia Dependent) es equivalente a la capa fisica OSI - se especificacion del medio y esquema de cdificacion. Precisa sincronizacion que se consigue con el campo de control de errores de la cabecera HEC
    - Subcapa TC (Transmision Convergence). Descompone en bits las celdas de la capa ATM y recompone en celsad los bits que recoge de la subcapa PMD. Realiza parte de las funcione que corresponden a la capa de enlace
- Subnivel ATM

    Define estructuras de las celdas y su transorte, constitute y termina los CV (multiplexacion u conmutacion del medio), realiza control de congestion, elimina las unidades recibidas con errores y equicale a una mezcla de la capa de enlace y la red

- Subnivel AAL

    Permite transmitir protocolos no basados en ATM, las funciones son segmentacion y reensamblado, control de flujo y temporizacion.

    El subnivel AAL se subdivide en :

    - Subcapa CS (Convergence Sublayer) - se ocupa de suministrar distintos tipos de servicios adecuados al tipo de trafico
    - Subcapa SAR (Segmentacion an d Reassemby Sublayer) - se ocupa de dividir en celdas el paquete recibido de CS y de reensamblar en el receptor el paquete a partir de las celdas recibidas

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%208.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%208.png)

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%209.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%209.png)

- Conexion logica ATM
    - Canal Virtual (VC)

        Tubo unidireccional compuesto a partir de la concatenacion de una secuencia de elementos de conexion que permite el transmoporte secuencial e integral de celdas en unflujo full-duplex. La concatenacion de varios VC forman una conexion de cal virtual VCC y une dos usuaior finales (user-user, user-red o red-red), cada VC esta asociado a un unico identificador llamado VCI y las celdas ATM se trasnforman en la red por VC

    - Camino o ruta virtual (VP)

        Agrupacion de VC con los mismos extremos de manera que todas las celdas trasnmitidas a traves de todas las VCC de unamisma VCP se conmutan conjuntamente. Cada VP esta asociado a un unico identificador llamado VPI

- Conmutacion ATM

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2010.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2010.png)

- Categorias de servicios ATM

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2011.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2011.png)

- Parametros de conexion ATM

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2012.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2012.png)

- Categorias estandarizados de servicio ATM

    ![Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2013.png](Q%20-%20Questions%20T3%20fe797ffaff964f37bfa735ea9043fc0c/Untitled%2013.png)
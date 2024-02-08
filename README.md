Sprint1 - Hardering en Ubuntu:

   -Tarea 1: Lectura artículo CIS.
   -Tarea 2: Guía/Tutorial cis_level2_server.
   -Tarea 3: Seguir el semniario de INCIBE.
   -Tarea 4: Asegurar configuraciones globales.
   -Tarea 5: Configuración de usuarios y grupos.
   -Tarea 6: Comprobación del complimiento sobre las actualizaciones de software


Sprint2 - Copias de seguridad:

  -Tarea 1: Instalación de duplicati.
  -Tarea 2: Copia nº1 (Documentos).
  -Tarea 3: Copia nº2 (Imágenes).


Sprint3 - Hardering apache:

   Instalación de Apache. 
   Configuraciones globales. comprobarlas 
   
   Ficheros de configuraciones 

   Configuración de usuarios y grupos

   Ocultación de versiones. 

   Exposición mínima de módulos.

   Creación de virtualhost con tu nombre y apellido.
   
   Configuración múltiple y de contexto: directiva options

   Ficheros .htaccess. ¿Para qué sirven?

   ¿Cómo podemos evitar el hotlinking? Compruébalo.
   
   Configuración HTTPS mediante OpenSSL. Crea los certificados para que tu virtualHost sea seguro, y       obligatoriamente los accesos sean por HTTPS
   
   Módulo mod_security. ¿Qué es mod_security?
   
   Realiza un ataque DoS mediante Metasploit (Slowloris) y comprueba que efectivamente el servidor          está inaccesible.
   
   Clona e instala las reglas recomendadas OWASP. Habilita mod_security
   
   Reglas para detectar SQLInjection
   
   Realiza de nuevo el ataque DoS y comprueba que el servidor está accesible.


Sprint4 - Hardering SSH:


   Realiza la instalación de tu servidor SSH siguiente la guía del Incibe (minuto 15), y aplica las          configuraciones de hardening recomendadas por el Incibe.

   Además, investiga como habilitar el doble factor de autenticación en el servicio SSH, configura y          comprueba su correcto funcionamiento.


Sprint5 - Escaneo de vulnerabiliades

   Descarga la máquina virtual metasplotaible2, e impórtala en VirtualBox. Esta máquina virtual es muy       utilizada para practicar pentesting, ya que es conocida por su multitud de vulnerabilidades.


   Realiza una lectura de la cheatSheet de Nmap.

   Realiza un escaneo utilizando la técnica SYN Scan y reconoce los principales servicios de la             máquina metasplotaible 2 y tu servidor de Ubuntu.

   Realiza un escaneo de los principales puertos UDP abiertos en la máquina metasplotaible2.

   Realiza un escaneo lanzando el script vuln sobre metasplotaible 2 y tu servidor de Ubuntu.

   Realiza un escaneo agresivo sobre metasplotaible 2 y tu servidor de Ubuntu.

   Realiza un escaneo únicamente de descubrimiento de equipos en la red de tu casa.

   Para todos ellos, comenta los resultados obtenidos.


Sprint6 - Seguridad perimetral con pfSense

   Instala Pfsense con tres tarjetas de red: Wan (adaptador puente, Lan DMZ (Red interna 10.0.3.0/24)       y Lan Empleados (Red interna 10.0.2.0/24).
   
   Configura el servidor adjudicando a su tarjeta de red Lan DMZ.
   
   Configura el equipo del empleado adjudicando a su tarjeta de red Lan Empleados (debes simular que       este equipo es un Windows).

   Responder preguntas.


Sprint7 - IDS y VPN con pfSense

   Instala IDS/IPS Suricata siguiendo esta guía.
   A
   plica las reglas de la comunidad Snort.
   
   Antes de habilitar Suricata, realiza un ataque DoS sobre el servidor Web. 
  
   Habilita el IDS, y vuelve a realizar el ataque, comprobando que aparece en el log el ataque que se       está realizando, además de proteger del mismo.
   
   Habilita el servidor VPN en pfSense. Para ello puedes seguir las siguientes guía (selecciona la          tecnología que prefieras):
         -OpenVPN configura y comprueba su funcionamiento.
         -WireGuard configura y comprueba su funcionamiento. 
   
   Además, resaltar que pfSense, en el apartado diagnostics incorpora multitud de herramientas que          pueden ser interesantes. En nuestro caso vamos a añadir una nueva: ntopng. Esta herramienta           está orientada al análisis de tráfico de red. Para utilizar esta herramienta debes descargar          el paquete ntopng. Comenta brevemente la información que puedes obtener.



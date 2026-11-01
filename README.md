## Trabajo práctico INTEGRADOR de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: Elvis De la Torre
* Título corto del trabajo: Réplica de la RTLS UWB Click (Qorvo DWM3001C)
* Descripción: Réplica de la placa RTLS UWB Click (MIKROE-6863), basada en el módulo Qorvo DWM3001C, para medición de distancia y localización por UWB. Incluye cargador de batería Li-ion, LDO de 3,3 V, USB Type-C y conector mikroBUS. El objetivo es rediseñar la placa como base para su uso en el trabajo final de la Especialización en Sistemas Embebidos (CESE-FIUBA). Como modificación inicial respecto del original, se elimina el circuito ClickID (DS28E36 y 74LVC1G3157).
* Cursada: OCT-NOV-DIC 2026


## Licencia de este trabajo ##
XXXMENCIONAR ACÁ LA LICENCIAXXX (Editar este párrafo) 
Y además colcar el archivo de texto de la misma en el directorio raíz.
Para este TP se pide que la licencia sea de hardware abierto.
Ver la sección "What license should I use?": https://www.oshwa.org/faq/

## Estructura del repositorio ##

* **doc**: documentación propia del trabajo.
  * [doc/propuesta](doc/propuesta): propuesta del TP, con fotos de ambas caras de la placa original, el esquemático de referencia y las fuentes.
* **info**: información de terceros.
  * [info/datasheets](info/datasheets): hojas de datos de los componentes relevantes.
  * [info/cad](info/cad): modelo 3D (STEP) y contorno (DXF) de la placa original.
* **pcb**: proyecto KiCad (esquemático, PCB, modelos 3D, bibliotecas propias y archivos de fabricación: BOM, gerbers).

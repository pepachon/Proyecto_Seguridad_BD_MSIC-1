# ROLES Y RESPONSABILIDADES

## Tabla de Contenido

* [DEFINICIÓN DE ROLES Y RESPONSABILIDADES](#definición-de-roles-y-responsabilidades)
  + [DBA (Database Administrator)](#dba-database-administrator)
  + [Analista de Aplicaciones](#analista-de-aplicaciones)
  + [Coordinador de Seguridad](#coordinador-de-seguridad)
  + [Usuarios](#usuarios)
* [MATRIZ RACI](#matriz-raci)

 - - -

## DEFINICIÓN DE ROLES Y RESPONSABILIDADES

Se presenta la siguiente metodología de gestión de riesgos para la bases de datos de Salud Capital, acorde a los requerimientos y apetito de riesgo de la entidad.

### DBA (Database Administrator)

Garantizar y optimizar la integridad y estabilidad de las bases de datos, que administran la información de las operaciones de la compañía, para que siempre estén disponibles, según las necesidades de las diferentes áreas de la compañía.

* Administración bases de datos (inserción, eliminación, modificación). 
* Afinamiento y rendimiento de bases de datos.
* Realización de backups y restauración de datos.
* Gestión de la capacidad de CPU y memoria.
* Estrategias de la gestión de la capacidad de la gestión de la disponibilidad de bases de datos.
* Estrategias de la gestión continuidad de la operación de bases de datos.

### Analista de Aplicaciones

Adaptar y diseñar sistemas de información para ayudar a la compañía optimizar sus procesos. El analista de aplicaciones deberá cumplir las siguientes obligaciones:

* Dar soporte técnico y funcional a las aplicaciones que soportan los procesos de la compañía mediante la atención oportuna de incidentes (se requiere permiso de consulta en la base de datos).
* Atender los requerimientos y proponer soluciones adecuadas para optimizar las actividades de los usuarios en los sistemas de información.
* Desarrollo e implementación de nuevos aplicativos para la compañía.
* Soporte a los sistemas de Información ERP.

### Coordinador de Seguridad

Garantizar la integridad, confidencialidad y disponibilidad de la información. El Coordinador de seguridad deberá cumplir las siguientes obligaciones:

* Custodio de las cuentas de servicio de la compañía.
* Monitoreo de seguridad de las plataformas de la compañía (base de datos, servidores, dispositivos de red, etc).
* Establecer directrices de seguridad basada en estándares de bases de datos Microsoft SQL.
* Autorizar la restauración de backups de bases de datos.
* Aseguramiento backups de bases de datos.

### Usuarios

El usuario es el sujeto autorizado a hacer inserción y consulta de sus datos.

## Matriz RACI

A continuación, se presenta la matriz RACI, para la cual se deben considerar los siguientes criterios

* R=Responsable
* A=Aprobador
* C=Consultado
* I=Informado

 . | DBA | Analista de aplicaciones | Coordinador de Seguridad | Usuarios
---|:---:|:------------------------:|:------------------------:|:---------:
Administración BD (consultas, edición, eliminación)| R/A | C | I | NA
Afinamiento de las bases de datos| R/A | C | I | NA
Realización de backups bases de datos| R | C | A/I | NA
Custodio cuentas de servicio| C | C | R/A | NA
Monitoreo de las bases de datos| C | C | R/A | NA
Restauración de backups| R | C | A/I | NA

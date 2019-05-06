# CLASIFICACION DE LA INFORMACION

## Tabla de Contenido

* [CRITERIOS DE CLASIFICACION](#criterios-de-clasificacion)
  + [GENERALES](#generales)
  + [ESPECIFICOS](#especificos)
* [CLASIFICACIÓN DE LA INFORMACIÓN](#clasificación-de-la-información)

 - - -

### CRITERIOS DE CLASIFICACION

#### GENERALES

Criterios por acceso o confidencialidad:

Acceso o Confidencialidad |	Descripción
:------:|-------
Altamente confidencial | Informacion de alta importancia para Salud Capital, su acceso es altamente restringido y solo para personal autorizado. Ej: Planes de negocio, bases de datos completas con datos personales o medicos.
Confidencial|Informacion importante y de valor para Salud Capital para garantizar la prestacion de los servicios, solo podrá ser accedida por grupos específicos de usuarios que requieren del conocimiento de esta información para estricto cumpimiento de sus funciones. Ejem: datos individuales o limitados de informacion, datos del negocio y operacion.
Uso interno|Informacion de consulta y de uso en el interior de Salud Capital, es accedida para fines pertinentes de las funciones y operaciones internas. Ejem: procedimientos, politicas internas.

Criterios por utilidad o función:

Utilidad o Funcion |	Descripción
:------:|-------
Información de clientes y proveedores |	De alto valor para la operacion de Salud Capital
Información de compras y ventas	| De valor alto-medio para la operacion de Salud Capital
información de personal y gestión interna |	De valor medio para la operacion de Salud Capital

Criterios por impacto al negocio:

Por el impacto al negocio | Descripción
:------:|-------
Perdida de imagen | Su perdida, modificacion o borrado implica perdidas reputacionales
Sanciones legales | Su perdida, modificacion o borrado implica incumplimientos y sanciones regulatorias
Sanciones economicas |	Su perdida, modificacion o borrado implica perdidas economicas


#### ESPECIFICOS

Criterios por acceso o confidencialidad:

Acceso o Confidencialidad | Confidencialidad | Integridad	| Disponibilidad | Autenticación | Control de Acceso | No repudio | Monitoreo
:------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
Altamente confidencial |X|X|X|X|X|X|X|
Confidencial |X|X||X|X||X
Uso interno|||X|X|X||

Criterios por utilidad o función:

Utilidad o Funcion|Confidencialidad|Integridad|Disponibilidad|Autenticacion|Control de Acceso|No repudio|Monitoreo
:------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
información de clientes y proveedores||X|X|X|X||X
información de compras y ventas||X|X||X||
información de personal y gestión interna||X|X||X||

Criterios por impacto al negocio:

Por el impacto al negocio|Confidencialidad|Integridad|Disponibilidad|Autenticacion|Control de Acceso|No repudio|Monitoreo
:------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
Perdida de imagen||X|X||||X
Sanciones legales||X|X||||X
Sanciones economicas||X|X||||X

- - -

## CLASIFICACIÓN DE LA INFORMACIÓN

A continuación se presenta el nivel de clasificación de la base de datos:

Elemento |Acceso o Confidencialidad|Utilidad o Funcion|Por el impacto al negocio
---------|:-----------------------:|------------------|-------------------------
BD Salud Capital | Altamente confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas

En la siguiente tabla se presenta el nivel de clasificación por tabla de la base datos:

Elemento |Acceso o Confidencialidad|Utilidad o Funcion|Por el impacto al negocio
---------|:-----------------------:|------------------|-------------------------
Tabla Personas|Confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Tabla Hijos|Confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Tabla Enfermedades|Confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas

Finalmente, se presenta la clasificación de la información considerando cada uno de los campos existentes en las diferentes tablas de la base datos:

Tabla | Campo |Acceso o Confidencialidad|Utilidad o Funcion|Por el impacto al negocio
------|:-----:|:-----------------------:|------------------|-------------------------
Personas|Id|Uso interno|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Personas|Nombre|Publico|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Personas|Cedula|Publico|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Personas|Profesion|Publico|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Personas|Tel|Confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Personas|Direccion|Confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Personas|Fecha_resolucion|Uso interno|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Hijos|Id|Uso interno|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Hijos|Nombre|Publico|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Hijos|Edad|Confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Hijos|Padre_id|Uso interno|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Enfermedades|Id|Uso interno|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Enfermedades|Nombre|Confidencial|Información de clientes y proveedores|Sanciones legales y sanciones economicas
Enfermedades|Padre_id|Uso interno|Información de clientes y proveedores|Sanciones legales y sanciones economicas

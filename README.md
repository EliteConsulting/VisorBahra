# Visor de la Base de Asentamientos Humanos de la República Argentina

# Introducción

La **Base de Asentamientos Humanos de la República Argentina (BAHRA)** es producto del trabajo conjunto entre el **Ministerio de Educación**, a través del **Programa Nacional Mapa Educativo**, el **Instituto Nacional de Estadística y Censos (INDEC)** y **el Instituto Geográfico Nacional (IGN)**.

Es la primera base de datos oficial y normalizada de localidades y sitios edificados de la República Argentina. Consiste en un registro único de datos que permite identificar a todos y cada uno de los asentamientos humanos (localidad censal o paraje, sitio edificado) con un nombre unívoco, una coordenada geográfica y un código único, independientemente de la categorización utilizada por los distintos organismos gubernamentales.

**Referencia:** [http://www.bahra.gob.ar](http://www.bahra.gob.ar)

# Desarrollo

El desarrollo se centra en disponibilizar un visualizador que consuma los servicios de base provisto por el IGN (Instituto Geográfico Nacional), específicamente la capa base del Argenmap, por otro lado el servicios WFS (Web Feature Service) tipificados en los siguientes grupos: 

* Localidades Censales;

* Sitios Edificados;

* Entidades.

Como también disponer de información en cada uno de los puntos que se representen en el mapa especificando los siguientes datos: 

* Código identificador;

* Fuente del dato;

* Nombre;

* Nombre del Departamento;

* Nombre de la Provincia;

* Tipo de grupo;

* Código BAHRA.


Descripcion de los campos:  [http://www.bahra.gob.ar/files/estructura_base_datos.pdf](http://www.bahra.gob.ar/files/estructura_base_datos.pdf)

# Herramientas 

Se desea que el proyecto cuente con las siguientes herramientas: 

1. Escala en el mapa;

2. Control de zoom;

3. Medición de longitud y áreas;

4. Información en el punto;

5. Búsqueda de Localidad o Sitio Edificado.


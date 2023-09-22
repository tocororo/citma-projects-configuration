# citma-projects-configuration

DspaceCRIS configurations. Repositorio de Programas, Proyectos y Premios

Este repositorio gestiona las configuraciones de la instalación de DspaceCRIS, para el [Repositorio de Proyectos, Programas y Premios del Proyecto Ciencia en Cuba](https://proyectos-citma.sceiba.cu/)

Se utilizó como base la carpeta de [configuración de DspaceCRIS](https://github.com/4Science/DSpace/tree/dspace-cris-7/dspace/config)

Aquí se detallan las especificidades de los metadatos, vocabularios controlados, etc.

## Contenido de este repositorio

- **dspace**: contiene las configuraciones del servidor DspaceCris
  - **dspace/config/citma-structure.xml**: define las principales colecciones y comunidades
  - **dspace/config/sumission-forms.xml**: define los formularios para importar datos

- **angular**: contiene las configuraciones de la interfaz
  - **dspace-ui.json**: configuracion para el servicio pm2
  - **config/config.prod.yml**: configuracion de dspace-angular

- **data**: contiene datos de ejemplos

# Soluciones para Apache log4cxx
En este repositorio se encuentra soluciones para poder compilar:

- [APR](https://apr.apache.org/)
- [APR-UTIL](https://apr.apache.org/)
- [LOG4CXX](https://logging.apache.org/log4cxx/)
- [EXPAT](https://libexpat.github.io/)
- [EXPAT_STATIC](https://libexpat.github.io/)

Esto permite compilar directamente la librería de **LOG4CXX** sin tener que descargar, configurar y arreglar los proyectos.

Con abrir la solución del proyecto (`log4cxx/projects/log4cxx.sln`) ya se pueden compilar las librerías **apr**, **apr-util**, **log4cxx** y con las soluciones de la carpeta `apr-util/xml/expat/lib/` se pueden compilar las librerías **expat** y **expat_static**.


En esta tabla, se resume todas las configuraciones y plataformas en que se puede compilar actualmente cada proyecto:

|               | Debug (x86) | Release (x86) | Debug (x64) | Release (x64) |
| :-----------: | :---------: | :-----------: | :---------: | :-----------: |
|      apr      |      ✔      |       ✔       |      ✔      |       ✔       |
|   apr-util    |      ✔      |       ✔       |      ✔      |       ✔       |
|    log4cxx    |      ✔      |       ✔       |      ✗      |       ✗       |
|     expat     |      ✔      |       ✔       |      ✔      |       ✔       |
| expat-static  |      ✔      |       ✔       |      ✔      |       ✔       |
|    expatw     |      ✗      |       ✗       |      ✗      |       ✗       |
| expatw-static |      ✗      |       ✗       |      ✗      |       ✗       |



### Contribuciones
---
Todas las contribuciones son bienvenidas mientras arreglen el proyecto.

Para cambios significativamente grandes, errores o sugerencias, por favor utilizad las `Issue`



### Licencias
---
Las licencias de cada proyecto se encuentra en sus respectivas páginas web o repositorios.

Este proyecto no tiene ningún ánimo de lucro y solo sirve con fines académicos. Cualquiera que utilice completa o parcialmente archivos de este repositorio se hará carga de cumplir con las leyes y licencias que corresponden a cada proyecto.
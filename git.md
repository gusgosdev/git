# GIT

- Es local
- Es un Sistema de Control de Versiones que nos permite rastrear los cambios que hemos
hecho en un conjunto de archivos.
- Nos permite trabajar en equipo, ver la fecha de cambios (commits) y volver atrás en el tiempo

## Teoría

- Repositorio  
Colección de archivos de distintas versiones de un proyecto.

- Commit  
Componentes básicos de la línea del tiempo de un proyecto de git.  
Son como un registro o "foto" del estado de un proyecto en un momento específico.  
Registran los cambios que se realizaron en los archivos en comparación con la versión anterior.  
Git le asigna a cada commit un identificador único llamado SHA (Secure Hash Algorithm) o hash.

- Git Bash
Herramienta que te permite ejecutar comandos de Git. Es una línea de comandos.

- 3 áreas de trabajo:  
    - Directorio de trabajo (Modificada)
        La carpeta del proyecto que contiene los archivos y el directorio .git del repositorio.

    - Área de preparación (Preparada)
        Conjunto de archivos y cambios que serán incluidos en el próximo commit.

    - Repositorio (directorio .git) (Confirmada)
        Directorio que contiene los metadatos y las versiones de tu proyecto.
        Es la parte del repositorio que se copia cuando clonas un repositorio a tu computadora. Es la parte mas importante de GIT.

- Rama (Branch)  
Una rama en Git es una línea independiente de desarrollo en el repositorio.

- Fusionar ramas  
Proceso que permite combinar varias líneas independientes de desarrollo en una sola rama.
Para fusionar dos ramas es importante estar en la rama que recibirá la fusión.
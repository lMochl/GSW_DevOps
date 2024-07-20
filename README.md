# Proyecto semestral Gestión de Proyectos de Software
Proyecto desarrollado por Matías Guiñez Monsalve y José García Navarrete estudiantes de la Universidad del Bío-Bío.

## Tabla de Contenidos
1. [Descripción](#descripción)
2. [DevOps](#devops)

## Descripción
Este proyecto se realizó como parte del curso de Gestión de Proyectos de Software. El objetivo principal fue desarrollar una aplicación siguiendo la filosofía DevOps para asegurar una integración y despliegue continuo efectivos.

## DevOps
Para asegurar un ciclo de vida de desarrollo de software eficiente y de alta calidad, se implementaron las siguientes prácticas y herramientas de DevOps:

<div align="center">
  <img src="./devops.png" alt="DevOps Pipeline" width="600"/>
</div>

### Integración Continua (CI)
Se utilizó GitHub Actions para configurar la integración continua. Cada vez que se realiza un commit, se ejecutan automáticamente las pruebas unitarias para garantizar que no se introduzcan errores en el código base.

### Despliegue Continuo (CD)
El despliegue continuo se configuró utilizando Vercel, lo que facilita la puesta en producción de la aplicación de manera ágil y sin interrupciones.

### Pipeline CI/CD
El pipeline CI/CD consta de los siguientes pasos:
1. **Build**: Construcción de la aplicación.
2. **Test**: Ejecución de los tests.
3. **Deploy**: Despliegue de la apliación atraves de Vercel.
4. **Monitor**: Monitorización continua del rendimiento y la salud de la aplicación la cual Vercel permite hacerlo.


## SISTEMA DE VERSIONES

Según la documentación: Semantic Versioning 2.0.09

Control de versiones semántico 2.0.0

Dado un número de versión MAJOR.MINOR.PATCH, incremente el:

Importante (nueva API, cambios importantes)
Menor (nuevas funciones, componentes internos, cambios irreversibles compatibles con versiones anteriores)
Parche (correcciones urgentes y parches menores)

O como yo lo entiendo mejor breakingChanges.feature.bugs

EJEMPLO: 2.1.3(importante: 2, de menor importancia: 1, parche: 3)

Pre-lanzamientos
Lo mismo que con los pre_releases_, pero añadiendo el alfa, beta o bc más un
número. Las versiones preliminares no se utilizan normalmente para patches.

alpha: Implica implementación inestable en etapa de diseño.
beta: Indica que un pre-release está listo para ser probado con _users_in un entorno
controlado, todavía abierto a cambios y rediseño.
rc: (release candidate) se utiliza cuando el diseño está bloqueado y solo quedan por resolver cuestiones menores.
Por ejemplo:

2.0.0-alpha.1< 2.0.0-alpha.2< 2.0.0-beta.1< 2.0.0-rc.1< 2.0.0-rc.2< 2.0.0< 2.0.1< 2.1.0<3.0.0-alpha.1
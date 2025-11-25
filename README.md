# Arc-Net

Arc-Net es una aplicación de escritorio multiplataforma diseñada para centralizar la administración y supervisión de un ecosistema personal o técnico compuesto por múltiples dispositivos, servidores, procesos y servicios distribuidos. Su finalidad es proporcionar una interfaz unificada para ejecutar acciones de control, monitoreo y gestión sin depender de múltiples herramientas aisladas.

## Propósito del Proyecto

El objetivo principal de Arc-Net es ofrecer un centro de control integral que permita a un usuario administrar servicios locales y remotos, supervisar el estado de dispositivos conectados, gestionar contenedores, interactuar con repositorios Git y acceder a almacenamiento en red, todo desde una plataforma coherente y extensible.

## Alcance General

Arc-Net proporciona funcionalidades orientadas a:

- Supervisión de dispositivos y recursos.
- Control de servicios remotos (Docker, APIs locales, procesos del sistema).
- Gestión de archivos y almacenamiento en red.
- Sincronización de datos entre máquinas.
- Administración de repositorios Git.
- Registro y consulta de eventos del ecosistema.
- Integración con herramientas internas o externas mediante API.

El alcance está diseñado para crecer progresivamente, permitiendo agregar nuevos módulos según necesidad técnica o evolutiva.

## Arquitectura Tecnológica

El proyecto se construirá utilizando:

- Electron (aplicación de escritorio).
- React (interfaz de usuario).
- Flask (backend modular y desacoplado).
- Comunicación mediante API REST.
- Integración con servicios externos: SSH, Docker Remote API, Syncthing REST, Git.

Esta arquitectura permite despliegue multiplataforma, separación clara entre frontend y backend, escalabilidad y capacidad de migración futura.

## Características Planeadas

- Panel general de ecosistema.
- Visualización de estado de dispositivos y recursos.
- Gestión de contenedores Docker.
- Control de servicios remotos.
- Exploración y administración de archivos en red.
- Módulo de sincronización entre dispositivos.
- Registro y auditoría de eventos.
- Gestión de repositorios Git: creación, clonación, branches y operaciones comunes.
- Configuración avanzada para integración con red y servicios.

## Estado Actual del Proyecto

Arc-Net se encuentra en fase inicial de planificación bajo metodología xp

## Licencia

MIT License.

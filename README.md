# Arc-Net

Arc-Net is a cross-platform desktop application designed to centralize the administration and monitoring of a personal or technical ecosystem composed of multiple devices, servers, processes, and distributed services. The purpose of the application is to provide a unified interface for performing control, supervision, and management tasks without relying on isolated or fragmented tools.

## Project Purpose

Arc-Net aims to deliver a comprehensive control center that enables users to manage local and remote services, monitor device status, operate Docker containers, interact with Git repositories, and access network-based storage from a single, coherent, and extensible platform.

## Scope Overview

The scope of Arc-Net includes:

- Monitoring of devices and system resources.
- Remote service control (Docker, local APIs, system processes).
- Network storage access and file management.
- Data synchronization across devices.
- Git repository administration (creation, cloning, branching, and common operations).
- Event logging and auditing.
- Integration with external systems through APIs.

The system is designed to evolve progressively, allowing expansion into new modules as needed.

## Technology Stack

Arc-Net is developed using:

- **Electron** for the desktop environment.  
- **React** for the user interface.  
- **Flask** for a modular, decoupled backend.  
- **REST API** communication.  
- Integration with external services such as SSH, Docker Remote API, Syncthing REST, and Git.

This architecture provides cross-platform deployment, clear separation between frontend and backend, maintainability, and long-term scalability.

## Planned Features

- Global ecosystem dashboard.
- Device and resource status visualization.
- Docker container management.
- Remote service and process control.
- Network storage file explorer.
- Device synchronization module.
- Event logging and auditing.
- Git repository management.
- Advanced configuration options.


## License

MIT License.

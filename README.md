# TFG-2ASIR – Implementación de infraestructura crítica

## Descripción del proyecto

Este proyecto consiste en diseñar e implementar una infraestructura informática virtualizada para centralizar servicios IT, mejorar la seguridad de la red y automatizar la gestión de incidencias.

La infraestructura se desplegará sobre **Proxmox VE**, utilizando máquinas virtuales y contenedores para alojar los distintos servicios.

## Objetivo

Crear un entorno centralizado, seguro y eficiente que permita administrar recursos informáticos y facilitar el soporte técnico mediante herramientas de gestión, automatización e inteligencia artificial.

## Tecnologías previstas

- **Proxmox VE:** plataforma de virtualización.
- **CasaOS y Docker:** administración y despliegue de aplicaciones en contenedores.
- **Pi-hole:** filtrado DNS y bloqueo de dominios no deseados.
- **GLPI:** gestión de incidencias y solicitudes del CAU.
- **n8n:** automatización e integración de servicios.
- **Llama 3.3 70B mediante Groq:** agente de IA para analizar y clasificar incidencias.

## Alcance inicial

La primera fase contempla preparar el entorno de virtualización, desplegar los servicios principales y estudiar su integración. Como línea de trabajo, se plantea conectar GLPI con n8n y un agente de IA para clasificar tickets, proponer respuestas automáticas cuando sea posible y derivar al técnico los casos que requieran intervención humana.

La configuración y las funcionalidades se irán documentando conforme avance el desarrollo.

## Estructura actual

- `README.md`: presentación, objetivos y tecnologías del proyecto.
- `TFG-2 ASIR/`: documentación inicial del proyecto en PDF.

## Autores

- Pablo Gómez
- Izan Villalba

## Estado del proyecto

**Fase inicial:** documentación y definición del alcance. Este repositorio recogerá la evolución del proyecto y sus sucesivas versiones.

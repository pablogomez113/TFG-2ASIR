TFG-2ASIR – Implementación de Infraestructura Crítica

Descripción del proyecto

Este proyecto consiste en el diseño, configuración e implementación de una infraestructura informática orientada a la gestión de servicios IT en pequeñas y medianas empresas.

La infraestructura está basada en Proxmox VE como plataforma principal de virtualización, desde la que se despliegan y administran diferentes servicios mediante máquinas virtuales y contenedores.

El objetivo principal es crear un entorno centralizado, seguro y eficiente que permita gestionar los recursos informáticos, mejorar la seguridad de la red y automatizar tareas habituales de administración de sistemas.

Tecnologías utilizadas

Proxmox VE: plataforma de virtualización para gestionar servidores, máquinas virtuales y contenedores.

CasaOS: entorno de administración de aplicaciones y servicios mediante contenedores Docker.

Pi-hole: servicio DNS para bloquear publicidad, rastreadores y dominios no deseados.

GLPI: sistema de gestión de incidencias y solicitudes del Centro de Atención al Usuario (CAU).

n8n: herramienta de automatización para conectar servicios y crear flujos de trabajo.

Inteligencia Artificial: integración de un agente basado en Llama 3.3 70B mediante Groq para analizar, clasificar y gestionar incidencias.

Funcionamiento del proyecto

Uno de los aspectos principales es la integración de GLPI con n8n y un agente de inteligencia artificial.

El sistema permite detectar nuevos tickets, analizar su contenido y clasificarlos según el tipo de incidencia. Las consultas que pueden resolverse mediante instrucciones técnicas reciben una respuesta automática, mientras que los problemas que necesitan intervención humana se notifican al técnico responsable.

De esta forma, se consigue reducir el trabajo manual y mejorar la gestión de las incidencias informáticas.

Objetivos

Implementar una infraestructura virtualizada con Proxmox VE.

Centralizar diferentes servicios informáticos.

Mejorar la seguridad y el control del tráfico de red.

Gestionar incidencias mediante GLPI.

Automatizar procesos utilizando n8n.

Integrar inteligencia artificial en la gestión del CAU.

---
layout: default
title: Inicio
nav_order: 1
description: "GitHub Pages for Proxmox Tutorials."
permalink: /
---

## Proxmox VE

*Proxmox Virtual Environment, o Proxmox VE, entorno de virtualización de servidores de código abierto. Está en distribuciones GNU/Linux basadas en Debian con una versión modificada del Kernel RHEL y permite el despliegue y la gestión de máquinas virtuales y contenedores*

### Requisitos

* Procesador en 64bits (Intel EMT64 ó AMD64), de preferencia con múltiples núcleos

* Tarjeta Madre con soporte para virtualización (Intel VT ó AMD-V) 2 GB en RAM, solo servicios PVE.
    
* Discos duros rápidos (SSD)
    
* Soporte para RAID por hardware o ZFS
    
* Tarjetas de red Gbit (Cantidad según la configuración de almacenamiento externo y/o cluster)

### Introduccion a Proxmox como Hypervisor

*Maximizar el uso de sus recursos existentes, reducir el costo de hardware y una rápida implementación de servidores, es necesario contar un una solución estable y poderosa para la administración centralizada en virtualización.*

![Proxmox](https://raw.githubusercontent.com/Lucho00Cuba/Proxmox/main/src/Proxmox.jpg)

### Conociendo Proxmox

* **Administrador Web GUI** se basa en el marco de JavaScript ExtJS y puede usarla con cualquier navegador moderno, para configurar los servidores físicos, clusters, máquinas virtuales, respaldos y restauracion, snapshots. No es necesario instalar aplicaciones de terceros

* **Virtualización para la mayoría de Sistemas Operativos**, en versiones de 32 y 64bits. Linux en todas sus distribuciones, Microsoft desde windows 98 hasta windows 10 y windows server desde 2000 hasta 2019, Solaris, AIX, entre muchos más compatibles con KVM

* **Máquina virtual basada en kernel (​KVM)** es una solución para implementar virtualización sobre Linux.  Puede funcionar en hardware x86/x86_64 y es necesario que el microprocesador tenga soporte de virtualización ya sea Intel VT-x o AMD-V

* **Virtualización basada en contenedores (LXC)**, es una alternativa para ejecutar máquina Linux en espacios separados.  A diferencia de la virtualización KVM este funciona como un módulo agregado al servidor físico y hace uso directo del hardware (también conocido como Paravirtualización

* **Los Respaldos** se administran a través de su interfaz Web.  Puede efectuar un respaldo de forma inmediata o programado.  La restauración es simple, solo debe de seleccionar el backup a restaurar y listo

* **Alta Disponibilidad** con al menos 3 nodos o equipos con proxmox en cluster, si alguno de los nodos falla, las maquinas virtuales migran en automatico hacia los otros nodos

* **Firewall** es completamente personalizable y permite configuraciones complejas a través de la conosla web o linea de comandos


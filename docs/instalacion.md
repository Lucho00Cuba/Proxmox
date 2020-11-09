---
layout: default
title: Empezar
nav_order: 2
---

## Empezar a usar Proxmox VE

* VMware 15.5 Pro o algun virtualizador
* Imagen ISO de Proxmox
* Red con Acceso a Internet

## Instalacion

**La instalacion es sencilla de seguir los pasos. Aqui os dejo el video de la instalacion y recorido por su interfaz web**

[Instalacion Proxmox](https://youtu.be/9RJEmG5y9kQ){: .btn .btn-green}

## Caracteristicas

### Almacenamiento

_El modelo de almacenamiento Proxmox VE es muy flexible. Las imágenes de máquinas virtuales pueden almacenarse en una o varios almacenamientos locales, o en almacenamiento compartido como NFS o iSCSI (NAS, SAN). No hay límites, y se puede configurar tantos grupos de almacenamiento como se desee. Puede usar todas las tecnologías de almacenamiento disponibles para Debian.
Una de las principales ventajas de almacenar máquinas virtuales en almacenamiento compartido es la capacidad de migrar en vivo las máquinas en ejecución sin tiempo de inactividad, ya que todos los nodos del clúster tienen acceso directo a las imágenes de disco de VM. No hay necesidad de copiar datos de imagen de VM, por lo que la migración en vivo es muy rápida en caso de que falle el nodo donde se encuentra._

### Local

_Instalación local del sistema operativo Debian con el kernel de Proxmox VE, tenemos la posibilidad de utilizar RAID por hardware o software con ZFS, tener discos adicionales independientes del sistema._

### En Red

_El almacenamiento en red permite tener las VM en forma externa y compartida con otros nodos, para tener capacidades de alta disponibilidad y migración en vivo._

### Distribuido

_Proxmox VE tiene una compatibilidad estrechamente integrada para implementar una infraestructura de almacenamiento hiperconvergente. Se puede implementar y administrar las siguientes dos tecnologías de almacenamiento utilizando solo la interfaz web._
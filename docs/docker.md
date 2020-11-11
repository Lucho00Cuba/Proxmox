---
layout: default
title: Dockerizacion
nav_order: 3
---

## Dockerizacion

**_Docker es un proyecto de código abierto diseñado para ayudar a instalar aplicaciones usando contenedores de software. Según su página oficial_**

>“Los contenedores de docker envuelven una pieza de software en un sistema de archivos completo que contiene todo lo que necesita para ser ejecutada: código, tiempo de ejecución, herramientas del sistema, y librerías o cualquier cosa que pueda ser instalada en un servidor. Esto garantiza que el software siempre sera ejecutado de la misma manera independientemente de el ambiente.”

## Aplicaciones de Docker en Contenedores Proxmox VE

### Aportes de Docker

* Desarrollar aplicaciones usando contenedores, con todos sus beneficios
* Testear usando contenedores, mediante imágenes previamente configuradas
* Llegar a producción con contenedores, donde es recomendable el uso de orquestadores para aprovechar todo el potencial de los contenedores

_En el siguiente enlace encontraremos aplicaciones listas para ser levantadas en host's docker._

[Aplicaciones](https://github.com/Lucho00Cuba/Docker){: .btn .btn-green}

## Orquetadores Docker

* Kubernetes
* Docker Swarm
* Apache Mesos

_Un orquestador, como la propia palabra indica, lo podemos definir con un “director de orquesta”, donde cada uno de los elementos a dirigir es un contenedor. Un orquestador tiene sentido cuando tenemos que manejar un sistema con muchos contenedores implementados sobre multitud de servidores, es decir, en un entorno clusterizado. En este escenario el manejo manual se complica demasiado_

**Utilizaremos Docker Swarm a lo largo del Proyecto**
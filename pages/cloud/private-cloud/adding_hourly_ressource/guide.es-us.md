---
title: 'Añadir recursos por horas'
slug: anadir-recursos-por-horas
excerpt: 'Cómo añadir recursos con facturación por horas'
section: 'Funcionalidades de OVHcloud'
---

**Última actualización: 15/12/2020**

## Objetivo

La solución [Hosted Private Cloud](https://www.ovhcloud.com/es/enterprise/products/hosted-private-cloud/){.external} permite disfrutar de recursos con facturación por horas.

**Esta guía explica cómo añadir recursos por horas desde el panel de administración vSphere de Hosted Private Cloud.**

## Requisitos

* Tener contratado un servicio [Hosted Private Cloud](https://www.ovhcloud.com/es/enterprise/products/hosted-private-cloud/){.external}.
* [Conceder al usuario el permiso "Adición de recursos"](../cambiar-los-permisos-de-un-usuario/) para el datacenter correspondiente desde el [área de cliente de OVHcloud](https://ca.ovh.com/auth/?action=gotomanager) {.external}.
* Estar conectado al cliente vSphere.

## Procedimiento

### Seleccionar el recurso

En la pestaña `Hosts and Clusters`{.action} de la columna izquierda, seleccione un datacenter de la infraestructura. A continuación, abra la pestaña `Configure`{.action}.

![Añadir un host](images/addhost_01.png){.thumbnail}

Para añadir un host con facturación por horas, haga clic en `Add host`{.action}. Seleccione el modelo y haga clic en el botón `Next`{.action}. Si, en lugar de un host, quiere añadir un datastore, puede hacerlo desde el menú `Add storage...`{.action}.

![Añadir un host](images/addhost_03.png){.thumbnail}


### Confirmar la orden de pedido

Compruebe que la información relativa al pedido es correcta y haga clic en el botón `Next`{.action} para aceptar la orden de pedido.

![confirmar orden de pedido](images/addhost_04.png){.thumbnail}

### Seguir el progreso de la instalación

Una vez que haya aceptado la orden de pedido, puede consultar el progreso de la instalación del recurso.

![progreso instalacion](images/addhost_06.png){.thumbnail}

También puede seguir el progreso de la operación desde la zona de tareas recientes de vSphere, en la parte inferior de la pantalla.


## Más información

Interactúe con nuestra comunidad de usuarios en <https://community.ovh.com/en/>.
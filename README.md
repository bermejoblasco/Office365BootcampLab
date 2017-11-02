# Azure para Office365 Developers

## Overview
¿Como podemos integrar nuestro office365 con Azure? Hay dos formas básicas:
- WebHooks
- Servicios que se conectan a office365 y realizan operaciones.

Dentro de este último apartado nos encontramos con las LogicApps que nos permiten conectarnos a los diferentes productos de office365 entre otros y reaccionar a cambios ejecutando un flujo de trabjao.
También podemos integrar nuestras aplicaciones medainte AzureAD y hacer SSO.

## Objectives

Que aprenderemos:
- Realizar un SSO entre Office365 y una webapp.
- Crear la infraestructura necesaria de Azure
- Creación de una LogicApp y creación de un flujo.
- Primera aproximación a CosmosDB
- Envair notificaciones push.

## Prerequisites
Que es necesario:
- Un tenant de office365
- Una subscripción de Azure.

## Exercises

This hands-on lab includes the following exercises:
- [1- AzureADSSO](./1 - AzureAD SSO/readme.md)
- [2 - Creación infraestructura Azure](./2 - Creación infraestructura Azure/readme.md)
- [3 - Creación entorno Sharepoint](./3 - Creación entorno Sharepoint/readme.md)
- [4 - Creación Lógic App](./4 - Creación Lógic App/readme.md)
- [5 - Aplicación móvil](./5 - Aplicación móvil/readme.md)
- [6 - Creación AzureFunction y envío Push](./6 - Creación AzureFunction y envío Push/readme.md)

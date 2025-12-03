# NyxSOS-Examen-Final
Examen final de Programación Web
1. Descripción General del Proyecto

NyxSOS es un sistema de seguridad personal diseñado para reaccionar con rapidez y discreción en situaciones críticas. Está compuesto por dos partes principales:
una Aplicación Móvil desarrollada en React Native y una Consola Web de Monitoreo en React, ambas conectadas a un backend en tiempo real.

La aplicación permite activar una alerta de emergencia de manera completamente silenciosa, incluso con el teléfono bloqueado, mediante gestos o patrones táctiles que el usuario puede configurar. Desde ese momento, el sistema envía la ubicación en tiempo real y registra la ruta recorrida, de modo que los contactos de emergencia puedan visualizar toda la información desde una plataforma web segura.

Componentes Clave

Aplicación Móvil:
Pensada para reaccionar rápido y sin levantar sospechas. Permite la activación silenciosa, recopila datos de GPS, nivel de batería y envía la información al backend en tiempo real.

Consola Web de Monitoreo:
Un dashboard accesible mediante un enlace seguro, donde los contactos pueden ver un mapa interactivo con la ubicación actual del usuario y su historial de movimiento desde el inicio de la alerta.

Backend / API:
Desarrollado en Node.js + Express, y desplegado en Google Cloud Functions/Run. Utiliza Firestore (NoSQL) para almacenar la información en tiempo real de forma eficiente, fiable y escalable.

2. Entregables y Documentación Técnica

Todos los recursos solicitados para el examen —incluyendo documentación, diagramas y contenido del prototipo— están organizados en el repositorio correspondiente.

Documento Técnico Completo

El documento formal con la propuesta, arquitectura, análisis de costos, diseño de API y demás detalles técnicos se encuentra aquí:https://drive.google.com/file/d/1Jer4YqkATfTGd0P5ElQzIHXtRYCYsAyV/view?usp=sharing

Stack Tecnólogico

| Capa           | Tecnología        | Justificación                                               |
| -------------- | ----------------- | ------------------------------------------------------------ |
| Frontend Móvil | React Native      | Desarrolla rápido, permite acceso a módulos nativos.         |
| Frontend Web   | React             | Coherencia tecnológica, excelente para datos en tiempo real. |
| Backend / API  | Node.js + Express | Manejo eficiente de múltiples conexiones (GPS, alertas).     |
| Base de Datos  | Firestore (NoSQL) | Ideal para lecturas y escrituras constantes en tiempo real.  |

3.Link de Video Pitch y Presentación:

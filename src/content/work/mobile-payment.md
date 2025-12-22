---
title: Mobile Payment Gateway Dashboard
publishDate: 2023-11-01 00:00:00
img: /assets/davopagos.jpg
img_alt: Flutter mobile application for payment gateway management with charts and dark mode
description: |
  Aplicación móvil desarrollada en Flutter como frontend de una pasarela de pagos,
  orientada a la visualización, aprobación y rechazo de transacciones, con dashboards,
  autenticación por roles, gráficos interactivos y soporte para modo oscuro.
tags:
  - Flutter
  - Dart
  - Mobile Development
  - Payment Gateway
  - Data Visualization
  - NestJS
---

Este proyecto corresponde al **frontend móvil de una pasarela de pagos**, desarrollado como parte de un proyecto académico, donde estuve a cargo del **diseño e implementación completa de la aplicación móvil en Flutter**, conectada a un backend construido en **NestJS** mediante APIs REST.

La aplicación permite la gestión de transacciones bajo un **modelo de autenticación por roles**, diferenciando entre:
- **Usuarios administradores**, quienes pueden aprobar o rechazar transacciones, visualizar métricas y monitorear el estado general del sistema.
- **Usuarios clientes**, que acceden a su historial de pagos y estados de transacción de forma segura.

### Tecnologías y librerías utilizadas

- **Flutter & Dart**: desarrollo de la aplicación móvil multiplataforma.
- **Dio**: consumo de APIs REST y manejo de peticiones HTTP.
- **shared_preferences** y **flutter_secure_storage**: almacenamiento seguro de tokens, credenciales y sesiones.
- **fl_chart**: visualización de datos mediante gráficos interactivos (transacciones aprobadas, rechazadas, volumen de pagos, etc.).
- **flutter_animate**: animaciones suaves para mejorar la experiencia de usuario.
- **url_launcher**: redirecciones externas y soporte para enlaces de pago.
- **Dark Mode**: soporte completo para modo oscuro, mejorando la accesibilidad y experiencia visual.

### Enfoque en datos y experiencia de usuario

Uno de los puntos fuertes del proyecto es la **visualización clara de información financiera**, mediante dashboards móviles que permiten interpretar rápidamente el estado de la pasarela de pagos. Las gráficas ayudan a los administradores a tomar decisiones rápidas y a los usuarios a entender su historial de transacciones.

Se aplicaron principios de **UX/UI**, priorizando:
- claridad visual
- navegación intuitiva
- retroalimentación inmediata ante acciones críticas (aprobación/rechazo)

Este proyecto demuestra mi capacidad para desarrollar **aplicaciones móviles modernas**, integrar frontend con backend, trabajar con datos, seguridad y visualización, así como construir soluciones tecnológicas alineadas a escenarios reales del sector financiero.

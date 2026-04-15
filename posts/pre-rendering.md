---
title: 'Dos formas de Pre-renderizado'
date: '2025-01-06'
---

Next.js tiene dos formas de pre-renderizado: **Generación Estática** y **Renderizado del Lado del Servidor**. La diferencia radica en **cuándo** se genera el HTML de una página.

- La **Generación Estática** es el método de pre-renderizado que genera el HTML en el **momento de la compilación**. El HTML pre-renderizado se _reutiliza_ en cada solicitud.
- El **Renderizado del Lado del Servidor** es el método de pre-renderizado que genera el HTML en **cada solicitud**.

Es importante destacar que Next.js te permite **elegir** qué forma de pre-renderizado usar en cada página. Puedes crear una aplicación Next.js "híbrida" utilizando Generación Estática de manera predeterminada para la mayoría de las páginas, y reservando el Renderizado del Lado del Servidor para las otras.
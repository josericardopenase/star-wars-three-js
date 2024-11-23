# Proyecto de Animación Basada en Star Wars 🌌🚀


Este proyecto fue desarrollado para la asignatura de **Informática Gráfica (IG)**. El objetivo principal es crear una animación interactiva basada en el universo de Star Wars utilizando **Three.js** y herramientas de postprocesado. 

La animación incluye modelos 3D de naves icónicas como el Halcón Milenario, el Interceptor TIE, el Phantom, y la Estrella de la Muerte, junto con efectos visuales como **bloom**, movimientos complejos de cámara y un campo de asteroides generado proceduralmente.

---

## 📖 Introducción

El universo de Star Wars siempre ha inspirado creatividad debido a su riqueza visual y narrativa. Este proyecto busca recrear una pequeña escena interactiva donde diferentes naves espaciales interactúan entre sí en un entorno dinámico y espectacular.

La escena implementa:
- Movimiento complejo de las naves y la cámara utilizando interpolaciones (tweens).
- Modelos 3D cargados desde archivos GLTF.
- Efectos visuales como **Unreal Bloom** para realzar el brillo de las naves y balas.
- Procedimientos para generar un campo de asteroides.

---

## 🎯 Objetivos

1. Implementar animaciones suaves y realistas para las naves espaciales.
2. Aplicar técnicas de postprocesado para mejorar el impacto visual.
3. Generar y renderizar un entorno dinámico que evoluciona a medida que avanza la animación.
4. Explorar la integración de **Three.js** con interpolaciones para movimientos complejos.

---

## 🎥 Video

Aquí puedes ver una demostración de la animación creada. *(Incluir enlace al video si se sube a YouTube o cualquier plataforma)*

---

## 💻 Código

El código del proyecto está estructurado de la siguiente manera:

1. **Efectos Visuales**:
   - Se utiliza `UnrealBloomPass` para añadir un efecto de brillo a las naves y balas.
   - Se emplea un compositor de postprocesado para renderizar la escena con calidad mejorada.

2. **Interpolaciones (Tweens)**:
   - Las naves y la cámara se mueven siguiendo trayectorias calculadas mediante interpolaciones con la biblioteca `@tweenjs/tween.js`.

3. **Modelos 3D**:
   - Los modelos GLTF se cargan dinámicamente y se escalan según las necesidades de la escena.

4. **Entorno**:
   - Se genera un campo de asteroides procedural alrededor de la cámara en un momento específico de la animación.

El código completo se encuentra en el archivo principal del proyecto: [`main.ts`](./main.ts).

---

## 📋 Conclusión

Este proyecto ha sido una experiencia enriquecedora para explorar técnicas avanzadas de animación y renderizado en gráficos 3D. Trabajar con modelos complejos, efectos visuales y movimientos dinámicos ha permitido comprender mejor el potencial de herramientas como **Three.js** en la creación de entornos interactivos.

Star Wars ha sido el marco perfecto para desarrollar esta práctica debido a su estética icónica y su atractivo para implementar animaciones espaciales. 

¡Esperamos que disfrutes del resultado tanto como nosotros disfrutamos haciéndolo! 🌠

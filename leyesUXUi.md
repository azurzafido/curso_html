# leyes ux

# Apuntes: Leyes de UX/UI

Este archivo resume las leyes y principios más importantes de UX/UI para que puedas estudiarlos fácilmente y usarlos en proyectos de diseño web y apps.

---

## 1. Ley de Fitts

### Descripción
La **Ley de Fitts** dice que el tiempo que tardas en llegar a un objetivo con el cursor o el dedo depende de:
- La distancia al objetivo.
- El tamaño del objetivo.

Cuanto más grande y más cerca esté un botón, más rápido y fácil será hacer clic en él. [web:4][web:10]

### Ejemplos
- En un móvil, los botones grandes de “Llamar” o “Enviar mensaje” en la parte inferior de la pantalla.
- En un sitio web, los botones principales de “Inicio de sesión” o “Compra” en el centro de la página.

### Implicaciones para diseño
- Haz clicables grandes a los botones principales (Call to Action).
- Coloca elementos frecuentes cerca del punto de interacción habitual (por ejemplo, botón de menú en la esquina superior izquierda).

---

## 2. Ley de Hick

### Descripción
La **Ley de Hick** establece que el tiempo de decisión aumenta al crecer el número y la complejidad de las opciones. [web:4][web:10]

### Ejemplos
- Un menú de navegación con 15 opciones dificulta elegir rápidamente.
- Un formulario con 5 botones de acción (Enviar, Guardar, Guardar como borrador, Cancelar, Ayuda) hace que el usuario se bloquee.

### Implicaciones para diseño
- Limita el número de opciones visibles (por ejemplo, agrupar menús con subcategorías).
- Usa prioridades: muestra solo 1–3 acciones principales y el resto en “más opciones”.

---

## 3. Ley de Jakob (Ley de Jakob Nielsen)

### Descripción
**Ley de Jakob**: los usuarios pasan la mayor parte del tiempo en otros sitios, así que esperan que tu interfaz funcione como las que ya conocen. [web:4][web:10]

### Ejemplos
- Un icono de “lupa” se entiende como búsqueda porque es un patrón usado en muchas páginas.
- El menú hamburguesa (☰) ya se asocia con “menú” gracias a su uso masivo.

### Implicaciones para diseño
- Usa patrones estándar de navegación, iconos y disposición.
- No inventes flujos radicalmente nuevos si no los justificas con un gran beneficio de usabilidad.

---

## 4. Efecto estética‑usabilidad

### Descripción
Las interfaces estéticamente agradables se perciben como más fáciles de usar, incluso si no lo son. [web:4][web:13]

### Ejemplos
- Una app con colores limpios, tipografía legible y buen espaciado se siente más rápida y “buena”.
- Una web con diseño caótico y colores chocantes se percibe como lenta o confusa.

### Implicaciones para diseño
- Invierte tiempo en tipografía, color, alineación y jerarquía visual.
- Un buen diseño visual ayuda a que la experiencia se perciba como más fluida.

---

## 5. Ley de Miller (7 ± 2 elementos)

### Descripción
La memoria de trabajo del ser humano puede retener aproximadamente **7 ± 2 ítems** al mismo tiempo. [web:4][web:10]

### Ejemplos
- Un menú principal con 7–9 secciones máximo.
- Un formulario dividido en pasos de 3–5 campos, no 15 seguidos.

### Implicaciones para diseño
- Agrupa la información en bloques pequeños y lógicos.
- Usa secciones, cards, tabs o paginación para reducir la carga visual.

---

## 6. Ley de Tesler (Conservación de la complejidad)

### Descripción
La **Ley de Tesler** dice que todo sistema tiene una cierta complejidad **que no se puede eliminar**, solo trasladar de usuario al sistema (o al desarrollador). [web:4][web:10]

### Ejemplos
- Un CRM complejo: puedes ocultar pasos avanzados bajo “Configuración avanzada”.
- Una app de envíos: el algoritmo calcula rutas, pero el usuario solo ve “Calcular envío”.

### Implicaciones para diseño
- Automatiza cálculos y flujos complejos en el backend.
- Simplifica el flujo visible al usuario, pero no elimines funcionalidad necesaria.

---

## 7. Principios Gestalt aplicados a UI

Los principios de la **Escuela Gestalt** explican cómo el cerebro agrupa elementos visuales:

### Ley de proximidad
- Los elementos cercanos se perciben como un grupo. [web:4][web:11]  
**Ejemplo:** campos de “Nombre” y “Apellido” colocados juntos para que parezcan un bloque.

### Ley de similaridad
- Elementos con color, forma o tamaño parecidos se perciben con la misma función. [web:4][web:16]  
**Ejemplo:** todos los botones azules en la app son de “acción principal”.

### Ley de Prägnanz (simplicidad)
- El cerebro interpreta formas y diseños de la manera más simple posible. [web:4][web:16]  
**Ejemplo:** íconos limpios (lupa, casa, perfil) en lugar de dibujos complejos.

---

## 8. Modelo mental del usuario

### Descripción
El **modelo mental** es la idea que el usuario tiene de cómo funciona un sistema, basada en experiencias anteriores. [web:4][web:13]

### Ejemplos
- Si ya usas WhatsApp, esperarás que un chat tenga un cajón de texto abajo y botón de enviar a la derecha.
- Si un producto digital sigue ese modelo, el usuario entiende el flujo sin explicaciones.

### Implicaciones para diseño
- Alinea el diseño con lo que el usuario ya conoce (patrones de apps similares).
- Si cambias el flujo, añade pequeñas ayudas (tooltips, onboarding).

---

## 9. Ley de Parkinson y carga cognitiva

### Ley de Parkinson
Las tareas se expanden hasta llenar todo el tiempo disponible. [web:4]  
**En UX:** si el usuario tiene un formulario largo, tardará más y puede abandonar.

### Carga cognitiva
Es la cantidad de esfuerzo mental que necesita una persona para entender e interactuar con una interfaz. [web:4]

### Implicaciones
- Reduce pasos, labels largos y campos innecesarios.
- Usa progresos, pasos numerados y mensajes claros para que el usuario sepa “dónde está”.

---

## 10. Principio de Pareto (80/20)

### Descripción
Aproximadamente el **80 % de los resultados surgen del 20 % de las acciones**. [web:4]

### Ejemplos
- En una app de e‑commerce, el 80 % de las ventas vienen de 20 % de las funcionalidades principales: búsqueda, carrito y pago.
- En un dashboard, el 80 % de las decisiones se basan en 20 % de los gráficos.

### Implicaciones para diseño
- Optimiza primero las 2–3 características más usadas.
- No repartas el diseño de forma “igual” entre todas las funciones.

---

## 11. Umbral de Doherty

### Descripción
La **productividad del usuario se dispara** cuando la interacción con el sistema es tan rápida que ninguna parte tiene que esperar a la otra (respuesta < 400 ms). [web:4]

### Ejemplos
- Autocomplete que responde en tiempo real al escribir.
- Botones que no se quedan “congelados” al hacer clic.

### Implicaciones para diseño
- Optimiza tiempos de respuesta en acciones clave.
- Usa estados de carga (spinners, skeletons) si una operación es lenta.

---

## 12. Paradoja del usuario activo

### Descripción
Los usuarios no leen manuales, pero empiezan a usar el software de inmediato. [web:4]

### Implicaciones
- Diseña el producto para que sea **intuitivo** sin necesidad de guía.
- Usa onboarding rápido, tooltips contextuales y microcopia explicativa.

---

## 13. Principios adicionales útiles

### Regla de fin de pico
Las personas juzgan una experiencia sobre todo por su **punto álgido y cómo termina**, no por el promedio. [web:4]

- Un registro que termina con un mensaje de “¡Bienvenido!”, notificación o animación positiva se recuerda mejor.

### Sesgo cognitivo
Errores de pensamiento que influyen en decisiones de usuario. [web:4]

- Ejemplo: usar “Tú eres el 1000ᵉʳ usuario” para apoyar decisiones de compra.

---

## Cómo usar estos apuntes en tus proyectos

- **Al diseñar una app o web**, revisa:
  - ¿Honro patrones conocidos? (Ley de Jakob)
  - ¿He reducido opciones? (Ley de Hick)
  - ¿Son grandes y cercanos los botones clave? (Ley de Fitts)
  - ¿La información está agrupada claro? (Gestalt, Ley de Miller)
  - ¿La complejidad está del lado del sistema, no del usuario? (Ley de Tesler)

Este archivo te sirve como checklist y guía rápida para UX/UI en cualquier proyecto en Visual Studio Code. [web:4][web:10]
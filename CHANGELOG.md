# 📋 Changelog — Raspados Locos

Historial de cambios y mejoras del sitio web de **Raspados Locos**.
Repositorio: `raspadoslocos`

---

## [v1.3.0] — 2026-04-17

### ✨ Agregado
- **Simulador de carrito de compras** completamente funcional
  - Ícono 🛒 con contador de items en el navbar (badge rosa neón)
  - Animación *pop* en el contador al agregar productos
  - Panel lateral deslizable con lista de productos agregados
  - Botones **＋ / −** por producto para ajustar cantidades
  - Eliminación automática del item al llegar a 0 unidades
  - **Total acumulado** en tiempo real (amarillo neón)
  - Botón **"¡Ordenar ahora!"** — simula la compra, muestra confirmación y vacía el carrito
  - Botón **"Vaciar carrito"** para limpiar todo de golpe
  - Overlay oscuro al abrir el panel (click fuera para cerrar)
  - **Toast de notificación** animado al agregar cada producto
- `data-name`, `data-price` y `data-emoji` agregados a los botones de cada producto
- Enlace **"Equipo"** alineado verticalmente con el resto del navbar (`align-items-lg-center`)

### 🎨 Diseño
- Panel del carrito con borde cian neón y scroll interno estilizado
- En móvil el panel ocupa el **100% del ancho** de pantalla para mejor experiencia táctil
- Animación `slideIn` en cada item al ser agregado al carrito

---

## [v1.2.0] — 2026-04-17

### ✨ Agregado
- **Sección Equipo / Founders** con tarjetas estilo corporativo
  - Katherine Armenta — CEO & Co-Founder (destacada en fila superior)
  - Luz Regina Zavala — Chief Marketing Officer
  - Jesus Edgar Zamora — Chief Operations Officer
  - Elena Sofia Camacho — Chief Creative Officer
  - Ivan Aldama — CISO & Co-Founder
- **Favicon** (ícono de pestaña del navegador) con emoji 🍧 usando SVG inline
- Enlace **"Equipo"** agregado al navbar de navegación

### 🐛 Corregido / Actualizado
- Copyright actualizado de **2025** a **2026**
- Mejoras de **responsividad** para iPad y dispositivos móviles:
  - Media query tablet `max-width: 991px` — ajuste de fuentes, padding y navbar
  - Media query móvil `max-width: 575px` — tarjetas compactas, emojis y botones optimizados para pantalla táctil

---

## [v1.1.0] — 2026-04-17

### ✨ Agregado
- Estructura inicial completa de la landing page con HTML, CSS y Bootstrap 5
- **Navbar** fija con scroll suave a cada sección
- **Sección Hero** con animación flotante y llamada a la acción
- **Sección Nosotros** con descripción de la empresa
- **Sección Eslogan** con caja destacada: *"Cuando hay malos días, Raspados Locos te mejorará tus días"*
- **Sección Productos** con 3 tarjetas:
  - 🍓 El Más Fresa — $35 MXN
  - 🍧 Raspado Loco — $40 MXN
  - 🥭 MangoMambo — $45 MXN
- **Footer** con eslogan y copyright
- Animaciones de scroll reveal en todas las secciones
- Compatible con **GitHub Pages** (`index.html` en rama `main`)

### 🎨 Diseño
- Tema **neon pop oscuro** — fondo `#0d0d1a` con acentos en rosa, cian, amarillo y verde neón
- Tipografías: **Boogaloo** (display) + **Nunito** (cuerpo) via Google Fonts
- Fondo con gradientes radiales animados
- Tarjetas de producto con efecto hover y sombras de color

---

## 🗺️ Pendientes / Ideas futuras

- [ ] Agregar logo oficial cuando esté disponible (reemplazar emoji del navbar y hero)
- [ ] Agregar redes sociales a las tarjetas del equipo
- [x] ~~Sección de contacto o formulario de pedido~~ → reemplazado por simulador de carrito v1.3.0
- [ ] Galería de fotos de los productos
- [ ] Sección de reseñas o testimonios de clientes
- [ ] Animación de entrada más elaborada en el hero (typewriter, partículas, etc.)
- [ ] Versión en modo claro (light mode)

---

*Proyecto escolar — Raspados Locos © 2026*

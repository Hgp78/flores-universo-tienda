# Flores Universo — V4

Esta versión mantiene como referencia principal el diseño vertical aprobado por el usuario.

### Cambios confirmados
- Se conserva la composición vertical y el aspecto profesional de la referencia.
- La bandera de Nicaragua se usa como imagen del diseño aprobado.
- La bandera queda estática: NO tiene animación.
- No se coloca texto, sello, badge ni otro elemento encima de la bandera.
- Se conservan los tres botones Payhip:
  - Cocina Nica: `Cq5Vf`
  - Bebidas Nica: `y0YJb`
  - Postres: `dpizf`
- Los PDF no están incluidos en GitHub; permanecen en Payhip.

### Publicación
El repositorio es estático y listo para GitHub Pages.

## V5 — Idiomas
Se agregó selector de idioma en el encabezado con:
- 🇳🇮 Español
- 🇺🇸 English
- 🇧🇷 Português
- 🇫🇷 Français
- 🇮🇹 Italiano

La selección se guarda en `localStorage` del navegador para conservar el idioma elegido en visitas posteriores.
La traducción cubre la navegación, portada, colección, productos, beneficios, sección Sobre Nosotros y pie de página.


## V6 — Carrito de compras
Se reemplazó el icono pasivo del carrito por un carrito funcional en el sitio:
- Permite agregar los tres libros.
- Evita duplicar el mismo libro.
- Muestra cantidad y total.
- Permite eliminar artículos.
- Guarda temporalmente el carrito en `localStorage`.
- El botón "Pagar en Payhip" genera un checkout de Payhip con todos los productos seleccionados.
- Mantiene los cinco idiomas.
- La bandera continúa estática.

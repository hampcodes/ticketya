# SPEC: TicketYa

## Objetivo
Maquetar con HTML y CSS las 5 pantallas del flujo de compra de entradas,
en versión móvil y web, iguales al diseño de Figma.

## Diseño
Figma: https://www.figma.com/design/r3YZG630IjrAFYequXHPDO/TicketYa?node-id=1-2&t=VIlGbfQKQwBpIBXv-1
Páginas: guia de estilo, mockups movil, mockups desktop y diagrama de flujo.

## Pantallas
1. Eventos             index.html         css/eventos.css
2. Detalle del evento  evento.html        css/evento.css
3. Elegir entradas     entradas.html      css/entradas.css
4. Datos y pago        pago.html          css/pago.css
5. Confirmación        confirmacion.html  css/confirmacion.css

## Archivos compartidos
css/tokens.css       Variables del style guide (colores, textos, espacios, radios) y estilos base
css/componentes.css  Botón, chip, campo, insignia y tarjetas

## Reglas
- Solo HTML y CSS, sin librerías.
- HTML semántico (header, nav, main, section, article, aside, footer) y un solo h1 por página.
- Todas las imágenes llevan alt y cada campo de formulario lleva su label.
- Colores, espacios y radios salen de las variables de tokens.css.
- Primero móvil (390 px) y luego escritorio con @media (min-width: 1024px).

## Criterios de aceptación
- [ ] Cada pantalla se ve igual que su mockup en 390 px y en 1440 px.
- [ ] No hay estilos en línea ni colores sueltos.
- [ ] Otra persona del equipo revisó el código.

## Fuera de alcance
Todo lo que no sea HTML y CSS.

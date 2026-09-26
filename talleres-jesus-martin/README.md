# Talleres Jesús Martín — boceto de landing (vista previa)

Web de muestra de una sola página para enseñar al taller antes de la contratación. **No es la versión final**: lleva una marca fija "Vista previa — diseño de muestra" y una nota en el pie.

## Cómo verla

Abrir `index.html` en cualquier navegador. Es un único archivo autocontenido (tipografías incrustadas, coche en SVG), así que funciona sin conexión; solo el mapa de Google necesita internet.

- Botón ↻ de la marca de agua: repite la animación de portada (útil al enseñarla en pantalla).
- La página lleva `noindex` para que no la indexen buscadores mientras sea un boceto.

## Datos usados y fuentes

Google Maps no era accesible desde el entorno donde se preparó el boceto; los datos se cruzaron en directorios que replican la ficha y en la web actual del taller:

| Dato | Valor | Estado |
| --- | --- | --- |
| Dirección | C/ Rubén Darío, s/n · Pol. Ind. San Cayetano · 18194 Churriana de la Vega (Granada) | Coincide en todas las fuentes |
| Teléfono | 958 55 28 14 (un directorio da también 958 55 33 96) | Confirmar si el segundo sigue activo |
| Horario | L–V 9:00–14:00 y 16:00–19:00 | Confirmar sábados (se muestra "Cerrado") |
| Valoración | 4,3 / 5 con 68–71 opiniones según la fuente → "más de 70" | Actualizar con la cifra actual de la ficha |
| Apertura | 1991 (+30 años) | Coincide en las fuentes |
| Servicios | Mecánica, motor, cajas de cambio, culatas, turbo, inyectores, frenos, suspensión, aceite, neumáticos, alineación, diagnosis, chapa y pintura, pre-ITV/ITV, descarbonización con hidrógeno (centro FlexFuel), recogida de vehículos, ozono, homologaciones, tapicería, venta de vehículos | Web del taller y directorios |
| Coordenadas del mapa | 37.1457467, -3.6344155 | Del enlace de Google Maps |

"Lo que más se repite" en opiniones (profesionalidad, rapidez, atención al detalle, honestidad en el diagnóstico) sale del resumen de opiniones de los directorios, no de reseñas leídas una a una.

## Pendiente antes de enseñarla

1. **Reseñas reales de Google.** La sección muestra huecos marcados como pendientes. Para rellenarla, copiar 4–6 reseñas de la ficha en el array `RESENAS` del `<script>` de `index.html`:
   ```js
   const RESENAS = [
     { autor: 'Nombre', estrellas: 5, fecha: 'hace 2 meses', texto: 'Texto literal de la reseña' },
   ];
   ```
   Con 4 o más reseñas se activa un carrusel vertical automático.
2. Logo del taller (ahora hay un monograma "JM" provisional) y, si se quiere, fotos reales del taller.
3. Cómo se gestionarán las citas en la versión final (llamada, WhatsApp, formulario por correo…). El formulario actual es de demostración y no envía datos.

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
| Horario | L–V 9:00–14:00 y 16:00–19:00, fin de semana cerrado | Web oficial y ficha de Google. La ficha de InterTaller (probablemente antigua) dice L–V hasta las 20:30 y sábados 9:00–14:00 |
| Valoración | 4,3 / 5 con 68–71 opiniones según la fuente → "más de 70" | Actualizar con la cifra actual de la ficha |
| Apertura | 1991 (+30 años) | Coincide en las fuentes |
| Servicios | Mecánica, motor, cajas de cambio, culatas, turbo, inyectores, frenos, suspensión, aceite, neumáticos, alineación, diagnosis, chapa y pintura, pre-ITV/ITV, descarbonización con hidrógeno (centro FlexFuel), recogida de vehículos, ozono, homologaciones, tapicería, venta de vehículos | Web del taller y directorios |
| Coordenadas del mapa | 37.1457467, -3.6344155 | Del enlace de Google Maps |
| Acceso | A-44, salida 138 (Ogíjares), vía de servicio | Directorios (reparatucoche, abat) |
| Redes | Taller de la red InterTaller · centro FlexFuel | InterTaller y FlexFuel |
| Venta de coches | Revisados por sus mecánicos y con garantía en todas las ventas | Web del taller |
| Email | talleresjesusmartin@gmail.com (directorio) · jesusmartin@intertaller.com (InterTaller) | No se muestra en la web; confirmar cuál usan |

### Reseñas

Seis reseñas reales de la ficha de Google (capturas facilitadas), copiadas literalmente en el array `RESENAS` de `index.html`; solo se han normalizado espacios tras comas y puntos. Donde Google recorta el texto ("Más") se muestra lo visible y un enlace "Leer completa en Google". Los apellidos se muestran abreviados.

Lo que se repite en ellas: honradez, trato amable y cercano, negocio familiar (Jesús y su mujer), rapidez, que te explican la avería y clientes que vienen de lejos (Costa Tropical, "estábamos de paso"). Único matiz negativo: una reseña dice que el precio está "un poco por encima de la media", aunque "siempre tienen algún detalle para rebajarlo".

### Empresa

- Talleres Jesús Martín S.L. (CIF B24893737, CNAE 4520 mantenimiento y reparación de vehículos).
- Talleres Hermanos J. Martín S.L., constituida en 2002, en la misma dirección y con el mismo teléfono.
- En la misma dirección figura el "Desguace Talleres Hnos. Jesús Martín" (recambios, bajas, tasaciones). No se ha incluido en la web hasta confirmar que forma parte del mismo negocio.

## Pendiente antes de enseñarla

1. Confirmar la cifra actual de opiniones y la valoración media de la ficha, y si se quieren nombres completos en las reseñas.
2. Logo del taller (ahora hay un monograma "JM" provisional) y, si se quiere, fotos reales del taller.
3. ¿El desguace de la misma dirección es suyo? Se podría añadir "recambios de desguace" y "bajas de vehículos".
4. Las citas se piden por teléfono (sección "Pide tu cita": llamar, copiar número, rutas en Google Maps / Waze / Apple Maps y códigos QR para el móvil). Si el taller quiere recibirlas también por WhatsApp o email, habría que añadirlo con su número o correo.

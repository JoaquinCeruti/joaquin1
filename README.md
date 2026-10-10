# Teorema de Bernoulli en 3D

Demostración interactiva del teorema de Bernoulli en un tubo de Venturi, hecha con Three.js para usar en clase.

Abre `index.html` en el navegador (necesita conexión a internet para cargar Three.js y las fuentes).

## Qué se ve

- **Partículas de agua** que aceleran en la garganta (azul = lentas, naranja/amarillo = rápidas).
- **Tubo de vidrio** coloreado según la presión (violeta = baja, cian = alta).
- **Piezómetros** (presión estática) y **tubos de Pitot** (presión total) en los puntos A, B y C.
- **Línea de energía** y **línea piezométrica**.
- **Barras de energía**: P + ½ρv² + ρgz da el mismo total en A, B y C.
- **Recorrido guiado** en 5 pasos: continuidad, velocidad frente a presión, altura y conservación.

## Controles

Caudal, diámetro de la garganta, desnivel de la salida, ritmo de la animación, capas visibles y vistas de cámara predefinidas.

---

# Silo bivalva en 3D

Abrí `silo-bivalva.html` en el navegador (necesita internet para cargar Three.js desde el CDN).

- **Armado por etapas:** platea, patas y placas base, tolvas y bocas, chapas y tabique, anillos, perfiles, techo.
- **Llenado de maní** (volumen que sube + granos que caen por la boca de carga) y **descarga** por las dos bocas.
- **Controles:** cámara orbitable, pausar, reiniciar, chapa semitransparente, etiquetas y velocidad. Teclas: Espacio, R, T.

Notas de modelado: patas en las 4 esquinas; perfiles verticales con SHS 80×80 adoptado (sección no especificada);
la tolva baja 0,5 m hasta una boca de 0,30 × 0,30 m, así que sus caras quedan a ~24° y ~38° (≈30° en promedio).

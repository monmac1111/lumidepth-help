# Ayuda

**Lumidepth Player VR** reproduce en tu Meta Quest vídeos VR180, VR360 y 2D guardados en tu PC o en el NAS de tu casa. Un modelo de IA estima la profundidad de cada fotograma, de modo que los objetos cercanos y lejanos se desplazan con naturalidad al mover la cabeza.

## Requisitos

- Windows 10 / 11 (64 bits)
- NVIDIA GeForce RTX 3060 o posterior (series RTX 30 / 40 / 50)
- Visor Meta Quest conectado mediante Meta Quest Link (cable) o Air Link
- Vídeo: MP4, MKV, MOV, WebM. H.265 (HEVC), H.264 (hasta 4K), AV1, VP9, ProRes
- De 8 a 12 bits, 4:2:0 / 4:2:2 / 4:4:4, HDR (HDR10, HLG). Los vídeos HDR se muestran en SDR
- En las series RTX 30 / 40, 4:2:2 y ProRes se decodifican en la CPU, por lo que es posible que 8K a 60 fps no se reproduzca con fluidez (la serie RTX 50 los decodifica en la GPU)

## Primeros pasos

1. Abre la aplicación Meta Quest Link en tu PC y conecta tu Quest con Link o Air Link.
2. Inicia Lumidepth Player VR desde la Biblioteca de tu Quest.
3. Las unidades de tu PC aparecen en la lista. Para explorar una carpeta compartida de un NAS, asígnala como unidad de red en Windows.
4. Selecciona un vídeo con el gatillo derecho para empezar a reproducirlo. La primera vez que uses el 3D, la IA se prepara para tu PC, lo que puede tardar unos minutos (después es inmediato).

## Controles

| Botón | Biblioteca | Durante la reproducción |
|---|---|---|
| Gatillo derecho | Elegir / mantener y mover para desplazar | Mostrar la barra de reproducción / pulsar un botón |
| A | Subir una carpeta | Volver a la biblioteca |
| B | Subir una carpeta | Activar o desactivar el 3D |
| Y | – | Reproducir / pausar |
| X | – | Mostrar / ocultar la línea de estado |
| Stick derecho izquierda/derecha | – | −10 s / +10 s |
| Stick izquierdo izquierda/derecha | – | −60 s / +60 s |
| Pulsar el stick derecho | – | Centrar |
| Mantener el agarre derecho y mover | – | Girar el vídeo |

## Barra de reproducción y ajustes

Durante la reproducción, aprieta el gatillo derecho para mostrar la barra de reproducción donde apuntes. Incluye volumen, zoom, 3D sí/no, centrar y ajustes (⚙).

El panel de ajustes tiene tres páginas:

- **Pantalla**: brillo, nitidez, antialiasing
- **3D**: profundidad, alineación de bordes, bordes, relleno de huecos, estabilización, frecuencia de actualización, ventana, 3D para 2D/mono
- **Formato**: proyección (180°, 360°, plano) y disposición (lado a lado, arriba/abajo, única). Se detecta automáticamente a partir del nombre del archivo y la relación de aspecto; elígela manualmente solo si la imagen no se ve bien (se aplica únicamente al vídeo actual).

El efecto de profundidad funciona mejor con vídeos VR180 lado a lado.

## Solución de problemas

- **"Tu Meta Quest no está conectado"**: conecta tu Quest con Link o Air Link y vuelve a intentarlo.
- **"No se encontró ninguna GPU NVIDIA"**: actualiza el controlador de NVIDIA. Se necesita una GPU RTX serie 30 o posterior.
- **El 3D muestra "no disponible"**: es posible que a la GPU le falte memoria. Cierra otras aplicaciones.
- **La imagen se ve duplicada o dividida**: elige la proyección y la disposición en la página Formato de los ajustes.

Contacto: [hello@monneural.dev](mailto:hello@monneural.dev)

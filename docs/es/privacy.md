# Política de privacidad

**Lumidepth Player VR**

- Fecha de entrada en vigor: 19 de octubre de 2026
- Última actualización: 28 de octubre de 2026 (se añadieron los servidores de la red doméstica)
- Proveedor: mon neural
- Contacto: [hello@monneural.dev](mailto:hello@monneural.dev)

Esta es una traducción. En caso de discrepancia, prevalece la [versión en inglés](../en/privacy.md).

## 1. Información que recopilamos

No recopilamos ninguna información personal, datos de uso ni contenido de vídeo. La aplicación no se comunica con nuestros servidores y no contiene publicidad ni herramientas de análisis.

## 2. Datos guardados en tu PC

Los siguientes datos se guardan únicamente en tu PC y nunca se envían a ninguna parte:

- Ajustes (opciones de pantalla y 3D, y las direcciones de las carpetas compartidas y servidores que registres)
- Registros de diagnóstico (no contienen nombres ni ubicaciones de archivos de vídeo)
- Datos del modelo de profundidad de IA optimizados para tu GPU
- Miniaturas que se muestran en la biblioteca de vídeos

Al desinstalar la aplicación y eliminar la carpeta `%LOCALAPPDATA%\LumidepthPlayerVR`, se borran todos estos datos.

## 3. Plataforma de Meta

La aplicación se distribuye a través de la tienda de Meta y utiliza la plataforma de Meta para verificar tu compra. La información relacionada la gestiona Meta conforme a la [Política de privacidad de Meta](https://www.meta.com/legal/privacy-policy/). Nosotros no la recibimos.

## 4. Red

Aparte de la verificación de compra, la app solo se conecta a:

- Unidades y carpetas compartidas que abres tú mismo (por ejemplo, un NAS de tu red doméstica)
- Servidores que registras tú mismo (WebDAV, Jellyfin)
- Servidores multimedia (DLNA) encontrados en tu red doméstica. Para encontrarlos, la app envía una solicitud de descubrimiento (SSDP) en tu red doméstica.

Los nombres de usuario y contraseñas de los servidores se leen de lo que guardaste en el Administrador de credenciales de Windows. La app no los guarda y nunca los escribe en los registros.

La app se identifica ante los servidores Jellyfin con un ID de este PC, para que el servidor no muestre un dispositivo nuevo cada vez. El ID es un hash derivado del ID del equipo de Windows; el ID del equipo en sí no se envía.

## 5. Menores

La aplicación no recopila información de menores.

## 6. Cambios

Publicaremos cualquier cambio de esta política en esta página.

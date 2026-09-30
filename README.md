# RESONA R1 · Consola de audio háptica

Gemelo digital interactivo de un dispositivo físico de audio, modelado en Blender y llevado a la web con Three.js.

**Autor:** Mario Sánchez Villanueva
**Curso:** Fabricación Digital · Facultad de Diseño, Universidad del Desarrollo
**Demo en línea:** https://TU_USUARIO.github.io/resona-r1/

## El dispositivo

RESONA R1 se compone de cinco piezas modeladas por separado:

| Pieza | Función |
|---|---|
| Bocina | Pieza principal. Reproduce el audio y pulsa con los graves. |
| Pantalla | Muestra la canción en reproducción, el progreso y el espectro. |
| Joystick | Cambia de canción y controla la reproducción. |
| Sliders | Regulan volumen, agudos y graves. |
| Módulo de vibración | Devuelve el ritmo de la música como vibración háptica. |

## Cómo usarlo

1. Abre la demo en un navegador de escritorio (Chrome, Edge o Firefox).
2. Arrastra para orbitar y usa la rueda del mouse para acercar.
3. Toca la bocina o el botón de reproducir para iniciar el sonido. Los navegadores exigen un clic antes de reproducir audio.
4. Mueve los sliders 3D o abre **Mezcla** en la barra inferior para regular volumen, agudos y graves.
5. Con **Separar** las piezas se abren en vista explosionada. Toca una pieza para verla de cerca y **Volver** para regresar.
6. El botón de encendido de la barra apaga y enciende todo el dispositivo.
7. **MP3** permite cargar tus propias canciones desde tu computador. Se reproducen en tu navegador y no se suben a ninguna parte.

Las tres canciones de demostración se generan por síntesis dentro de la página. El repositorio no incluye música de terceros.

## Tecnologías

Three.js r128, modelos FBX embebidos, Web Audio API, JavaScript y HTML/CSS. Es un único archivo (`index.html`) que funciona sin instalar nada y también sin conexión a internet. Solo las tipografías (Orbitron y Chakra Petch, de Google Fonts) requieren conexión.

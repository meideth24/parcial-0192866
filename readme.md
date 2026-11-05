# SONORA

Maqueta local de un reproductor musical, una biblioteca de álbumes, un editor visual de listas y una pantalla de cuenta. El diseño usa HTML y CSS.

## Abrir el proyecto

Abre `index.html` en un navegador. No requiere instalación, servidor ni dependencias externas.

## Archivos

- `index.html`: contenido y estructura de las vistas.
- `styles/style.css`: diseño, adaptación a pantallas pequeñas y cambios visuales de selección.
- `assets/`: portadas locales.

## Vistas

- **Reproductor:** muestra la canción elegida. Los controles de audio son visuales y están desactivados.
- **Biblioteca:** permite elegir una de las cuatro canciones de ejemplo. La selección cambia los datos del reproductor.
- **Listas:** presenta listas de ejemplo, casillas de canciones y un estado vacío cuando no hay canciones marcadas.
- **Mi cuenta:** contiene los formularios de inicio de sesión y registro y muestra el usuario de ejemplo «Invitado».

La navegación entre vistas, la selección de canciones y el cambio entre formularios usan controles HTML y estilos CSS. Crear o guardar listas, iniciar sesión y registrar usuarios todavía no guarda información.

## Portadas

Las imágenes se cargan desde `assets/`. Las portadas de *I Love You*, *Thriller* y *Bad* se usan en la biblioteca; *I Love You* y *Wiped Out* también aparecen como fondos de listas. *Dangerous* usa un degradado porque no hay una portada correspondiente en la carpeta.

Para usar otra portada, guarda la imagen en `assets/` y actualiza su ruta en `styles/style.css`.

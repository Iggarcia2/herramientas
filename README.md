# Portal de herramientas de ingeniería (IG)

Una única dirección para abrir ESTIMA, HYDRA, ATLAS 3D y TORQUE.

## Cómo publicarlo

1. Creá en GitHub un repositorio público llamado `herramientas`.
2. Descomprimí el ZIP y subí a la raíz del repositorio `index.html` y la carpeta `logos/` (con sus archivos `.svg` y `.png`).
3. En Settings > Pages, elegí Deploy from a branch, `main`, `/(root)`.
4. La dirección será https://iggarcia2.github.io/herramientas/ una vez publicada.

## Archivos

- `index.html`: portal completo, con estilos responsivos y enlaces a las cuatro herramientas.
- `logos/*.svg`: logos vectoriales usados por la página.
- `logos/*.png`: versiones PNG opcionales para accesos directos, presentaciones o favoritos.

No requiere JavaScript ni archivos externos de CSS. Los enlaces abren pestañas nuevas. Para agregar otra herramienta, duplicá uno de los bloques `<a class="tool">` en el HTML y cambiá nombre, imagen, descripción y dirección.

Este proyecto solo enlaza tus aplicaciones; no las contiene ni las modifica.

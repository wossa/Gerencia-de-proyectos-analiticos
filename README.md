# SAT-DU — Dashboard de Deserción Universitaria

Este paquete adapta la estructura del ejemplo de clase a la base sintética SAT-DU.

## Archivos
- `index.html`: aplicación web.
- `base_sintetica_sat_du.csv`: base de 1.800 registros para carga automática en GitHub Pages.
- El sitio también permite cargar directamente el Excel original `.xlsx`.

## Publicar en GitHub Pages
1. Cree un repositorio nuevo en GitHub.
2. Suba `index.html` y `base_sintetica_sat_du.csv` a la raíz del repositorio.
3. En **Settings > Pages**, seleccione **Deploy from a branch**.
4. Elija la rama `main` y la carpeta `/ (root)`.
5. Guarde. GitHub mostrará la dirección pública del sitio.

## Umbrales iniciales
- Riesgo alto: probabilidad >= 0.30
- Riesgo medio: probabilidad >= 0.15 y < 0.30
- Riesgo bajo: probabilidad < 0.15

Los umbrales se pueden modificar desde el tablero.

## Nota
La base es sintética. La probabilidad de deserción se usa como señal de priorización para intervención, no como decisión automática sobre estudiantes.

### GRID 

La grid nos permite trabajar los elemenos html como si fuera una cuadricula.

La grid de CSS cosnta de 6 elementos :


1) Grid Container: Nos inidica el contenedor padre
2) Grid Items: Nos indica los hijos del padre.
3) Grid Lines: Son las lineas tanto horizontales y verticales del container.
4) Grid Tracks: Son las filas y columnas del container.
5) Grid Area: Es cualquier rectangulo limitado por grid lines.
6) Grid Cell: Es la interesecion entre 2 track es la forma de un rectangualo

Existen 3 propiedades imporatnes dentro de la grid:

1) display: grid; (Nos permite indicar que el elemento es el contenedor)
2) grid-template-columns: repeat(4,1fr); (Nos permite darel a la grid ls columnas en este caso son 4 columnas de 1 unidad del contenedor total)
3)grid-gap: 20px; (Es el espacio entre cada contenedor hijo)
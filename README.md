# ICC - Estructura de Datos

Repositorio de prácticas y o evaluaciones para la asignatura de **Estructura de Datos**, orientado al análisis, implementación y comparación de algoritmos en Java.

El sitio está publicado mediante **GitHub Pages** y permite acceder a las prácticas desde una página principal con tarjetas de navegación.

## Sitio publicado

La página principal del proyecto se encuentra en:

```txt
https://pablot18.github.io/icc-est-practicas/
```



## Prácticas disponibles

| Código | Práctica | Descripción | Ruta |
|---|---|---|---|
| PL1 | Métodos de ordenamiento | Implementación y análisis de algoritmos clásicos de ordenamiento como burbuja, burbuja avanzada y Shell Sort. | `unidad1/01-metodos-ordenamiento.html` |
| PL4.1 | Comparativa y análisis de tiempos | Comparación situacional entre Insertion Sort y QuickSort usando arreglos de objetos `Persona` y medición de tiempos con Benchmarking. | `unidad1/PL4.1-comparativa.html` |

## Objetivo del repositorio

- Publicar prácticas y evaluaciones en una interfaz web clara.
- Centralizar indicaciones académicas en páginas accesibles por enlace.
- Mantener una estructura simple para actualizar contenidos por unidad.



```

## Página principal

El archivo `index.html` funciona como menú principal del sitio.

Desde esta página se puede acceder a cada práctica mediante tarjetas de navegación.

Ejemplo de rutas usadas:

```html
<a href="./unidad1/01-metodos-ordenamiento.html">PL1</a>
<a href="./unidad1/PL4.1-comparativa.html">PL4.1</a>
```



## Cómo agregar una nueva práctica

1. Crear un nuevo archivo HTML dentro de la carpeta correspondiente.

Ejemplo:

```txt
unidad1/PL5-nueva-practica.html
```

2. Agregar una nueva card en `index.html`.

Ejemplo:

```html
<a class="practice-card" href="./unidad1/PL5-nueva-practica.html">
    <span class="practice-code">PL5</span>
    <h3>Nueva práctica</h3>
    <p>Descripción breve de la práctica.</p>
</a>
```

3. Verificar que la ruta funcione correctamente en GitHub Pages.




## Autor

***Ing. Pablo Torres***

Docente de la Carrera de Computación  
Universidad Politécnica Salesiana

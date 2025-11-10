# Implementación (slides)

Carpeta con una slide por módulo del paquete `two_body`.

## Módulos cubiertos
- Core
- Simulation
- Logic
- Perf Timings
- Presentation
- Scripts

## Cómo incluir en la presentación (Beamer)
En `Presentacion/slide.tex`, agrega en la sección deseada:

```
% Sección de Implementación
\input{implementacion/_index.tex}
```

También puedes incluir archivos individuales, por ejemplo:

```
\input{implementacion/core.tex}
\input{implementacion/simulation.tex}
```

> Nota: los paths anteriores son relativos al archivo `slide.tex` ubicado en `Presentacion/`.

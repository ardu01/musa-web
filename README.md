# Musa

Página estática de presentación de **Musa**, un estudio de edición de música para Windows con inteligencia artificial local integrada.

[Web](https://ardu01.github.io/musa-web/) · [Catálogo de proyectos](https://ardu01.github.io/proyectos/)

## Qué es Musa

Musa es un estudio de edición de audio, como un editor de vídeo pero para el audio, con IA local integrada. Las órdenes en lenguaje natural actúan sobre la zona marcada y la música se genera en local, en la GPU.

- Aplicación para Windows.
- Licencia de la aplicación: GPL-3.0-only.
- Empezado el 11 de noviembre de 2026.
- La fase 1 está en desarrollo: estudio multipista, asistente local y generación de música con ACE-Step.
- Todavía no hay descarga. La web muestra el estado «En desarrollo» y no incluye botón de descarga.
- El código fuente de la aplicación está en un repositorio privado y no se enlaza desde aquí.

## Esta web

HTML, CSS y un JavaScript mínimo, sin paso de compilación y sin dependencias. No hay cookies, analítica ni otros rastreadores. La página no carga recursos de terceros: las fuentes son las del sistema.

Las figuras de forma de onda y de estudio multipista están dibujadas con SVG y CSS. Van etiquetadas como ilustraciones. No son capturas de la aplicación.

## Ver en local

No hace falta instalar nada ni compilar.

```bash
python3 -m http.server 8080
```

Abrir `http://127.0.0.1:8080/`.

## Publicación

GitHub Pages, rama `main`, carpeta raíz `/`.

https://ardu01.github.io/musa-web/

El archivo `.nojekyll` evita el procesado de Jekyll.

## Repositorio de esta web

El código de la página está en [ardu01/musa-web](https://github.com/ardu01/musa-web).

## Licencia

La licencia MIT de este repositorio cubre solo el contenido de la web: HTML, CSS, JavaScript y las ilustraciones originales.

La aplicación Musa tiene licencia GPL-3.0-only. Su código no forma parte de este repositorio.

## Autor

Miguel.

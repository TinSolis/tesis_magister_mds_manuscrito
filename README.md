# Manuscrito — Tesis de Magíster en Ciencia de Datos (LaTeX)

Manuscrito de la tesis con la clase `umemoria` de [dccuchile/memoria-tesis-latex](https://github.com/dccuchile/memoria-tesis-latex), que cumple el Manual de Normalización de la FCFM. La portada ya dice "Tesis para optar al grado de Magíster en Ciencia de Datos" (`\tesis{...}` en `main.tex`).

Esta carpeta es un **repo git propio** (como lo fue `memoria_french_deputies` para la memoria), pensado para sincronizarse con Overleaf. El repo del magíster la ignora.

## Conectar con GitHub y Overleaf

1. Crear en GitHub un repo vacío y **privado**, por ejemplo `TinSolis/tesis_magister_mds_manuscrito`.
2. Desde esta carpeta:
   ```
   git remote add origin git@github.com:TinSolis/tesis_magister_mds_manuscrito.git
   git push -u origin main
   ```
3. En Overleaf: **New Project → Import from GitHub** y elegir el repo. En **Menu → Settings**: *Compiler* = `pdfLaTeX`, *Main document* = `main.tex`.

## Estructura

| Archivo | Contenido |
|---|---|
| `main.tex` | Documento maestro: portada, resumen, índices, declaración de uso de IA, `\input` de capítulos |
| `capitulos/cap1_introduccion.tex` | Contexto, problema, objetivos, alcances, estructura |
| `capitulos/cap2_marco_teorico.tex` | Discurso y voto, clasificación temática, argumentos y postura, valores (MFT y Schwartz), audiovisual y emociones, evaluación de modelos |
| `capitulos/cap3_datos.tex` | Cohorte, manifiestos, Twitter, hemiciclo, leyes y votos, INA, integración |
| `capitulos/cap4_metodologia.tex` | Las etapas 2 a 6 de la propuesta |
| `capitulos/cap5_resultados_preliminares.tex` | Avance a la fecha |
| `capitulos/cap6_plan_de_trabajo.tex` | Cronograma y riesgos |
| `capitulos/cap7_conclusiones.tex` | Conclusiones |
| `bibliografia.bib` | Las 5 referencias de la inscripción del tema |
| `umemoria.cls`, `umemoria-LICENSE` | Clase LaTeX de la FCFM (no editar) |
| `imagenes/` | Escudo U. de Chile y logo FCFM para la portada |

Las secciones siguen la propuesta de `../seminario_1/entrega_2_inscripcion_tema/propuesta_tesis.md`. Para la Entrega 3 (3-dic-2026) basta con portada y secciones enunciadas, más los borradores que haya; el PDF entregado se guarda en `../seminario_1/entrega_3_avance_manuscrito/`.

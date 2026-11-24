# Manuscrito — Tesis de Magíster en Ciencia de Datos (LaTeX)

Manuscrito de la tesis con la clase `umemoria` de [dccuchile/memoria-tesis-latex](https://github.com/dccuchile/memoria-tesis-latex), que cumple el Manual de Normalización de la FCFM. La portada ya dice "Tesis para optar al grado de Magíster en Ciencia de Datos" (`\tesis{...}` en `main.tex`).

Esta carpeta es un **repo git propio** (como lo fue `memoria_french_deputies` para la memoria), pensado para sincronizarse con Overleaf. El repo del magíster la ignora.

## GitHub y Overleaf

Repo: [TinSolis/tesis_magister_mds_manuscrito](https://github.com/TinSolis/tesis_magister_mds_manuscrito) (público).

- **Conectar Overleaf (una vez):** New Project → Import from GitHub → `tesis_magister_mds_manuscrito`. En **Menu**: *Compiler* = `pdfLaTeX`, *Main document* = `main.tex`.
- **Si escribes en Overleaf:** Menu → GitHub → *Push Overleaf changes to GitHub*; después `git pull` en esta carpeta.
- **Si escribes en el Mac:** `git add -A && git commit -m "…" && git push`; después en Overleaf, Menu → GitHub → *Pull GitHub changes into Overleaf*.
- No editar en los dos lados sin sincronizar entre medio.

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

Las secciones siguen la propuesta de `../seminario_1/entrega_2_inscripcion_tema/propuesta_tesis.md`. Para la Entrega 3 (3-dic-2026) basta con portada y secciones enunciadas, más los borradores que haya; el PDF entregado se guarda en `../seminario_1/entrega_final/entrega_3_avance_manuscrito/`.

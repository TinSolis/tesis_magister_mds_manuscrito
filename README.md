# Manuscrito de la tesis de Magíster

En este repo escribo el manuscrito de mi tesis del Magíster en Ciencia de Datos. Uso la clase `umemoria` de [dccuchile/memoria-tesis-latex](https://github.com/dccuchile/memoria-tesis-latex), que ya cumple el Manual de Normalización de la FCFM, y lo tengo sincronizado con Overleaf. El código y los datos están en [tesis_magister_mds](https://github.com/TinSolis/tesis_magister_mds).

## Overleaf

Lo importé en Overleaf con New Project → Import from GitHub, usando el compilador `pdfLaTeX` y `main.tex` como documento principal.

- Si escribo en Overleaf, hago *Menu → GitHub → Push Overleaf changes to GitHub* y después `git pull` aquí.
- Si escribo en el computador, hago `git push` y después, en Overleaf, *Pull GitHub changes into Overleaf*.
- No edito en los dos lados sin sincronizar entre medio, para no generar conflictos.

## Archivos

| Archivo | Qué tiene |
|---|---|
| `main.tex` | Portada, resumen, índices, declaración de uso de IA y los `\input` de cada capítulo |
| `capitulos/cap1_introduccion.tex` | Contexto, problema, objetivos, alcances y estructura del documento |
| `capitulos/cap2_marco_teorico.tex` | Discurso y voto, clasificación temática, argumentos y postura, valores (MFT y Schwartz), audiovisual y emociones, evaluación de modelos |
| `capitulos/cap3_datos.tex` | Diputados, manifiestos, Twitter, hemiciclo, leyes y votos, INA, y cómo se integran |
| `capitulos/cap4_metodologia.tex` | Las etapas 2 a 6 de la propuesta |
| `capitulos/cap5_resultados_preliminares.tex` | Lo que llevo hasta ahora |
| `capitulos/cap6_plan_de_trabajo.tex` | Cronograma y riesgos |
| `capitulos/cap7_conclusiones.tex` | Conclusiones |
| `bibliografia.bib` | Las 5 referencias de la inscripción del tema, por ahora |
| `umemoria.cls`, `umemoria-LICENSE` | La clase de la FCFM, que no se edita |
| `imagenes/` | El escudo de la Universidad y el logo de la FCFM para la portada |

Los capítulos siguen la propuesta que entregué al inscribir el tema (`seminario_1/entrega_2_inscripcion_tema/propuesta_tesis.md` en el otro repo). Para la Entrega 3 basta con la portada y las secciones enunciadas, más los borradores que tenga.

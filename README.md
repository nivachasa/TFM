# TFM · Analítica predictiva responsable del abandono universitario

Trabajo Fin de Máster · Máster Universitario en Inteligencia Artificial (UNIR)
Autora: Nicole Valentina Chacón Sánchez · Director: Javier Ricardo Luna Pineda
Tipo 1 · Piloto experimental (Baseline vs. modelos de IA)

## Objetivo
Comparar un enfoque tradicional de detección (reglas de negocio) con modelos
de aprendizaje automático para anticipar el abandono en educación superior,
analizando además interpretabilidad (SHAP) y equidad por subgrupos.

## Datos

Este repositorio incluye una copia **sin modificar** del conjunto de datos
*Predict Students' Dropout and Academic Success*, publicado en el UCI Machine
Learning Repository bajo licencia
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/),
que permite compartirlo y adaptarlo siempre que se atribuya la autoría.

**Cita del dataset:**
Realinho, V., Vieira Martins, M., Machado, J., & Baptista, L. (2021).
*Predict Students' Dropout and Academic Success* [Dataset]. UCI Machine
Learning Repository. https://doi.org/10.24432/C5MC89

**Organización de los datos:**
- `data/raw/`: archivo original, sin cambios (nunca se edita).
- `data/interim/` y `data/processed/`: versiones derivadas, generadas por el
  código de este repositorio. Constituyen adaptaciones realizadas por la
  autora del TFM.
- `data/DATA_CARD.md`: procedencia, verificación de integridad y diccionario.

La licencia CC BY 4.0 aplica al dataset. La licencia del código de este
repositorio se indica en el archivo `LICENSE`.

## Estado
- [x] Descripción y auditoría inicial del dataset
- [ ] Decisiones metodológicas (formulación del objetivo, tratamiento del
      desbalance): pendientes de validación con el director
- [ ] Baseline · [ ] Modelos · [ ] Interpretabilidad y equidad

## Reproducir
conda env create -f environment.yml
(pasos detallados a completar)

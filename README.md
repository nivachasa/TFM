# TFM · Analítica predictiva responsable del abandono universitario

Trabajo Fin de Máster · Máster Universitario en Inteligencia Artificial (UNIR)
Autora: Nicole Valentina Chacón Sánchez · Director: Javier Ricardo Luna Pineda
Tipo 1 · Piloto experimental (Baseline vs. modelos de IA)

## Objetivo
Comparar un enfoque tradicional de detección (reglas de negocio) con modelos
de aprendizaje automático para anticipar el abandono en educación superior,
analizando además interpretabilidad (SHAP) y equidad por subgrupos.

## Datos
- Fuente: Realinho, V., Vieira Martins, M., Machado, J., & Baptista, L. (2021).
  Predict Students' Dropout and Academic Success [Dataset]. UCI Machine
  Learning Repository. https://doi.org/10.24432/C5MC89
- Licencia del dataset: CC BY 4.0
- 4.424 registros, 36 variables + objetivo (Graduate / Dropout / Enrolled)
- Ver `data/DATA_CARD.md`

## Estado
- [x] Descripción y auditoría inicial del dataset
- [ ] Decisiones metodológicas (formulación del objetivo, tratamiento del
      desbalance): pendientes de validación con el director
- [ ] Baseline · [ ] Modelos · [ ] Interpretabilidad y equidad

## Reproducir
conda env create -f environment.yml
(pasos detallados a completar)

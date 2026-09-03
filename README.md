# Laboratorios de Machine Learning

Colección de trabajos académicos desarrollados durante la formación en Ingeniería en Inteligencia Artificial y Ciencia de Datos. Los notebooks combinan fundamentos matemáticos, análisis exploratorio y herramientas de `scikit-learn`, con énfasis en comprender y verificar cada etapa del modelado.

## Contenido

| Notebook | Temas principales |
| --- | --- |
| `01-carga-y-dataframes.ipynb` | Carga, selección, filtrado, agrupación y resumen de datos con pandas |
| `02-auditoria-exploratoria.ipynb` | Calidad de datos, distribuciones, valores atípicos, faltantes y relaciones entre variables |
| `03-validacion-y-pipelines.ipynb` | Hold-out, validación cruzada, prevención de fuga de datos, pipelines y transformaciones |
| `04-regresion-logistica-desde-cero.ipynb` | Sigmoide, entropía cruzada, gradiente, ajuste e interpretación de coeficientes |
| `05-gradient-descent-desde-cero.ipynb` | Batch, SGD, mini-batches, learning rate, escalado y comparación con scikit-learn |
| `06-desbalance-y-remuestreo.ipynb` | Clases desbalanceadas, SMOTE, submuestreo, validación sin fugas, calibración y selección de umbrales |

## Enfoque

- Implementación de algoritmos desde sus fundamentos.
- Verificación numérica contra implementaciones de referencia.
- Evaluación adecuada sobre datos no observados.
- Prevención de data leakage mediante pipelines.
- Interpretación de métricas, coeficientes y decisiones del modelo.

## Ejecución

```bash
python -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Abrir los notebooks en el orden indicado. Algunos conjuntos de datos educativos se descargan desde su fuente pública al ejecutar las primeras celdas. El dataset de mantenimiento industrial necesario para la auditoría se incluye en `data/`.

## Tecnologías

Python, Jupyter, NumPy, pandas, Matplotlib, SciPy y scikit-learn.

## Autor

Resoluciones y análisis realizados por Marcos Devincenzi en el marco de sus estudios en la Universidad Católica del Uruguay.

## Estado

Colección académica en crecimiento. Se incorporarán nuevos laboratorios y proyectos a medida que avance el curso.

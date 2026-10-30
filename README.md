# NovaRetail+ | Comportamiento del cliente e ingreso anual

**Autora:** Laura Sofía Arias González  
**Tipo:** Proyecto académico de análisis de datos — TripleTen  
**Herramientas:** Python · pandas · NumPy · scipy · seaborn · matplotlib

## Resumen ejecutivo

Analicé 15.000 registros de clientes para explorar relaciones entre frecuencia de compra, visitas, publicidad y generación de ingresos.

## Pregunta de negocio

¿Qué comportamientos del cliente están más asociados con el ingreso anual generado?

## Proceso de análisis

1. Exploración de 15.000 registros y 12 columnas; revisión de tipos, nulos e identificadores únicos.
2. Matriz de correlación y gráficos de dispersión para pares relevantes.
3. Coeficientes de Pearson para variables numéricas y punto biserial para relaciones binaria–numérica.
4. Exploración de asociación entre región y dispositivo mediante V de Cramér.
5. Interpretación de evidencia separando asociación y causalidad.

## Hallazgos principales

- La frecuencia de compras mensuales tiene una asociación positiva fuerte con el ingreso anual: Pearson r ≈ 0,967.
- El gasto publicitario dirigido y las visitas mensuales presentan una asociación positiva moderada: r ≈ 0,579.
- La membresía premium presenta una asociación débil con ingreso anual (≈ 0,093); abandono, una asociación cercana a cero (≈ −0,003).

## Recomendación

Priorizar hipótesis de fidelización y frecuencia de compra para pruebas posteriores; evaluar conjuntamente visitas, conversiones e ingresos.

## Ver el análisis

[Notebook del proyecto](https://github.com/lausofi97/Proyecto-final-sprint-8-/blob/main/S8%20Student%20Version-Project-NovaRetail.ipynb)

## Alcance y limitaciones

- El análisis es observacional y bivariado: no establece efectos causales.
- El cálculo de V de Cramér del notebook requiere corregir paréntesis y volver a ejecutarse; no se publica su valor como resultado validado.
- Una correlación entre predictor y objetivo no constituye por sí misma multicolinealidad. Esta se evalúa entre predictores.
- El notebook incluye pandas, NumPy, seaborn y matplotlib; conviene corregir el import de pyplot antes de ejecutarlo desde cero.

## Reproducibilidad

1. Descarga o clona este repositorio.
2. Abre el notebook enlazado en Jupyter.
3. Instala las librerías importadas en el notebook en un entorno virtual.
4. Ajusta las rutas de los datos a tu entorno. Los datasets no están incluidos en el repositorio revisado.
5. Ejecuta todas las celdas en orden y revisa las salidas.

Los resultados anteriores se documentan a partir de las salidas guardadas del notebook; no representan una ejecución independiente de punta a punta.

## Contacto

[LinkedIn](https://www.linkedin.com/in/laura-sofia-arias) · [GitHub](https://github.com/lausofi97)

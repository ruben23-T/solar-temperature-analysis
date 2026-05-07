# Análisis temporal de Temperatura e Irradiancia

## Resumen

En este proyecto se analizó un conjunto de datos que contiene el registro
de temperatura e irradiancia en la cuidad de Khulna durante los años del
2014 al 2022.

## Objetivo

Analizar la relación entre la irradiancia solar y la temperatura en función del tiempo,
identificando patrones diarios y mensuales, así como posibles desfases térmicos
y las variaciones en dicha relación.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

El conjunto de datos contiene registros horarios de temperatura e
irradiancia solar en la ciudad de Khulna desde 2014 hasta 2022.

Fuente:

- [Kaggle](https://www.kaggle.com/code/ashfakyeafi/solar-iridescence-and-temperature-dataset-eda)

## Hallazgos principales

- Correlación moderada entre temperatura e irradiancia.
- La irradiancia presenta un patrón diario consistente con máximos cercanos al mediodía.
- La temperatura muestra un desfase temporal respecto a la irradiancia.
- La agregación mensual suaviza los valores extremos debido al promedio
  de horas nocturnas y diurnas.
- La relación temporal entre temperatura e irradiancia se mantiene
  consistente a lo largo del año, aunque su magnitud cambia entre estaciones.

## Estructura del proyecto

```text
solar-temperature-analysis/
│── data/
│   └── solar_data_khulna.csv
│
│── notebooks/
│   └── analisis_temporal.ipynb
│
│── .gitignore
│── README.md
└── requirements.txt
```

## Cómo ejecutar el proyecto

```bash
git clone <repo>
cd solar-temperature-analysis

pip install -r requirements.txt
jupyter notebook
```

## Conclusión

Este análisis permitió identificar la relación entre la temperatura
y la irradiancia solar, así como comprender su comportamiento y
dinámica temporal a lo largo del tiempo.

Los resultados mostraron patrones consistentes entre ambas variables,
especialmente en el análisis horario, donde se observó una relación
física coherente entre la irradiancia y la variación de la temperatura.

Además, se identificó que la agregación mensual suaviza la magnitud
de los valores observados, aunque la relación temporal entre las
variables se mantiene consistente.

Finalmente, el análisis sugiere que existen factores externos
no incluidos en el dataset como humedad, nubosidad o condiciones
climáticas que podrían influir en el comportamiento observado.

## Autor

Ruben Trinidad

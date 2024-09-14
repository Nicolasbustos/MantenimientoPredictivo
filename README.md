# Mantenimiento Predictivo de Equipos Mineros - Etapa 1

Este repositorio contiene el código y los archivos necesarios para replicar el análisis de la **Etapa 1** del proyecto de **mantenimiento predictivo en equipos mineros**. El objetivo es desarrollar un modelo de **machine learning** que prediga las fallas en equipos mineros basándose en datos operativos y de sensores en tiempo real.

## Descripción del Proyecto

El mantenimiento predictivo es clave para reducir los costos operativos y mejorar la eficiencia de los equipos mineros. Este proyecto aplica técnicas de machine learning para anticipar fallas en los equipos, permitiendo una planificación más precisa del mantenimiento y evitando paradas imprevistas.

Este proyecto se divide en varias etapas. La **Etapa 1** se centra en el preprocesamiento de los datos y la creación de un modelo de clasificación inicial para predecir fallas en los equipos mineros.

## Contenidos
- **Dataset**: Un conjunto de datos de condiciones operativas de equipos mineros, que incluye características como temperatura, velocidad de rotación, torque, y desgaste de la herramienta.
- **Notebook Jupyter**: El notebook `Etapa1.ipynb` guía el proceso de análisis de datos, preprocesamiento, entrenamiento del modelo, y evaluación del rendimiento.
- **Scripts de preprocesamiento**: Código para la preparación y limpieza de los datos antes del modelado.
- **Resultados del modelo**: Métricas de rendimiento del modelo, como precisión, recall, y F1-score.
- **Licencia**: [Licencia MIT](#licencia) - detalla los términos bajo los cuales puede ser utilizado este código.

## Requisitos

Para ejecutar este proyecto localmente, necesitarás:

- **Python 3.10** o una versión compatible
- Bibliotecas listadas en `requirements.txt`:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

Puedes instalar todas las dependencias utilizando el siguiente comando:

```bash
pip install -r requirements.txt
```

## Cómo usar
1. Clona este repositorio:  
   ```bash
   git clone https://github.com/Nicolasbustos/MantenimientoPredictivo.git
   ```
2. Navega al directorio del proyecto:
    ```bash
    cd MantenimientoPredictivo
    ```   
3. Instala las bibliotecas necesarias:
    ```bash
    pip install -r requirements.txt
    ```
4. Ejecuta el notebook `Etapa1.ipynb` para replicar el análisis.
    ```bash
    jupyter notebook Etapa1.ipynb
    ```

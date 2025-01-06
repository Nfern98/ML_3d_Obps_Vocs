# ML_obps_vocs

El enfoque utilizado en este trabajo es buscar descriptores de proteínas que se unen a los odorantes (secuencias de aminoácidos) y compuestos orgánicos volátiles (SMILES) para predecir el valor de afinidad de unión proteína-ligando con modelos de aprendizaje automático de regresión.

![Figure](https://github.com/Glarah453/ML_obps_vocs/blob/main/figures/Esquema%20de%20Flujo%20de%20trabajo.jpg)

# Instalación

## Datos para el estudio

La Base de datos utilizada para este estudio fue obtenida desde el Github de  [iobpdb_app](https://github.com/sshuklz/iobpdb_app.git) para obtener más detalles de los datasets creados en este estudio, contactar a xlopez@ucm.cl.
## Requisitos

Para ejecutar los códigos, se debe instalar las siguientes librerias:


*   [Python 3.9.2 <=](https://www.python.org/downloads/)
*   [Pandas 2.2.x](https://pandas.pydata.org/docs/getting_started/install.html)
*   [Numpy 1.26.x](https://numpy.org/install/)
*   [Matplotlib 3.7.x](https://matplotlib.org/3.7.0/)
*   [Scipy 1.10.x](https://scipy.org/install/)
*   [Joblib 1.2.x](https://joblib.readthedocs.io/en/stable/installing.html)
*   [Padelpy 0.1.x](https://pypi.org/project/padelpy/)
*   [Propy 1.1.x](https://pypi.org/project/propy3/)
*   [Rdkit 2022.09.x](https://www.rdkit.org/docs/Install.html)
*   [Openpyxl 3.1.x](https://openpyxl.readthedocs.io/en/stable/tutorial.html)
*   [Hyperopt 0.2.x](https://hyperopt.github.io/hyperopt/)
*   [Scikit-learn 1.5.x](https://scikit-learn.org/1.5/install.html)
*   [Xgboost 2.1.1 <=](https://xgboost.readthedocs.io/en/latest/install.html)
*   [Lightgbm 4.5.x](https://lightgbm.readthedocs.io/en/latest/Installation-Guide.html)


# Uso

Para utilizar los códigos de este estudio, se puede ejecutar de dos maneras:

1. **Opción 1**:

Descargar el archivo [ML_IOBPdb_obps_covs.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_IOBPdb_obps_covs.ipynb) para ejecutar todas las etapas en un solo entorno de Jupyter.

2. **Opción 2**:

Descargar los siguientes archivos "ipynb" para ejecutar las etapas por separado en distintos entornos Jupyter:

* Recolección y filtrado de datos [ML_obps_covs - Etapa 1.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%201.ipynb). 

* Búsqueda de descriptores y creación de dataset [ML_obps_covs - Etapa 2 y 3.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%202%20y%203.ipynb). 

* Preprocesamiento, normalización y optimización de hiperparámetros para cada modelo. verificar los archivos "ipynb" de cada modelo en la carpeta [Opt for Models](https://github.com/Glarah453/ML_obps_vocs/tree/main/Opt%20for%20Models).

* Resultados de los mejores hiperparámetros de cada modelo [ML_obps_covs - Etapa 4 y 5.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%204%2C%205.ipynb).

* Evaluación de predicciones de cada modelo [ML_obps_covs - Etapa 6.ipynb](https://github.com/Glarah453/ML_obps_vocs/blob/main/ML_obps_covs%20-%20Etapa%206.ipynb).
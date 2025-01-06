# ML_3d_Obps_Vocs

El enfoque principal de este trabajo es la obtencion de descriptores a partir de estructuras 3D de las proteinas odorantes, compuestos organicos volatiles y docking molecular, con el fin de predecir la afinidad de union vinculante (Ki) a travez del aprendizaje automatico.

![Figure](https://github.com/Nfern98/ML_3d_Obps_Vocs/blob/main/workflow/workflow2.jpg)

# Instalación

## Datos para el estudio

La Base de datos utilizada para este estudio fue obtenida desde el Github de  [iobpdb_app](https://github.com/sshuklz/iobpdb_app.git) para obtener más detalles de los datasets creados en este estudio, contactar a xlopez@ucm.cl.
## Requisitos

Para ejecutar los códigos, se debe instalar las siguientes librerias:


*   [Python 3.9.2 <=](https://www.python.org/downloads/)
*   [Miniconda (Python 3.7)](https://repo.anaconda.com/miniconda/Miniconda3-py37_4.12.0-Linux-x86_64.sh)
*   [Pandas 2.2.x](https://pandas.pydata.org/docs/getting_started/install.html)
*   [Numpy 1.26.x](https://numpy.org/install/)
*   [Matplotlib 3.7.x](https://matplotlib.org/3.7.0/)
*   [Scipy 1.10.x](https://scipy.org/install/)
*   [Joblib 1.2.x](https://joblib.readthedocs.io/en/stable/installing.html)
*   [Openbabel](https://pypi.org/project/openbabel/)
*   [Pybel](https://open-babel.readthedocs.io/en/latest/UseTheLibrary/Python_Pybel.html)
*   [Mordred](https://github.com/mordred-descriptor/mordred)
*   [OpenMM](https://github.com/openmm/)
*   [PyBioMed](https://github.com/gadsbyfly/PyBioMed)
*   [PDBFixer](https://github.com/openmm/pdbfixer.git)
*   [Py3dMol 2.4.2](https://pypi.org/project/py3Dmol/)
*   [Propy 1.1.x](https://pypi.org/project/propy3/)
*   [Rdkit 2022.09.x](https://www.rdkit.org/docs/Install.html)
*   [Openpyxl 3.1.x](https://openpyxl.readthedocs.io/en/stable/tutorial.html)
*   [Hyperopt 0.2.x](https://hyperopt.github.io/hyperopt/)
*   [Scikit-learn 1.5.x](https://scikit-learn.org/1.5/install.html)
*   [Xgboost 2.1.1 <=](https://xgboost.readthedocs.io/en/latest/install.html)
*   [Lightgbm 4.5.x](https://lightgbm.readthedocs.io/en/latest/Installation-Guide.html)

Instalacion de herramientas
*   [MglTools 1.5.7](https://ccsb.scripps.edu/download/532/)
*   [Smina](https://downloads.sourceforge.net/project/smina/smina.static)



# Uso

Para utilizar los códigos de este estudio, se debe ejecutar de la siguiente manera:

1. **Paso 1**:

Descargar el archivo [Datos.ipynb](https://github.com/Nfern98/ML_3d_Obps_Vocs/blob/main/Datos.ipynb) para ejecutar todas las etapas en un solo entorno de Jupyter.

2. **Paso 2**:

Descargar el archivo [ML_Docking.ipynb](https://github.com/Nfern98/ML_3d_Obps_Vocs/blob/main/ML_Docking.ipynb) para ejecutar todas las etapas en un solo entorno de Jupyter.

3. **Paso 3**

Ejecutar el archivo [Datos.ipynb](https://github.com/Nfern98/ML_3d_Obps_Vocs/blob/main/Datos.ipynb) para obtener el dataset.

4. **Paso 4**

Ejecutar el archivo [ML_Docking](https://github.com/Nfern98/ML_3d_Obps_Vocs/blob/main/ML_Docking.ipynb) para realizar aprendizaje automatico.
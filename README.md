# 🌍 Clasificación geográfica de la ETo con WRF y SOM

Este repositorio contiene el código necesario para replicar los experimentos del artículo titulado:  
**"Clasificación geográfica de la ETo mediante la utilización del modelo de predicción meteorológico WRF y el método de aprendizaje no supervisado SOM."**

---

## 📦 Contenido

- `SOM_WRF_Andes_Amazon_Ecuador.ipynb`: flujo completo en Jupyter Notebook para:
  - descarga y preprocesamiento de datos climáticos,
  - entrenamiento de un modelo **Self-Organizing Map (SOM)** usando `somoclu`,
  - visualización y análisis de resultados.
- `collect_data.py`: script de **Scott Williams** para transformar archivos WRF en formato **NetCDF**.
- Datos preprocesados en formato `.csv` para los años **2017**, **2018** y **2019**, alojados en **Google Drive** y descargables directamente desde el notebook.

---

## ⚙️ Requisitos

Este proyecto fue ejecutado en **Google Colab** y utiliza las siguientes bibliotecas de Python:

  - `numpy`
  - `os`
  - `sys`
  - `pandas`
  - `matplotlib`
  - `somoclu`
  - `google.colab` (si se ejecuta en Google Colab)
  - `datetime`
  - `tempfile`
  - `math`
  - `gdown`
  - `ipywidgets`
  - `IPython.display`

## 🚀 Cómo usar

1. Clona este repositorio en tu entorno local o en Google Colab:

```bash
git clone https://github.com/tu_usuario/nombre_repositorio.git](https://github.com/carlosflores597/SOM_WRF
cd SOM_WRF
```
2. Abre el archivo SOM_WRF_Andes_Amazon_Ecuador.ipynb en Jupyter Notebook o súbelo a Google Colab.

3. Ejecuta las celdas para:

Montar Google Drive (si estás en Colab).

- Descargar automáticamente los datos .csv desde Google Drive con gdown.

- Procesar los datos meteorológicos.

- Entrenar el modelo SOM.

- Visualizar la clasificación geográfica de la ETo.

## 📜 Licencia

Este repositorio se distribuye con fines exclusivamente **académicos y de investigación**.

El archivo `collect_data.py` pertenece a su autor original, **Scott Williams**, y se incluye respetando sus condiciones de uso público.


## 📬 Contacto

Para sugerencias, colaboración o consultas relacionadas con este trabajo:

**Carlos Flores**  
Maestría en Ciencia de Datos  
Universidad San Francisco de Quito

carloscadena.flores@gmail.com



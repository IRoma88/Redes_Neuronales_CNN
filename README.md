# Clasificador de Imágenes de Gatos y Perros 🐱🐶

Este proyecto entrena un modelo de deep learning basado en **MobileNetV2** para clasificar imágenes de gatos y perros, utilizando el dataset de Microsoft de *PetImages*. Las imágenes se procesan, organizan en conjuntos de entrenamiento, validación y prueba, y luego se entrena una red neuronal convolucional con transferencia de aprendizaje.

## 🗂️ Estructura del proyecto

PetImages/ 

    ├── Cat/ 

    ├── Dog/ 

├── train/ 
  
    │ ├── cat/ 

    │ └── dog/ 

├── validation/ 
   
    │ ├── cat/ 
  
    │ └── dog/ 

├── test/ 

    │ ├── cat/ 
  
    │ └── dog/


## 🧪 Características

- Usa **MobileNetV2** como base congelada para transferencia de aprendizaje.
- Preprocesamiento con `ImageDataGenerator`.
- Entrenamiento con `model.fit` y visualización de métricas.
- Detección básica de overfitting.
- Guarda el modelo en formato `.h5`.

## 🚀 Requisitos

Instala los requerimientos con:

```bash
pip install -r requirements.txt
````

## 🧾 Uso
  1. Ejecuta el script principal (requiere curl y unzip si lo haces desde una notebook):

````bash
python main.py
````

  2. Entrenará el modelo y guardará el archivo cat_dog_classifier.h5.

## 📊 Resultados
Incluye gráficos de precisión y pérdida en entrenamiento y validación para observar el rendimiento del modelo y posibles signos de overfitting.

## 📁 Archivos importantes
  . **main.py:** Código principal de entrenamiento.

  . **requirements.txt:** Lista de dependencias.

  . **.gitignore:** Ignora archivos innecesarios para Git.

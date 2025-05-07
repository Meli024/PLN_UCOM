
# Modelado de Relaciones Semánticas con Word2Vec y LSTM

Este proyecto implementa modelos de clasificación semántica utilizando embeddings Word2Vec combinados con redes neuronales LSTM. Se desarrollaron dos modelos (binario y multiclase) sobre datasets sintéticos para evaluar su capacidad de generalización.

## Requisitos
pip install -r requirements.txt

## Estructura
notebooks/: Entrenamiento y pruebas interactivas de modelos.
models/: Modelos entrenados (.h5) listos para usar.
articles/: Informe final del proyecto.
data/: Instrucciones para cargar Word2Vec preentrenado.

## Cómo ejecutar
1. Instalar dependencias.
2. Descargar el archivo Word2Vec desde Kaggle (ver /data/README.md).
3. Abrir y ejecutar los notebooks en Google Colab.

## Datos
GoogleNews-vectors-negative300.bin: Modelo Word2Vec preentrenado con más de 100 mil millones de palabras del corpus de noticias de Google.

## Autor: Melizza Amarilla Cardozo

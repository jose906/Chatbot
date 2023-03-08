# ProyectoFinalML
## Enlace videos 
https://drive.google.com/drive/folders/1L8U1TJ0sRkHGzknuaHmfqPntzUOkAjIA?usp=sharing

# DESARROLLO DE UN CHATBOT MEDIANTE EL PROCESAMIENTO DE LENGUAJE NATURAL Y APRENDIZAJE PROFUNDO PARA LA NIVELACIÓN DE ESTUDIANTES PRE UNIVERSITARIOS

![image](https://user-images.githubusercontent.com/15108160/221388554-527a635e-a4d4-4d3a-a821-520b6dbaf149.png)

DESARROLLO DE UN CHATBOT MEDIANTE EL PROCESAMIENTO DE LENGUAJE NATURAL Y APRENDIZAJE PROFUNDO PARA LA NIVELACIÓN DE ESTUDIANTES PRE UNIVERSITARIOS
Integrantes

José Estensoro (josee906@gmail.com)
Roger Patón (oviroger@gmail.com)

Descripcion del Problema

En la actualidad, es común observar que muchos estudiantes que ingresan a la universidad presentan dificultades en su nivel de conocimientos en comparación con otros estudiantes. Esto se debe, en gran parte, a las deficiencias en la enseñanza de ciertos temas en algunos colegios, lo que resulta en una falta de preparación académica adecuada para enfrentar los retos de la educación superior.
Estas deficiencias en la enseñanza pueden ser el resultado de varios factores, incluyendo la falta de recursos y materiales didácticos adecuados, la falta de capacitación de los docentes y la ausencia de una política educativa que promueva la excelencia académica. Estas dificultades pueden ser especialmente graves en áreas como las matemáticas y las ciencias, que son fundamentales para muchas carreras universitarias.

!pip install tflearn
!pip install tensorboard

#NLTK 
import nltk
from nltk.stem.lancaster import LancasterStemmer
from nltk.tokenize import word_tokenize
#Numpy
from numpy.core.defchararray import mod
from numpy.lib.function_base import append
import numpy
#tflearn
import tflearn
import pickle,json, pandas as pd
import matplotlib.pyplot as plt
stemmer = LancasterStemmer()

import tensorflow as tf
from tensorflow import keras
from tensorflow.keras import layers
from transformers import TFBertModel, BertConfig
from tokenizers import BertWordPieceTokenizer
import textwrap

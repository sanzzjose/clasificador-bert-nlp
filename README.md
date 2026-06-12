# Clasificador de texto con BERT

Entregable de la Parte 3 de la asignatura Seminario Avanzado de Aprendizaje Automatico
(Master en Logica, Computacion e Inteligencia Artificial). El objetivo es resolver un
problema de clasificacion de procesamiento del lenguaje natural utilizando embeddings de
un modelo tipo BERT, justificando cada decision tomada.

## Estado

En construccion. Fase actual: configuracion del repositorio y estudio de los conceptos
previos (Transformers, mecanismo de atencion y arquitectura BERT).

## Estructura prevista

- `entregable_parte3_bert.ipynb`: notebook principal con la solucion y las explicaciones
  (se anade al empezar la Tarea 1).
- `requirements.txt`: dependencias del entorno.
- `data/`: datos del problema. Los datos pesados no se versionan (ver seccion "Datos").

## Entorno

Python 3.9. Dependencias principales en `requirements.txt`. Para reproducibilidad se
registraran las versiones exactas de las librerias y las semillas utilizadas.

Instalacion:

    pip install -r requirements.txt

## Datos

Los datasets pequenos se versionan en el repositorio. Los datasets grandes no se suben a
git: se descargan a disco local (o a Drive si el volumen lo exige) siguiendo las
instrucciones del notebook.

## Material de referencia (no versionado)

La teoria de la asignatura (PDFs) y los notebooks de practicas de ejemplo se mantienen
solo en local y estan excluidos del control de versiones.

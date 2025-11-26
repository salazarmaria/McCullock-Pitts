# Notas-de-IA

> Este repositorio contiene todas las actividades realizadas durante el semestre

## Trabajos realizados en la clase de Inteligencia Artificial   

## Modelos de Redes Neuronales

Una **Red Neuronal** es un modelo de cómputo inspirado en el funcionamiento del cerebro, diseñado para reconocer patrones complejos, clasificar información y hacer predicciones. Estos modelos aprenden ajustando las conexiones (pesos) entre sus nodos (neuronas).

## Contenido del Repositorio: Proyectos de IA por Arquitectura

Los proyectos están clasificados según la arquitectura fundamental de Red Neuronal implementada.

| Abreviatura | Nombre Completo | Mejor Uso Demostrado |
| :---: | :--- | :--- |
| **MLP** | **M**ultilayer **P**erceptron (Perceptrón Multicapa) | Datos tabulares, clasificación básica, predicción numérica |
| **CNN** | **C**onvolutional **N**eural **N**etwork (Red Neuronal Convolucional) | Imágenes, visión artificial, reconocimiento de objetos y patrones visuales |
| **RNN** | **R**ecurrent **N**eural **N**etwork (Red Neuronal Recurrente) | Texto, lenguaje natural, series de tiempo, datos secuenciales |

### 1. Perceptrón Multicapa (MLP)

El **MLP** (**M**ultilayer **P**erceptron) es la arquitectura de red neuronal **fundamental** 

Gracias a sus neuronas con **funciones de activación no lineales**, puede aprender a resolver problemas complejos que no son linealmente separables (como el XOR). Es el modelo estándar y más eficiente para tareas de **Clasificación** y **Regresión** con **datos tabulares** o estáticos. 

**Trabajos de MLP**

* **Perceptron_OR_y_NOT:** Implementación del Perceptrón básico, demostrando la solución a problemas **linealmente separables** (compuertas lógicas).
* **1_Neuronal_Multicapa_XOR:** Muestra cómo el uso de una **capa oculta** permite resolver el problema NO linealmente separable de la compuerta XOR.
* **predicción_de_la_eficiencia_del_combustible:** Proyecto de **Regresión** que utiliza el MLP para estimar un valor numérico continuo.
* **Clasificación_de_un_candidato_a_un_empleo:** Aplicación del MLP a una tarea de **Clasificación** en datos de características.
* **1_Flor_Iris:** Un ejemplo estándar de clasificación multicategoría con MLP.

### 2. Redes Neuronales Convolucionales (CNN)

Las **CNNs** son el estándar de oro para el procesamiento de imágenes. Utilizan la operación de **convolución** para escanear y extraer automáticamente características y patrones espaciales, lo que las hace muy eficientes para la visión artificial.

**Trabajos de CNN**

* **Clasificación_de_dígitos:** Implementación de una CNN para la tarea fundamental de reconocimiento de dígitos escritos a mano.
* **Clasificación_de_Ropa:** Aplicación de la CNN para clasificar imágenes de prendas de vestir, demostrando la escalabilidad de la arquitectura.

### 3. Redes Neuronales Recurrentes (RNN)

Las **RNNs** se especializan en el manejo de **datos secuenciales**. Tienen una "memoria" que les permite que la salida en un momento dependa de entradas y cálculos previos en la secuencia, siendo esenciales para predecir series de tiempo o analizar lenguaje.

**Trabajos de RNN**

* **Accion_de_Amazon** y **Predecir_el_precio_de_Bitcoin:** Aplicaciones clave de las RNNs para el análisis y predicción de **Series de Tiempo Financieras**, donde el orden de los datos es vital.
* **predicción_de_popularidad_de_una_canción:** Uso de modelos secuenciales para predecir un resultado (popularidad) basado en una serie de atributos temporales o contextuales de la canción.


Cada carpeta contiene su cuaderno Colab con **gráficos, código y comentarios de estudio** que documentan el proceso.




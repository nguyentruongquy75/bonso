---
layout: post
title: Một buổi chụp cần chuẩn bị những gì
date: 2023-08-22 00:00:00 -0600
image: "https://images.unsplash.com/photo-1698778573868-75a5c62ab43e?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw1fHx8ZW58MHx8fHx8"
tags:
  [Inteligencia&nbspArtificial, Redes&nbspNeuronales, Tecnologia, Perceptron]
featured: True
---

Las redes neuronales artificiales (RNA) son modelos simplificados de las redes neuronales biológicas. Aunque el termino red neuronal artificial puede que suene como algo extraído de una película de ciencia ficción, la realidad es muy diferente a como nos ha mostrado el cine.

Estas no son más que una estructura de datos que nos permite extraer capacidades similares a las del cebro humano, en la actualidad probando que han sido capaces de resolver problemas como el reconocimiento de patrones o el reconocimiento de imágenes. En general problemas que son difíciles de resolver usando la ordinaria programación basado en reglas.

Sin embargo, en la actualidad aun las redes neuronales artificiales, no alcanzan a emular en su totalidad la complejidad del cerebro humano, estando aún muy distantes de inteligencias artificiales como las que el cine nos tiene acostumbrados. Estos algoritmos siguen la siguiente estructura:

![](https://images.unsplash.com/photo-1698778573868-75a5c62ab43e?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw1fHx8ZW58MHx8fHx8)

| Neurona Biológica              | Neurona Artificial            |
| ------------------------------ | ----------------------------- |
| Soma ( θ )                     | Neurona ( + )                 |
| Axón ( j )                     | Salida ( j )                  |
| Sinapsis ( w1, w2, w3 ... wk ) | Peso ( w1, w2, w3 ... wk )    |
| Entradas ( x1, x2, x3 ... xk ) | Entradas ( x1, x2, x3 ... xk) |

De la observación detallada del proceso biológico, se han hallado las siguientes analogías
con el sistema artificial.

- Las entradas Xi representan las señales que provienen de otras neuronas y que son
  capturadas por las dendritas. Para las neuronas artificiales, las entradas pueden ser
  variables continuas o discretas, mientras que en las neuronas biológicas son pulsos
  discretos.

- Los pesos Wi representan la intensidad de la sinapsis que conecta dos neuronas;
  tanto Xi como Wi son valores reales

- θ es la función umbral que la neurona debe sobrepasar para activarse; este proceso
  ocurre biológicamente en el cuerpo de la célula.

Si recuerdas tus clases de ciencias naturales podrías recordar a las células como la unidad básica fundamental de todo ser vivo, y a su vez como es que cada sistema del cuerpo humano posee células especializadas unidas en grandes cantidades para realizar los procesos que requiere, formando así a los sistemas del cuerpo humano nervioso, digestivo ... etc.

![](https://images.unsplash.com/photo-1698778573868-75a5c62ab43e?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw1fHx8ZW58MHx8fHx8)
_Diferentes tipos de células en el cuerpo humano están especializadas para realizar determinados trabajos._

Es entonces como la neurona biológica conforma la parte más pequeña, o la unidad mínima que compone al sistema nervioso y como la neurona artificial es como cualquier software, no es algo que sea tangible, no es algo que puedes tocar, en realidad se trata de reglas, un algoritmo o una representación matemática que intenta funcionar de manera que aproxime a la neurona biológica. Pero adentrarse a las matemáticas detrás de estas serán tema para otra publicación.

### Bibliografía

1. S. Haykin, Neural Networks: A comprehensive Foundation, Second edition, Prentice
   Hall, New Jersey, USA., 1999.
2. Dr. Edgar Nelson Sánchez Camperos y M.C Alma Yolanda Alanís García, Redes Neuronales Conceptos Fundamentales y Aplicaciones a Control Automático, PEARSON EDUCACION S.A., Madrid, 2006

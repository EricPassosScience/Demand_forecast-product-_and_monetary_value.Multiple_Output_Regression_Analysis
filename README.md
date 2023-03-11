# Pronóstico de demanda (producto y valor monetario) con "Multiple Output Regression Analysis" de Scikit Learn.
## Problema de Negocios
Imagine que una empresa quiere predecir cuántas unidades de un producto se venderán y cuáles serán las ventas monetarias totales. Podríamos crear dos modelos de regresión separados, uno para predecir el total de unidades vendidas y otro para predecir el total de ventas. Pero podemos aplicar una técnica que crea ambos modelos simultáneamente, prediciendo así dos variables de salida al mismo tiempo basadas en las mismas variables de entrada.
## Multiple Output Regression Analysis
Este algoritmo sirve para predecir dos valores de Y. En la práctica, crea varios modelos de regresión en un solo comando, el MultiOutputRegressor simplemente encapsula el algoritmo.

La función MultiOutputRegressor admite varios modelos de regresión: KNN, Linear Regression, Random Forest y otros.

Documentación -> https://scikit-learn.org/stable/modules/generated/sklearn.multioutput.MultiOutputRegressor.html

Obs. Este tipo de modelo no es fácil de ajustar, ya que ajustar la variable predictora puede mejorar y1, pero empeorar y2. Lograr un equilibrio no es tarea fácil.

Obs. Para este caso, utilizaremos datos ficticios que representan un caso real.

Obs. Nuestro trabajo aquí es analizar este enfoque y descubrir si puede ayudarnos durante los proyectos de ciencia de datos. Por lo tanto, los datos ficticios son suficientes. 


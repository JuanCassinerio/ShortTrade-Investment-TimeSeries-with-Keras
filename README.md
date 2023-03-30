# ShortTrade-Investment-TimeSeries-with-Keras
<p align="center">
  <img src="https://github.com/JuanCassinerio/Bank-Deposit-Classification---Logistic-Regression-Decision-tree-and-Random-Forest/blob/main/logo.jpg" width="300" alt="Logo">
</p>

# Algoritmo Predictivo de probabilidad de que Clientes Bancarios realicen Depósitos a Plazo
Integrantes del proyecto: Juan Cassinerio - Juan Isasi - Jose Vargas

Ultima fecha de actualización: 18/03/2023

# Resumen
Dentro de los productos y servicios que ofrecen los bancos, los depósitos a plazo representan un gran porcentaje de las fuentes de ingresos. Para poder maximizar la cantidad de depósitos a plazo realizados, se buscará identificar a los clientes (parámetros) que tengan la mayor probabilidad de subscribirse a este tipo de producto y de esa manera poder mejorar los esfuerzos de marketing en dichos clientes.

Para ello recopilo un conjuntos de datos con el objetivo de desarrollar modelos de machine learning para predecir la probabilidad de que clientes realicen depósitos a plazo en bancos. Estos datos fueron tomados de una campaña de marketing de una importante institución bancaria de Portugal.

Se nos permitió el acceso a un .cvs donde emplearemos un análisis descriptivo para poder entender de mejor forma los datos recopilados y su relación con la variable a investigar "y" (Si el depósito a plazo fue realizado o no).
Dataset: https://www.kaggle.com/datasets/rashmiranu/bankingdataset-classification).

# Conclusiones
Del análisis de los datos pudimos reconocer que las variables Edad, Mes, Estado Civil y Tiempo de última llamada con el Cliente juegan un factor determinante en la probabilidad de que los clientes se subscriban o no a un depósito a plazo. Siendo las siguientes las condiciones óptimas:
- Edad: 18-25 y 60-100
- Mes: Marzo, Septiembre, Octubre y Diciembre
- Estado Civil: Soltero
- Tiempo de última llamada con el Cliente: 12min
Los modelos implementados lograron predecir el comportamiento observado en los datos con una precisión mayor al 86%, siendo el modelo de Regresión Logística aquel con mayor precisión, de un 91%. Proponemos utilizar el algoritmo de regresión logística en la base de datos de bancos para seleccionar a los prospectos a los cuales se le contactará mediante una campaña telefónica exclusiva, eficientizando el tiempo y el esfuerzo del call center.

# Actividad-de-Opiniones

PRIMEROS PASOS:
primero de todo se import pandas, para posteriormente usar el read con el csv respectivo.
También se uso el head y el shape para posterioemente usar el isnull mas el sum para analizar los nulos que hay.

ENTRENAMIENTO Y PRUEBA

Como en ocasiones anteriores se importo el train_test_split.
En este caso particular se recurrio a la concatenación de mas columnas para llegar a mas resultados,teniendo un rango mas amplio para la variable indepenediente.

AJUSTE DE DATOS

En el ajuste de lso datos se importo el CountVectorizer.

Se creo una variable relacionada al modelo(vectorizador) en este caso LogisticRegression,luego se utilizó el fit para los datos del train.

PREDICCIÓN

Para la predicción se importo el accuracy_score para por medio de una variable "predict" que se asocio al modelo,predecirlo utilizando el accuracy_score para ambos datos, por último se imprimio la exactitud.

TRABAJO CON DATOS DE PRUEBA

En esta parte se realizo lo mismo que se hizo anteriormente en pasos anteriores, pero trabajo con el segundo CSV leido.

Para el CountVectorizer de los datos de prueba se le añadio los datos concatenados del split.

También en esta parte se creó la columna de "etiquetas" que guardara los datos hechos en la predicción.

Por último por mdio del comando outpust se creo el csv que posteriormente se subió al ranking del profesor.












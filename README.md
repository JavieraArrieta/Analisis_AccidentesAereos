# Proyecto N°3 de Data Analytics para Henry - Accidentes de Aviones

<img src = 'Aviones.jpeg' height = 300>

----

<br>

La **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, nos solicita la elaboración de un informe y un dashboard interactivo que recopile tal información. 

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio.

**Pasos a seguir:**

* Se realizo la lectura del csv en el notebook *EDA+Transfor.ipynb* en donde se detalla la exploracion de los datos y el proceso de ETL.
<br>
<br>
<img src = 'EDA_ETL.png' height = 500 weight= 600>

----

<br>

* **Diccionario de Datos.**

Explicacion de columnas del dataset:<br>
**id** : Identificador unico de cada accidente.<br>
**Fecha** : Fecha en la que ocurrio el accidente.<br>
**Ruta** : Lugar del accidente.<br>
**Operador** : Operador del avion.<br>
**Trayecto** : Lugar de salida y llegada que debia hacer el avion.<br>
**Modelo del avion** : Nombre del modelo del avion.<br>
**Registro** : Registro del avion.<br>
**Total a bordo** : Total de personas a bordo, incluye pasajeros y tripulantes.<br>
**Pasajeros a bordo** : Total de solo pasajeros.<br>
**Tripulantes a bordo** : Total de solo Tripulantes.<br>
**Total fallecidos** : Total de personas fallecidas, pasajeros y tripulantes.<br>
**Fatalidad pasajeros** : Cantidad de pasajeros que murieron a bordo.<br>
**Fatalidad tripulantes** : Cantidad de tripulantes que murieron a bordo.<br>
**Fatalidad en tierra** : Cantidad de personas que murieron no estando a bordo, sino que en tierra.<br>
**Año** : Año en que ocurrio el accidente.<br>
**Tipo de operador** : Si el avion es militar o comercial.<br>
**Origen** : Lugar donde se creo el avion.<br>


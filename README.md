# Reto-Banorte-Hack-2021

## Equipo 79
## Creado por: David Martínez Celis, Sofía Sampogna, Ricardo González
## TEAM DSR
### Modelo de nowcasting para pronosticar la variación anual de la inflación general y subyacente de la 1° Quin. Enero 2021 a la 1° Quin. Agosto 2021


## Fase 1 - Recolectar dataset

### Se recolectaron los datos de la variación quincenal del INPC desde la 1Q de Enero de 1988, hasta la 1Q de Agosto de 2021, de la página del INEGI.
### Para ordenar los datos, se decidió convertir las fechas a números enteros, empezando del 1 hasta 804, para poder utilizarlo con más facilidad dentro del programa
### También se decidió incluir en la base de datos diferentes cifras del INPP, los cuales se tomaron de igual manera del INEGI 

## Fase 2 - Diagrama de dispersión

### Elaboración diagrama de dispersión para analizar la tendencia general de los datos y así comenzar a planear cuál sería el mejor approach

## Fase 3 - Primer Modelo

### Se hizo prueba con modelo lineal de regresión para observar la calificación de entrada de este

## Fase 4 - Limpieza de Datos

### Observamos que nuestros datos contenían un alto número de “outliers” que afectaban el modelo de regresión, por lo que decidimos suavizarlos utilizando el método de “z score” 

## Fase 5 - Nuevo ajuste del modelo 

### Para conseguir un mejor resultado, decidimos utilizar Training Test para conseguir mejores predicciones de nuestros datos sin tomar en cuenta las anomalías presentadas. 

## Fase 6 - Prueba con otros modelos

### Regresión Ridge

### Árbol de Decisión

### Random Forest

## Fase 7 - Pronósticos y Error



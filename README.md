## P2_DataAnalytics
# Proyecto de Análisis de Siniestros Viales en CABA con Víctimas Fatales (2016-2021)
*Por Diego Gamarra Rivera*

## Presentación del Proyecto 

Este proyecto representa un análisis de datos llevado a cabo por un Data Analyst en simulación de un encargo del Observatorio de Movilidad y Seguridad Vial (OMSV) bajo la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA). El objetivo principal es proporcionar información relevante para la toma de decisiones orientada a la prevención y reducción de siniestros viales con víctimas fatales en la ciudad.
Los datos utilizados se extraen del dataset oficial de víctimas de siniestros viales en CABA entre 2016 y 2021, accesible en la página oficial de la ciudad. [Datos Oficiales](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales)

## Contexto del Problema 

Los siniestros viales, también conocidos como accidentes de tráfico, involucran diversos vehículos y pueden resultar en daños materiales, lesiones graves o fatales. En Argentina, aproximadamente 4,000 personas mueren cada año en siniestros viales, siendo una de las principales causas de muertes violentas.

La ciudad de Buenos Aires, con su alta densidad poblacional y tráfico, enfrenta desafíos particulares en materia de seguridad vial. El análisis de la evolución temporal, lugares críticos, perfiles de víctimas y factores contribuyentes es esencial para desarrollar estrategias efectivas.

## Desarrollo del Proyecto 

### Datos Utilizados 

Para este análisis, se trabajó con un dataset que contiene información detallada sobre los siniestros viales y las víctimas involucradas. Se realizó un proceso de ETL (Extracción, Transformación y Carga) para limpiar y estructurar los datos, eliminando nulos, duplicados y realizando transformaciones necesarias. El resultado se almacenó en un archivo CSV llamado `homicidios1.csv`.

El análisis exploratorio de datos (EDA) se centró en comprender las relaciones entre variables, identificar patrones y destacar tendencias a lo largo del tiempo.

### Resultados del Análisis 

- **Análisis Temporal:**
  - Se identificó una tendencia de siniestros viales que inicialmente era alta y estacionaria entre 2016 y 2018, seguida por una disminución durante la pandemia en 2020. En 2021, se observó un pico en diciembre.
  - Los meses con más víctimas fatales fueron diciembre y noviembre, mientras que los sábados y domingos registraron la mayor cantidad de siniestros.
  - 
![Evolución temporal](images/o2.png)
- **Análisis Demográfico y Geográfico:**
  - Las víctimas mayoritarias son hombres entre 20 y 40 años.
  - Las avenidas, especialmente en comunas 1 y 4, son los lugares con más siniestros.


- **Análisis Participativo:**
  - Los vehículos más frecuentes en los siniestros son motos y peatones, siendo los autos y colectivos los más involucrados como acusados.
  - Los horarios críticos coinciden con el ingreso y salida laboral, almuerzo y salidas nocturnas durante los fines de semana.

### Indicadores de Rendimiento Clave (KPI) 

Se propusieron KPI para evaluar el rendimiento y establecer objetivos concretos:

1. **Reducir en un 10% la tasa de homicidios en siniestros viales en comparación con el semestre anterior.**
   - Se define la tasa de homicidios como el número de víctimas fatales por cada 100,000 habitantes.

2. **Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año.**
   - Se focaliza en la disminución de siniestros mortales con víctimas en moto.


### Dashboard y Visualización 

![KPI](/images/kpis.PNG)

## Conclusiones 

A partir del análisis exahustivo de los datos y su posterior visualización a través del dashboard en PowerBi; se concluye que las víctimas fatales por siniestros de tránsito entre los años 2016 a 2021 fueron 717 personas.
Que la franja horaria de mayor problemática es la del ingreso laboral (5-9h), la del almuerzo (12-14h)y la del regreso a casa(17-18h); aunque durante los fines de semana (Sábado y Domingo), los accidentes se manifiestan en los horarios de salidas nocturnas (3-7h).
Las víctimas son en un 76% Masculinas, y sus edades entre el rango etario de 20-40 años.
Además en los siniestros de Masculinos los mayores casos se dan en su rol como Conductor.
Los tipos de vehículos más frecuentes con Víctimas son las Motos y luego los Peatones; mientras que para los Acusados los vehículos más frecuentes son Autos, Colectivos y cargas.
En cuanto a el lugar donde se producen los siniestros, las Avenidas a lo largo de los años han sido los espacios de mayor cantidad de siniestros; y en Cruce mayor a las calles. 
Se observo un patrón en relación con la variable Edad, Hora y Sexo. Donde los Masculinos de entre 20 a 40 años y en los horarios de entrada y salida laboral o para el caso de los fines de semana en horas de salidas nocturnas.



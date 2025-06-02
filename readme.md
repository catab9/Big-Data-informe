# Big Data informe
Evaluación Big Data

### Integrantes:
-Catalina Bravo
-Bastían Fuentes
-Valentina Sepúlveda

## PASO 1: Creación de Bucket
Ingreso al taller GSP840 para poder abrir la consola de google cloud para poder iniciar con un usuario. Una vez abierta la consola en una pestaña incógnita, se crea la Bucket con nombre-alumno.

<img width="1239" alt="bucket" src="https://github.com/user-attachments/assets/679c46ca-7352-46c6-92a7-8e6498b56eb9" />

## PASO 2: Conexión a Bigquery y conexion de usuario
En esta paso nos dirigimos a Bigquery y subimos la base de datos que tuvimos que transformar a csv para poder usarla posteriormente.

<img width="1239" alt="bucket" src="https://github.com/user-attachments/assets/7a481458-1629-4583-b871-34a69387d98e" />

<img width="770" alt="Screenshot 2025-06-01 at 5 31 01 PM" src="https://github.com/user-attachments/assets/a2831b0f-30c8-4ebb-91c2-443defedd944" />

<img width="588" alt="Screenshot 2025-06-01 at 5 31 12 PM" src="https://github.com/user-attachments/assets/e50e5d60-116f-4ee4-a690-f04bccfb6113" />

## PASO 3: DataPrep
Luego nos dirigimos a dataprep que se encuentra al ingresar al menú > View all products > Analytics. En esta parte es donde creamos un flujo con el archivo que subimos anteriormente.

<img width="1250" alt="Screenshot 2025-05-30 at 17 05 40" src="https://github.com/user-attachments/assets/0cf4fdbb-b8bb-4b6d-8f3b-98bfff2db8ac" />

## PASO 4: Limpieza de la base de datos.
Se hacen 7 limpiezas en total, en donde se eliminó de muchas columnas los datos considerados como ismissing e ismismatched. Además la tabla llamada "state/province" se cambia a "state_province" para eliminae el error que aparece por el uso de "/". Finalmente con los datos ya limpios obtenemos un 100% de valores válidos. 

<img width="1254" alt="base de datos" src="https://github.com/user-attachments/assets/2e338ac0-9b23-4697-8df2-c81870fe6cbb" />
<img width="1245" alt="Screenshot 2025-05-31 at 13 52 09" src="https://github.com/user-attachments/assets/be5f5640-174f-4ad9-a995-015c267cbd14" />

## PASO 5: Creación de gráficos.

Se generan los gráficos mediante los códigos insertados la consola de la tabla. 
•⁠  ⁠Creamos 3 gráficos por cantidad y ordenados de manera descendente, el primer gráfico de torta, es en el cual se visualiza la cantidad de avistamientos según las formas más vistas.
•⁠  ⁠El segúndo, es un gráfico de barras que representa la cantidad de avistamientos por año.
•⁠  ⁠El tercer gráfico podemos ver un mapa del mundo con la cantidad de avistamientos por estado.


![WhatsApp Image 2025-06-01 at 7 04 30 PM](https://github.com/user-attachments/assets/f2539556-2234-40c4-b664-90d6b08acc79)

gráfico 1 La visualización muestra un análisis realizado con BigQuery sobre avistamientos de OVNIs clasificados según la forma observada. Destaca notablemente que la mayoría de los reportes se describen como luces ("light"), constituyendo el 37.5% del total con 5,440 avistamientos. Formas más definidas como triángulos (17.8%), círculos (17.1%) y bolas de fuego (14.6%) también aparecen con frecuencia, mientras que diversas formas menos comunes se agrupan bajo "other" (13%). Esto sugiere que los testigos comúnmente reportan fenómenos luminosos difíciles de caracterizar con precisión.

<img width="709" alt="Gráfico 2" src="https://github.com/user-attachments/assets/6d0a4ca3-8e42-4041-b889-23eb68a03360" />

gráfico 2 La imagen muestra un análisis generado con BigQuery sobre avistamientos de OVNIs, ordenados por año (Year) y cantidad de avistamientos (Sightings). Se observa claramente que algunos años tuvieron notablemente más reportes que otros, destacando especialmente el año *1* (probablemente indicando datos faltantes o errores) con 10,163 registros, seguido por los años *3 y 91* con más de 6,000 y 5,900 avistamientos respectivamente. La distribución irregular indica posibles errores en la base de datos, anomalías en la recopilación histórica de los datos, o años específicos con picos notables de interés o sucesos que impulsaron el reporte de avistamientos.
 
![WhatsApp Image 2025-06-01 at 7 12 23 PM](https://github.com/user-attachments/assets/f7d4fa5f-23d0-4c85-9647-7fe97607770b)

gráfico 3 La visualización presenta la distribución geográfica y frecuencia de avistamientos OVNI en Estados Unidos y el mundo, destacando notablemente California (CA) como el estado con más reportes (3,561 avistamientos), seguido de Washington (WA, 1,555) y Florida (FL, 1,544). El mapa resalta claramente una alta concentración de avistamientos en Norteamérica, con un predominio particular en la costa oeste estadounidense. Otros lugares globales también presentan avistamientos, pero con una densidad notablemente menor. Esto indica que Estados Unidos, especialmente estados como California y Washington, es el área con mayor actividad registrada en avistamientos OVNI.



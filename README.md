# Big-Data-informe
##Evaluación Big Data

Integrantes:
-Catalina Bravo
-Bastían Fuentes
-Valentina Sepúlveda

##PASO 1: Creación de Bucket
Ingreso al taller GSP840 para poder abrir la consola de google cloud para poder iniciar con un usuario. Una vez abierta la consola en una pestaña incógnita, se crea la Bucket con nombre-alumno.

<img width="1239" alt="bucket" src="https://github.com/user-attachments/assets/679c46ca-7352-46c6-92a7-8e6498b56eb9" />

##PASO 2: Conexión a Bigquery
En esta paso nos dirigimos a Bigquery y subimos la base de datos que tuvimos que transformar a csv para poder usarla posteriormente.

<img width="1239" alt="bucket" src="https://github.com/user-attachments/assets/7a481458-1629-4583-b871-34a69387d98e" />

##PASO 3: DataPrep
Luego nos dirigimos a dataprep que se encuentra al ingresar al menú > View all products > Analytics. En esta parte es donde creamos un flujo con el archivo que subimos anteriormente.

<img width="1250" alt="Screenshot 2025-05-30 at 17 05 40" src="https://github.com/user-attachments/assets/0cf4fdbb-b8bb-4b6d-8f3b-98bfff2db8ac" />

##PASO 4: Limpieza de la base de datos.
Se hacen 7 limpiezas en total, en donde se eliminó de muchas columnas los datos considerados como ismissing e ismismatched. Además la tabla llamada "state/province" se cambia a "state_province" para eliminae el error que aparece por el uso de "/". Finalmente con los datos ya limpios obtenemos un 100% de valores válidos. 

<img width="1254" alt="base de datos" src="https://github.com/user-attachments/assets/2e338ac0-9b23-4697-8df2-c81870fe6cbb" />
<img width="1245" alt="Screenshot 2025-05-31 at 13 52 09" src="https://github.com/user-attachments/assets/be5f5640-174f-4ad9-a995-015c267cbd14" />

##PASO 4: Creación de gráficos.

Se generan los gráficos mediante los códigos insertados la consola de la tabla. 
- Creamos 3 gráficos por cantidad y ordenados de manera descendente, el primer gráfico de torta, es en el cual se visualiza la cantidad de avistamientos según las formas más vistas.
- El segúndo, es un gráfico de barras que representa la cantidad de avistamientos por año.
- El tercer gráfico podemos ver un mapa del mundo con la cantidad de avistamientos por estado.

<img width="795" alt="Gráfico 1" src="https://github.com/user-attachments/assets/05e46a3d-7046-4f2f-b89a-2b0d1e69636e" />
<img width="709" alt="Gráfico 2" src="https://github.com/user-attachments/assets/6d0a4ca3-8e42-4041-b889-23eb68a03360" />



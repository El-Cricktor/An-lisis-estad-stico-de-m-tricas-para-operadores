Dentro de la industria actual, los marcadores son herramientas completamente escenciales para la correcta implmentación de procesos y estructurar proyectos importantes, por lo que, para una empresa de telecomunicaciones realiza una prueba A/B para el desempeño de los operadores, es nuestro trabajo contrastar la infroamción recabada por los anitguos miembros y generar un reporte de desempeño de cada uno de los operadores. PAra ellos se realiza una serie de ETL'S donde se busca identificar, mediante metricas de la industria, a los elementos más problematicos del equipo de trabajo ya sea en una, dos o tres áreas, como lo pueden ser, las llamadas perdidas, llamadas entrantes y finalmente la duración misma de las llamadas.

Los csv son la información de los clientes y de los operadores respectivamente y se organiza tal que 

El dataset comprimido `telecom_dataset_us.csv` contiene las siguientes columnas:

- `user_id`: ID de la cuenta de cliente
- `date`: fecha en la que se recuperaron las estadísticas
- `direction`: "dirección" de llamada (`out` para saliente, `in` para entrante)
- `internal`: si la llamada fue interna (entre los operadores de un cliente o clienta)
- `operator_id`: identificador del operador
- `is_missed_call`: si fue una llamada perdida
- `calls_count`: número de llamadas
- `call_duration`: duración de la llamada (sin incluir el tiempo de espera)
- `total_call_duration`: duración de la llamada (incluido el tiempo de espera)

 

El conjunto de datos `telecom_clients_us.csv` tiene las siguientes columnas:

- `user_id`: ID de usuario/a
- `tariff_plan`: tarifa actual de la clientela
- `date_start`: fecha de registro de la clientela

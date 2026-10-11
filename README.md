# Recursos-humanos-de-una-empresa
Se realizan consultas SQL sobre un conjunto de datos de recursos humanos, cargándolo en una base SQLite para analizar satisfacción, evaluaciones y accidentes laborales por departamento.

Se realizaron consultas SQL sobre un conjunto de datos de recursos humanos, cargándolo en una base SQLite para analizar satisfacción, evaluaciones y accidentes laborales por departamento. Luego se leyó un CSV con pandas, se almacenó en la tabla “Detalle” de una base SQLite (RH.db) y se consultó con ORDER BY (satisfacción descendente), AVG con GROUP BY (promedio de la última evaluación por departamento) y HAVING (departamentos con promedio de accidentes > 0.15). 

Conclusiones: Para filtrar departamentos con más de 200 accidentes bastaría cambiar AVG por SUM, lo que muestra cómo las funciones de agregación y HAVING permiten resumir y filtrar datos por grupo.
